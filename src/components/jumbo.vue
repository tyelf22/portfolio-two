<template>
<v-container class="container">
        <v-img id='mainImg' src="../assets/code.jpg" height="95vh" gradient="to top right, rgba(33,33,33,.6), rgba(33,33,33,.9)"></v-img>
        <h1>Tyson Elfors</h1>
        <h2>Web Developer<br>and Designer</h2>
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
    text-align: center;
    color: white;

}

.container h1, h2 {
    font-family: 'Raleway', sans-serif;
}

.container h1 {
    position:absolute;
    top: 35%;
    left: 50%;
    transform: translate(-50%, -50%);
    white-space: nowrap;
    font-size: 3rem;
}

.container h2 {
    position:absolute;
    top: 43%;
    left: 50%;
    transform: translate(-50%, -50%);
    line-height: 25px;
    white-space: nowrap;
};


</style>