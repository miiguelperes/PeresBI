<template>
  <div id="app">
    <v-toolbar fixed inverted-scroll>
      <v-toolbar-title>
        <a href="#" v-scroll-to="'#top'">
        <img src="static/peres.svg" alt="Vuetify.js"  class="logo-main" height="45">
        </a>
        </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat>Sobre</v-btn>
        <v-btn flat>Portifólio</v-btn>
        <v-btn flat>Carreiras</v-btn>
        <v-btn flat>Contato</v-btn>
      </v-toolbar-items>
      <v-toolbar-side-icon></v-toolbar-side-icon>
    </v-toolbar>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>

@media only screen and (max-width: 600px) {
  .top-one .v-parallax__image {
    top: 0 !important;
    height: 127% !important;
  }
}
.top-one .v-parallax__image {
    top: 0 !important;
  }
#particles-js {
  height: 100%;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.v-btn .v-btn__content .v-icon {
    color: #0a406d;
}
</style>
