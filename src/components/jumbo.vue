<template>
<v-container fluid class="container">
        <v-img id='mainImg' src="../assets/code.jpg" height="500" gradient="to top right, rgba(33,33,33,.6), rgba(33,33,33,.9)">
        <h1>Tyson Elfors</h1>
        <h2>Web Developer & Designer</h2>
        </v-img>

</v-container>
</template>

<script>

import {VImg} from 'vuetify/lib'

export default {
  components: {
   VImg,
  },

  data: () => ({

  }),


}

</script>

<style scoped>

.container{
    margin: 0;
    padding: 0;
    position: relative;
}

.container h1 {
    position: absolute; 
    top: 35%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
}

.container h2 {
    position: absolute; 
    top: 42%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
};


</style>