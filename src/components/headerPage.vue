<template>
  <section style="height: 100vh">
    <v-layout
      white--text
      align-center
      column
      justify-center
      style="margin-top: 8.5em"
    >
      <h1 class="display-3 text-xs-center">Hello! I'm Ryno Arzando</h1>
      <h2 class="subheading">Consult, Design, and Develop Websites</h2>
      <h3 class="subtitle-1">
        Have something great in mind? Feel free to contact me.
      </h3>
      <h3 class="subtitle-1">I'll help you make it happen.</h3>
      <br />
      <v-flex row wrap text-xs-center>
        <div class="custom-hover">
          <v-btn class="white--text transparent">
            <h5 class="custom-button">LET'S MAKE CONTACT</h5>
          </v-btn>
        </div>
      </v-flex>
    </v-layout>
  </section>
</template>

<script>
export default {
  name: "headerPage",

  data() {
    return {};
  },
};
</script>

<style scoped>
.custom-hover {
  background-color: rgb(3, 3, 49);
  border: thin solid white;
}

.custom-hover:hover {
  background-color: white;
  border: thin solid rgb(3, 3, 49);
}
.custom-button:hover {
  color: rgb(3, 3, 49);
}
</style>