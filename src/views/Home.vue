<template>
 <v-container fluid class="px-0">
<HeroBanner/>
<AboutMe/>
<MyWork/>
<ContactUs/>

 </v-container>
</template>

<script>
import HeroBanner from "@/components/HeroBanner"
import ContactUs from "@/components/ContactUs"
import AboutMe from "@/components/AboutMe"
import MyWork from "@/components/MyWork"
  export default {
    name:"Home",

    components:{
    HeroBanner,
    ContactUs,
    AboutMe,
    MyWork
    }
  }
</script>

