<template>
    <v-container fill-height fluid class="px-0" style="margin-top: -0px;">
    <v-layout row wrap>
       <v-flex xs12 sm12 md4>
          <router-link to="/council">
        <v-card dark :color="color" height="100%" class="elevation-0 pt-4 pb-4 pl-3 box rule" >
         
         <h2 class="text-xs-center box-head">Find a Council</h2>
         
          <v-card-text class="px-3 font-weight-light box-text">
           Locate other criminal justice coordinating councils or similar groups across Illinois.
          </v-card-text>
         
        </v-card>
         </router-link>
      </v-flex>
       <v-flex xs12 sm12 md4>
         <router-link to="/what-we-offer">
        <v-card dark :color="color" height="100%" class="elevation-0 pt-4 pb-4 pl-3 box rule">
           <h2 class="text-xs-center box-head">What We Offer</h2>
          <v-card-text class="px-3 font-weight-light box-text ">
              Interested in crime trends and issues in your jurisdiction? Need assistance forming a criminal justice coordinating council? ICJIA can help.
          </v-card-text>
        </v-card>
         </router-link>
      </v-flex>
       <v-flex xs12 sm12 md4>
          <router-link to="/news">
        <v-card dark :color="color" height="100%" class="elevation-0 pt-4 pb-4 pl-3 box rule">
           <h2 class="text-xs-center box-head">News & Events</h2>
          <v-card-text class="px-3 font-weight-light box-text ">
               Find out the latest news and information relevant to Criminal Justice Coordinating Councils  
          </v-card-text>
        
        </v-card>
         </router-link> 
      </v-flex>
       
    </v-layout>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      color: '#E0E0E0'
    }
  }
}
</script>

<style scoped>
a {
  text-decoration: none !important;
}
.box:hover {
  background: #25274d !important;
}
.box:hover > * {
  color: #fff;
  cursor: pointer;
}
.box-head {
  font-size: 28px;
  text-transform: uppercase;
  color: #000;
}
.box-text {
  font-size: 18px;
  margin-top: -10px;
  color: #000;
}

.rule {
  border-bottom: 1px solid #ccc !important;
  border-top: 1px solid #ccc !important;
}
</style>