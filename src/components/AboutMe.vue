<template>

<div class="mx-auto pt-16" id="about">
    <v-row justify="center"  >
 <h1 class= "grey--text text--lighten-2">
          <span class="teal--text" style="font-size:60px">A</span>bout Me  
         </h1>
    </v-row  >
 <v-row justify="space-around"  class="mx-auto">
         <v-col cols="12" sm="12" md="6" lg="6" class="pl-16" >
   <p class="white--text mr-12"> Hello! My name is Olamide, i'm a Nigerian-Based software developer and I enjoy creating things that live on the internet. i started  teaching myself alot about HTML & CSS in 2011 when i took interest in Coding..</p>
   <p class="white--text">
   Fast-forward to today,  i've had the opportunities of creating website apps with different technologies.. My main focus these days is building accessible and a user experience products for a variety of clients.</p>
  <p class="white--text"> Here are a few technologies I've been working with recently:</p>
  
  <ul class="white--text mx-auto">
    <li>JavaScript (ES6+)</li> 
   <li>Vue</li> 
   <li>Node.js</li> 
    <li> WordPress</li> 
</ul>
     </v-col>

     <v-col 
     cols="12" sm="12" md="6" lg="6"
     class="text-center mx-auto">
         <v-img
         src="port.png"
         height="400"
         width="400"
         class="mr-12  mx-auto"
         contain
          >

         </v-img>
     </v-col>
 </v-row>
 </div> 
</template>

<script>
    export default {
        name:"AboutMe"
    }
</script>

