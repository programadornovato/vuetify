<template>
  <v-container >
    <v-layout wrap>
      <v-flex class="primary" xs6 >
        6
      </v-flex>
      <v-flex class="error" xs6 >
        6
      </v-flex>
      <v-flex class="secondary" xs6 >
        6
      </v-flex>
      <v-flex class="success" xs6 >
        6
      </v-flex>
    </v-layout>


    <v-layout wrap justify-center align-center class="mt-5 secondary"  style="height:500px">
      <v-flex xs3 class="primary" >3</v-flex>
      <v-flex xs3 class="success" >3</v-flex>
      <v-flex xs3 class="error" >3</v-flex>
    </v-layout>
  </v-container>
</template>

<script>
  export default {
  }
</script>
