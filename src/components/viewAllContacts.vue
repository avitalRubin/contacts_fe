<template>
  <div>
    <contactCard/> <!--todo - loop over contacts and send contact data to component-->
  </div>
</template>

<script>
import axios from 'axios';
import contactCard from '../components/contactCard';
export default {
  data() {
    return {
      contacts: {}
    };
  },
  components: {
    contactCard,
  },
  async created() {
    try {
      const response = await axios.get(
          "http://localhost:3000/get_contact_list"
      );
      // JSON responses are automatically parsed.
      this.contacts = response.data.contacts;
      console.log(this.contacts[0])
    } catch (error) {
      console.log(error);
    }
  }
}
</script>

<style scoped>

</style>