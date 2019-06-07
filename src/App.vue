<template>
  <v-app>
    <v-toolbar app class="info" dark>
      <v-toolbar-side-icon @click="menu=!menu;"></v-toolbar-side-icon>
      <v-toolbar-title>Titulo</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn class="success" >Login</v-btn>
      <v-btn class="error" >Log out</v-btn>
    </v-toolbar>

    <v-navigation-drawer app v-model="menu">
        <v-list class="pa-0">
          <v-list-tile avatar>
            <v-list-tile-avatar>
              <img src="https://randomuser.me/api/portraits/men/85.jpg">
            </v-list-tile-avatar>

            <v-list-tile-content>
              <v-list-tile-title>Programador novato</v-list-tile-title>
            </v-list-tile-content>
          </v-list-tile>
        </v-list>
    </v-navigation-drawer>

    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  data () {
    return {
      menu:false
    }
  }
}
</script>
