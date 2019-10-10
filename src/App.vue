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
    </v-content>
  </v-app>
</template>

<script>
import JumboTron from './components/jumbo'

export default {
  name: 'App',
  components: {
    JumboTron,
  
  },
  data: () => ({
    //
  }),
};
</script>

<style>

</style>