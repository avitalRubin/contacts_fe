<template>
  <v-card
      fluid
      class="pa-0"
  >
    <v-row align="center">
      <v-col
          cols="12"
          sm="4"
      >
        <div class="text-center">
          <div class="ma-4">
            <v-avatar
                size="140"
            >
              <img
                  src="../assets/male-avatar.png"
                  alt="user"
              >
            </v-avatar>
          </div>
        </div>
        <div class="text-center">
          <div class="ma-4">
            avital
          </div>
        </div>
        <div class="text-center">
          <div class="ma-4">
            avit123
          </div>
        </div>
      </v-col>
      <v-col
          cols="12"
          sm="4"
      >
        <div class="text-center">
          <div class="my-2">
            full name
          </div>
          <div class="my-2">
            email
          </div>
          <div class="my-2">
            phone number
          </div>
          <div class="my-2">
            address
          </div>
        </div>
      </v-col>
      <v-col
          cols="12"
          sm="2"
      >
        <div class="text-center">
          <div class="ma-4">
            <v-btn
                block
                large
                color="primary"
                dark
            >
              info
            </v-btn>
          </div>

          <div class="ma-4">
            <v-btn
                block
                color="error"
                dark
                large
            >
              delete
            </v-btn>
          </div>
        </div>
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
export default {
}
</script>

<style scoped>

</style>