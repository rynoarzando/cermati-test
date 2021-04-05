<template>
  <section style="height: 100vh;">
      <v-layout white--text align-center column justify-center style="margin-top: 8.5em;">
        <h1 class="display-3 text-xs-center">Hello! I'm Ryno Arzando</h1>
        <h2 class="subheading">Consult, Design, and Develop Websites</h2>
        <h3 class="subtitle-1"> Have something great in mind? Feel free to contact me.</h3>
        <h3 class="subtitle-1"> I'll help you make it happen.</h3>
        <br>
        <v-flex row wrap text-xs-center>
          <v-btn 
          @mouseover="isHovering = true" 
          @mouseout="isHovering = false"
          class="hovering">{{ isHovering ? "Woot! Hovered" : "Hover over me" }}
            LET'S MAKE CONTACT</v-btn>
        </v-flex>
      </v-layout>
    </section>
</template>

<script>
export default {
    name: 'headerPage',

    data() {
    return {
      isHovering: false
    };
  }
}
</script>

<style>
.buttonHoverOff{
  color:transparent;
}
.buttonHoverOn{
  color:grey;
}
.hovering{
  color: red
}
</style>