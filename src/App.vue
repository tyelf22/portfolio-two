<template>
  <v-app>
    <v-app-bar dark color="primary" app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Tyson</span>
        <span class="font-weight-light">Elfors</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-app-bar>

    <v-content>
      <jumbo-tron></jumbo-tron>
      <about-me></about-me>
    </v-content>
  </v-app>
</template>

<script>
import JumboTron from './components/jumbo'
import AboutMe from './components/about'

export default {
  name: 'App',
  components: {
    JumboTron,
    AboutMe,
  
  },
  data: () => ({
    //
  }),
};
</script>

<style>

</style>