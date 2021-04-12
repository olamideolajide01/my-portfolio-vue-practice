<template>
<div class="pt-16 mt-16" id="projects">
    <div class="text-start pl-16">
  <h1 class="grey--text ">Some things I've Built</h1>
    </div>
    <v-row justify="center"  class="pa-16">
        <v-col cols="12" sm="6" md="6" lg="6" >
          <a  href="https://yoforiafoods.vercel.app"  class="text-decoration-none"> 
             <v-img
            transition="slide-x-transition"
            src="snap.jpg" 
            >
            </v-img></a>
        </v-col>
        <v-col cols="12" sm="6" md="6" lg="4"  class="ml-n16" >
            <div class="text-end">
            <p class="teal--text ">Featured project</p>
             <a  href="https://yoforiafoods.vercel.app"  class="text-decoration-none"> 
            <h3 class="teal--text ">Yoforiafoods</h3></a>
            </div>
    <v-card
    color="#1F7087"
    hover
    >
<v-card-subtitle class="white--text">A website app for checking out all kind of pastries and to take orders.
     </v-card-subtitle>
    </v-card>
    <p class=" teal--text text-end">Bootstrap </p>
   <p class=" teal--text text-end">Javascript </p>
   <p class=" teal--text text-end">HTML </p>
   <p class=" teal--text text-end">CSS </p>
        </v-col>    
    </v-row>

   
<v-row justify="center">
<v-btn  @click="show = !show" small color="teal" class="text-center">Show More</v-btn>
</v-row>
    <v-expand-transition>
      <div v-show="show"> 


<v-row justify="center"  class="pa-16 ">
        <v-col cols="12" sm="6" md="6" lg="4"  class="mr-n14">
 <div class="text-start">
            <p class="teal--text ">Featured project</p>
           <a  href="https://laemmyyummies.vercel.app"  class="text-decoration-none"> 
            <h3  class="teal--text">LaemmyYummies</h3></a>
            </div>
    <v-card
    color="#1F7087"
    hover
    >
<v-card-subtitle class="white--text">My first coding, a  website app for checking out all kind of pastries and take orders. </v-card-subtitle>
    </v-card>
    <p class=" teal--text text-start">HTML</p>
    <p class=" teal--text text-start">CSS </p>
        </v-col>
        <v-col cols="12" sm="6" md="6" lg="6">
       <a  href="https://laemmyyummies.vercel.app"  class="text-decoration-none">  <v-img
        transition="slide-x-transition"
        src="snap2.jpg"
            >
            </v-img></a>
        </v-col>
    </v-row>








    <v-row justify="center"  class="pa-16">
        <v-col  cols="12" sm="6" md="6" lg="6">        
    <a  href="https://yofopet.vercel.app"  class="text-decoration-none"> <v-img
     transition="slide-x-transition"
     src="snap3.jpg"
            >
          </v-img></a>
        </v-col>
        <v-col cols="12" sm="6" md="6" lg="4"  class="ml-n16" >
           <div class="text-end">
               <h2 class="yellow--text ">Ongoing</h2>
            <p class="teal--text ">Featured project</p>
           <a  href="https://yofopet.vercel.app"  class="text-decoration-none"> 
               <h3  class="teal--text ">YofoPets</h3></a>
            </div>
    <v-card
    color="#1F7087"
    hover
    >
<v-card-subtitle class="white--text">A Responsive E-commerce web and mobile App for Pets shopping, a store where you can purchase or order for pets</v-card-subtitle>

    </v-card>
    <p class=" teal--text text-end">Vue.js </p>
    <p class="teal--text text-end">Vuetify </p>
    <p class="teal--text text-end">Firebase </p>
        </v-col>
    </v-row>   
      </div>
    </v-expand-transition>

    
    
    </div>
</template>

<script>
    export default {
        name:"MyWork",
        data() {
            return {
                 show: false,
            }
        },
    }
</script>

