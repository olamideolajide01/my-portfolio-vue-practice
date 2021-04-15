<template>
  <div class="home">
    
    <v-sheet
    color="black"
    width="100%"
    class="max-auto" 

    >
    <v-row justify="center" align="center">

      <v-col 
      cols="12" sm="12" md="6" lg="4"
       class="text-center mt-14" >
        <div>
         <h2 class="red--text">HI THERE,</h2>
         <h1 class="white--text">I'm Olamide Olajide</h1>
         <p class="red--text">A Software Developer</p>
         
      </div>
            <div  >
        <a href="https://github.com/olamideolajide01" class="text-decoration-none">  <v-icon title="Github" color="white" class="mx-2"> mdi-github </v-icon></a>
        <a href="https://twitter.com/mideemmy01" class="text-decoration-none"> <v-icon title="Twitter" color="white" class="mx-2">mdi-twitter</v-icon></a>
         <a href="https://www.linkedin.com/in/olajide-olamide-a8198b201" class="text-decoration-none"> <v-icon title="LinkedIn" color="white" class="mx-2">mdi-linkedin</v-icon></a>
   
      </div>
      <div class="mt-10">
        <a  href="mailto:olajideseyi8181@gmail.com"  class="text-decoration-none"> 
           <v-btn large outlined color="teal"> Get In Touch </v-btn></a>
      </div>
        
      </v-col>

       <v-col cols="12" sm="12" md="6" lg="4" >
         
      <v-img
      transition="scroll-x-transition"
      src="last.jpg"
      height="600"
      width="600"
      contain 
      class=" mx-auto" 
      >
      </v-img>
      
      </v-col>
      </v-row>
    </v-sheet>
  </div>
</template>

<script>

export default {
  name: "Home",

  components: {
  
  },
};
</script>