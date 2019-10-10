<template>
    <v-container fluid class="container">
        <div class="wrap">
        <h1 data-aos="fade-up" data-aos-once="true" >About Me</h1>  
        <p data-aos="fade-up" data-aos-once="true" >Lorem ipsum dolor sit amet consectetur adipisicing elit.
             Aliquid hic a pariatur sunt minus, earum nemo dicta 
             dolore atque obcaecati repellat fuga neque quo 
             consequuntur fugit incidunt molestias voluptatem iure.
              Lorem ipsum dolor sit amet consectetur adipisicing 
              elit. Minima dolores, perferendis numquam quia 
              sapiente aut eos, tempora blanditiis, ex voluptatem 
              velit cumque inventore fugit consectetur quo. 
              Molestias minus corporis voluptate?</p>
        <v-btn data-aos="fade-up" data-aos-once="true" id="button" dark ripple max-width="150px">View Skills</v-btn>
         </div>     
    </v-container>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
AOS.init();


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
    color: #888;
    font-size: 22px;
    margin-bottom: 50px;
    max-width: 75%;
    
    
}







</style>