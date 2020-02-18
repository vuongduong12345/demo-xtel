<template>
    <div>
      <v-card>
         <v-row>
        <v-col sm="4" >
                <v-img
                :src="va1"
              ></v-img>
          
        </v-col>
        <v-col sm="8" >
                <v-card-text class="pa-3">
                {{va2}}
                </v-card-text>
                <v-card-subtitle>
                {{va3}}
                </v-card-subtitle>
        </v-col>
        </v-row>
      </v-card>
      
    </div>
</template>
<script>
  export default {
      props:['va1','va2','va3',],
   
  }
</script>
<style>

</style>