<template>
  <v-container grid-list-md >
    <v-layout wrap row>
      <v-flex xs12 sm6>
        <v-card>
          <v-img src="https://cdn.vuetifyjs.com/images/cards/desert.jpg">
          </v-img>
          <v-card-title>Lorem, ipsum dolor.</v-card-title>
          <v-card-text>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident eaque quos ad consequatur minus recusandae accusamus facere suscipit delectus, numquam, porro tenetur temporibus repudiandae vero rem voluptatem earum error excepturi?</v-card-text>
          <v-card-actions>
            <v-btn flat @click="dialog=true;">Accion</v-btn>
          </v-card-actions>
        </v-card>
      </v-flex>
      <v-flex xs12 sm6>
        <v-card>
          <v-img src="https://cdn.vuetifyjs.com/images/cards/desert.jpg">
          </v-img>
          <v-card-title>Lorem, ipsum dolor.</v-card-title>
          <v-card-text>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident eaque quos ad consequatur minus recusandae accusamus facere suscipit delectus, numquam, porro tenetur temporibus repudiandae vero rem voluptatem earum error excepturi?</v-card-text>
          <v-card-actions>
            <v-btn flat @click="dialog=true;">Accion</v-btn>
          </v-card-actions>
        </v-card>
      </v-flex>
      <v-flex xs12 sm6>
        <v-card>
          <v-img src="https://cdn.vuetifyjs.com/images/cards/desert.jpg">
          </v-img>
          <v-card-title>Lorem, ipsum dolor.</v-card-title>
          <v-card-text>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident eaque quos ad consequatur minus recusandae accusamus facere suscipit delectus, numquam, porro tenetur temporibus repudiandae vero rem voluptatem earum error excepturi?</v-card-text>
          <v-card-actions>
            <v-btn flat @click="dialog=true;">Accion</v-btn>
          </v-card-actions>
        </v-card>
      </v-flex>
      <v-flex xs12 sm6>
        <v-card>
          <v-img src="https://cdn.vuetifyjs.com/images/cards/desert.jpg">
          </v-img>
          <v-card-title>Lorem, ipsum dolor.</v-card-title>
          <v-card-text>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident eaque quos ad consequatur minus recusandae accusamus facere suscipit delectus, numquam, porro tenetur temporibus repudiandae vero rem voluptatem earum error excepturi?</v-card-text>
          <v-card-actions>
            <v-btn flat @click="dialog=true;">Accion</v-btn>
          </v-card-actions>
        </v-card>
      </v-flex>
    </v-layout>
    <v-dialog v-model="dialog" width="500" persistent >
        <v-card>
          <v-card-title>Lorem, ipsum dolor.</v-card-title>
          <v-card-text>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident eaque quos ad consequatur minus recusandae accusamus facere suscipit delectus, numquam, porro tenetur temporibus repudiandae vero rem voluptatem earum error excepturi?</v-card-text>
          <v-card-actions>
            <v-btn flat @click="dialog=false;" >Cerrar</v-btn>
          </v-card-actions>
        </v-card>
    </v-dialog>
  </v-container>
</template>

<script>
  export default {
    data(){
      return{
        dialog:false
      }
    }
  }
</script>
