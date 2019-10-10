<template>
    <v-container fluid class="container">
        <div class="wrap">
        <h1>About Me</h1>  
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.
             Aliquid hic a pariatur sunt minus, earum nemo dicta 
             dolore atque obcaecati repellat fuga neque quo 
             consequuntur fugit incidunt molestias voluptatem iure.
              Lorem ipsum dolor sit amet consectetur adipisicing 
              elit. Minima dolores, perferendis numquam quia 
              sapiente aut eos, tempora blanditiis, ex voluptatem 
              velit cumque inventore fugit consectetur quo. 
              Molestias minus corporis voluptate?</p>
        <v-btn id="button" dark ripple color="primary" max-width="150px">View Projects</v-btn>
         </div>     
    </v-container>
</template>

<script>

import {VBtn} from 'vuetify/lib'

export default {
  components: {
      VBtn
  },

  data: () => ({

  }),


}

</script>

<style scoped>

.container {
    background-color: black;
    height: 100vh;

}

.wrap {
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: 100%;
    padding: 0 5%;
}

.wrap h1 {
    font-family: 'Raleway', sans-serif;
    font-size: 3rem;
    font-weight: 700; 
    color: white;
    float: left;
    margin-bottom: 10px;
    

}

.wrap p {
    font-family: 'Raleway', sans-serif;
    color: white;
    font-size: 22px;
    margin-bottom: 50px;
    
    
}







</style>