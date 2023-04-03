<template>
  <v-app dark>
    <v-navigation-drawer
      v-model="drawer"
      fixed
      app
    >
    </v-navigation-drawer>
    <v-app-bar fixed app elevation="0" flat>
      <v-toolbar-title class="text-h5 font-weight-regular">
        Dashboard
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-col cols="12" sm="4">
        <v-text-field outlined dense prepend-inner-icon="mdi-magnify" class="mt-7"></v-text-field>
      </v-col>
      <v-btn outlined color="#FDD656" class="text-body-2" height="40">
        <v-icon left color="#FDD656">mdi-filter</v-icon> 
        <v-badge dot color="#D33864">
          Filters
        </v-badge>
      </v-btn>
      <v-btn class="pa-0 ml-3" color="#FDD656" min-width="40" height="40">
        <v-icon color="black">mdi-plus</v-icon>
      </v-btn>

      <v-btn color="transparent" elevation="0" min-width="40" height="40">
        <v-badge dot color="#D33864" overlap>
          <v-icon color="#FDD656">mdi-bell-outline</v-icon>
        </v-badge>
      </v-btn>

      <v-avatar size="40">
        <v-img src='https://cdn.vuetifyjs.com/images/john.jpg'></v-img>
      </v-avatar>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data() {
    return {
      drawer: true,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/',
        },
      ],
    }
  },

}
</script>

<style>
* {
  font-family: 'Ubuntu';
}
</style>
