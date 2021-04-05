<template>
  <v-toolbar dark absolute class="headerpage-toolbar">
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-img
          class="mx-2"
          src="https://i.imgur.com/TyaFz6K.png" 
          max-height="40"
          max-width="40"
          contain
        ></v-img>
      <v-spacer></v-spacer>
    </v-toolbar>
</template>

<script>
export default {
    name: 'toolbarPage',
}
</script>

<style>
.headerpage-toolbar {
  background: transparent !important;
  box-shadow: none !important;
}
</style>