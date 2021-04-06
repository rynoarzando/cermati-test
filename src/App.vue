<template>
  <v-app>
    <v-main>
      <div class="blueDiv">
        <toolbar-page />
        <headerPage />
        <contentPage />
        <footerPage />
      </div>
    </v-main>
  </v-app>
</template>

<script>
import headerPage from "./components/headerPage";
import toolbarPage from "./components/toolbarPage.vue";

export default {
  name: "App",

  components: {
    headerPage,
    toolbarPage,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
#app {
  background: url("https://i.imgur.com/yAi5pA7.jpg") no-repeat center center
    fixed !important;
  background-size: cover;
}

.blueDiv {
  border: 0.1px outset rgb(3, 3, 49);
  opacity: 0.6;
  background-color: rgb(3, 3, 49);
  text-align: center;
}
</style>
