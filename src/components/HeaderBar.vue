<script setup>

</script>

<template>
  <v-app-bar
    color="teal-darken-4"
    image="https://picsum.photos/1920/1080?random"
  >
    <template v-slot:image>
      <v-img
        gradient="to top right, rgba(19,84,122,.8), rgba(128,208,199,.8)"
      ></v-img>
    </template>

    <template v-slot:prepend>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </template>

    <v-app-bar-title>
      <v-btn to="/">Torino Cars</v-btn></v-app-bar-title>

    <v-spacer></v-spacer>

    <v-btn to="/about">
      Sobre Nosotros
    </v-btn>

    <v-btn icon="mdi-magnify">
      <v-icon icon="mdi-magnify"/>
    </v-btn>

    <v-btn icon>
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn icon="mdi-help" to="/help">
      <v-icon>mdi-help</v-icon>
    </v-btn>

    <v-btn icon>
      <v-icon>mdi-dots-vertical</v-icon>
    </v-btn>

  </v-app-bar>
</template>

<style scoped>

</style>