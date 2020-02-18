<template>
  <div>
    <v-row>
      <v-container>
        <div align="center">
          <h1 class="h1">REQUEST A PROPOSAL TODAY</h1>
          <!-- <base-logo-index>REQUEST A PROPOSAL TODAY</base-logo-index> -->
          <base-dirvider></base-dirvider>
        </div>
      </v-container>
    </v-row>
    <div>
      <v-form class="bottom">
        <v-container>
          <v-row>
            <v-col cols="12" sm="6">
              <v-text-field
                label="Name"
                single-line
                outlined
                background-color="#fff"
              ></v-text-field>
            </v-col>

            <v-col cols="12" sm="6">
              <v-text-field
                label="Company Name"
                background-color="#fff"
                single-line
                outlined
              ></v-text-field>
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="12" sm="6">
              <v-text-field
                label="Work Email"
                background-color="#fff"
                single-line
                outlined
              ></v-text-field>
            </v-col>

            <v-col cols="12" sm="6">
             <client-only>
                <vue-tel-input
                style="background-color:white"
                class="py-3"
              ></vue-tel-input>
             </client-only>
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="12">
              <v-text-field
                label="How did you find us. Ex: Google."
                background-color="#fff"
                single-line
                outlined
              ></v-text-field>
            </v-col>
          </v-row>
          <v-row>
            <v-col cols="12">
              <v-textarea label="" background-color="#fff" single-line outlined>
              </v-textarea>
            </v-col>
          </v-row>
          <v-row>
            <v-col align="center">
              <v-btn max-width="500px" class="submit" color="yellow">REQUEST A PROPOSAL</v-btn>
            </v-col>
          </v-row>
        </v-container>
      </v-form>
    </div>
  </div>
</template>
<script>
import { VueTelInput } from "vue-tel-input";
export default {
  components: {
    VueTelInput
  }
};
</script>
<style lang="scss">
// .bottom {
//   background-color: #5a5de6;
// }
.h1 {
  padding-top: 50px;
  font-size: 32px;
  color: #fff;
  text-align: center;
  // background-color: #009cd7;
}
.submit:hover {
  background-color: #ffc107 !important;
  // color: white !important;
  .v-btn__content{
    color: blue;
  }
}
</style>
