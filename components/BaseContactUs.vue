<template>
  <div>
    <v-row>
      <v-container>
        <div align="center">
          <base-logo-index>REQUEST A PROPOSAL TODAY</base-logo-index>
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
              <vue-tel-input
                style="background-color:white"
                class="py-3"
              ></vue-tel-input>
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
            <!-- <v-hover v-slot:default="{ hover }">
                <v-btn max-width="500px" color="yellow"
                  :class="
                    (hover && 'white--text') + ' text-none no-background'
                  "
                  text
                  active-class="primary--text"
                  to="service"
                  v-on="on"
                  >REQUEST A PROPOSAL</v-btn
                >
            </v-hover> -->
            <v-col align="center">
              <v-btn max-width="500px" class="submit" color="yellow" >REQUEST A PROPOSAL</v-btn>
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
.submit:hover {
  background-color: #ffc107 !important;
  // color: white !important;
  .v-btn__content{
    color: blue;
  }
}
</style>
