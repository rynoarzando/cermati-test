<template>
  <v-app>
    <v-app-bar
      app
      color="transparent"
      elevate-on-scroll
    >
      <div class="d-flex align-center">
        <v-img
          class="mx-2"
          src="https://i.imgur.com/TyaFz6K.png" 
          max-height="40"
          max-width="40"
          contain
        ></v-img>

  <v-toolbar-title class="ml-2">
    
  </v-toolbar-title>

        <!-- <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        /> -->
      </div>

      <v-spacer></v-spacer>

      <!-- <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn> -->
    </v-app-bar>

    <v-main>
      <headerPage/>
      <contentPage/>
      <footerPage/>
    </v-main>
  </v-app>
</template>

<script>
import headerPage from './components/headerPage';

export default {
  name: 'App',

  components: {
    headerPage
  },

  data: () => ({
    //
  }),
};
</script>

<style>
#app {
  background: url('https://i.imgur.com/yAi5pA7.jpg')
    no-repeat center center fixed !important;
  background-size: cover;
}
</style>
