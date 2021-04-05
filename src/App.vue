<template>
  <v-app>
    <v-main>
      <toolbar-page/>
      <headerPage/>
      <contentPage/>
      <footerPage/>
    </v-main>
  </v-app>
</template>

<script>
import headerPage from './components/headerPage';
import toolbarPage from './components/toolbarPage.vue';

export default {
  name: 'App',

  components: {
    headerPage,
    toolbarPage
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
