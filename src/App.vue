<template>
 <v-app>
   <v-app-bar
   app
   flat
   color="grey lighten-5 "
   >
   <div class="text-center d-flex">
  <v-icon  color="teal" dark large class="mx-3">mdi-satellite-variant</v-icon>
   <h2  class="text-center"> oLA<span class="red--text">.</span>Mide</h2>
   </div>

<v-spacer></v-spacer>

    <span v-show="$vuetify.breakpoint.xsOnly" > <v-btn  @click="drawer=!drawer">
        <v-icon>mdi-menu</v-icon>
      </v-btn></span>
    <div  v-show="!$vuetify.breakpoint.xsOnly">
    <v-btn  class="mr-1"  small text > <a  @click="$vuetify.goTo('#about')">ABOUT</a></v-btn>
   <v-btn class="mr-1" small text><a  @click="$vuetify.goTo('#projects')">PROJECTS</a></v-btn>
   <v-btn class="mr-1" small text><a  @click="$vuetify.goTo('#contact')">CONTACT</a></v-btn>
   
  <!-- <a href="#"   class="text-decoration-none"> 
    <v-btn small class="mr-1" color="teal" outlined >Resume</v-btn></a> -->
   </div>
   </v-app-bar>


   <v-main class="ma-0  black">
     <router-view></router-view>
   </v-main>


      <v-navigation-drawer
      v-model="drawer"
      app
        temporary
        hide-overlay
        right
        class="black lighten-5" dark
        
        >
        <v-row justify="end"  class="mt-5 pr-6">
       <v-btn  @click="drawer=false">  <v-icon color="white">mdi-close</v-icon> </v-btn> 
          </v-row>

              <v-row  class="mt-5 text-center col-12" justify="center" dense >
                <v-col cols="12" class="ma-2">
                <v-btn class="mr-1 info--text" text > <a class="white--text"  @click="$vuetify.goTo('#about')">ABOUT</a></v-btn>
                </v-col>
                <v-col cols="12" class="ma-2">
                <v-btn class="mr-1 white--text" text ><a class="white--text" @click="$vuetify.goTo('#projects')">PROJECTS</a></v-btn>
                </v-col>
                <v-col cols="12" class="ma-2">
                <v-btn class="mr-1 amber--text" text ><a class="white--text" @click="$vuetify.goTo('#contact')">CONTACT</a></v-btn>
                </v-col>
                </v-row>
                <!-- <v-row justify="center" align="center" class="mt-3">
                  <a h ref="#"   class="text-decoration-none"> 
                <v-btn small class="mr-1" color="teal" outlined >Resume</v-btn></a>
                </v-row> -->
                    
            </v-navigation-drawer>

   
 </v-app> 
</template>

<script>
  export default {
    data() {
      return {
        drawer: false,
       
        
      }
    },

     computed: {
    
    mobile() {
      return this.$vuetify.breakpoint.smAndDown
    },
     },

    watch: {
      mobile(newValue) {
         if (!newValue) {
        this.hideDrawer()
      }
  },

    },

    methods: {
      hideDrawer(){
        this.drawer = false;
    },
     
     
    },
     }
</script>



