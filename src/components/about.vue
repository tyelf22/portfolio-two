<template>
    <v-container fluid class="aboutContainer">
        <div class="wrap">
        <h1 data-aos="fade-up" data-aos-once="true" data-aos-delay="100" >About Me</h1>  
        <p data-aos="fade-up" data-aos-once="true" data-aos-delay="200">Lorem ipsum dolor sit amet consectetur adipisicing elit.
             Aliquid hic a pariatur sunt minus, earum nemo dicta 
             dolore atque obcaecati repellat fuga neque quo 
             consequuntur fugit incidunt molestias voluptatem iure.
              Lorem ipsum dolor sit amet consectetur adipisicing 
              elit. Minima dolores, perferendis numquam quia 
              sapiente aut eos, tempora blanditiis, ex voluptatem 
              velit cumque inventore fugit consectetur quo. 
              Molestias minus corporis voluptate?</p>
        <v-btn data-aos="fade-in" data-aos-once="true" data-aos-delay="400" id="button" dark ripple max-width="150px">View Skills</v-btn>
         </div>     
    </v-container>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
AOS.init();

console.log(window.innerWidth);

import {VBtn} from 'vuetify/lib'

export default {
  components: {
      VBtn
  },

  data: () => ({

  }),


}

</script>


<style>

.aboutContainer {
    background-color: black;
    height: 95vh;

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
    margin-bottom: 15px;
    

}

.wrap p {
    font-family: 'Raleway', sans-serif;
    color: #888;
    font-size: 1rem;
    margin-bottom: 50px;


}
    
@media screen and (min-width: 600px) {
.wrap p {
    font-size: 1.4rem;
    max-width: 75%;
  }   

} 
    



</style>