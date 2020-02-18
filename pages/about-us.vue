<template>
  <div>
    <base-bg-top :name="'ABOUT US'"></base-bg-top>
    <div class="container">
      <!-- WHO ARE WE-->
      <v-row>
        <v-container>
          <div align="center">
            <base-logo-index>WHO ARE WE</base-logo-index>
            <base-dirvider></base-dirvider>
          </div>
        </v-container>
      </v-row>
      <v-row>
        <div>
          <p align="center" class="text-about">
            Xtel Software Solution is an international software development
            company with the vision to become the global leading Company in
            Software Services, specified in Enterprise Web and Mobile app
            solutions.
          </p>

          <p align="center" class="text-about">
            Founded in 2015 by a small team of passionate minds, Xtel now has a
            balanced blend of technology skills and domain knowledge of seasoned
            IT professionals, powered by passion for Technology.
          </p>
          <div class="text-center "></div>
        </div>
      </v-row>
    </div>
    <!-- CORE MEMBERS -->
    <div>
      <v-row style="margin-bottom:10px;">
        <v-container>
          <div align="center">
            <base-logo-index>CORE MEMBERS</base-logo-index>
            <base-dirvider></base-dirvider>
          </div>
        </v-container>
      </v-row>
    </div>
    <div class="container">
        <v-row class="mb-6" no-gutters>
          <div class="core-center">
            <v-row>
              <v-col md="6" align="center">
            <div>
              <base-member img="/anhhung.jpg" :textmember1="'Hung Nguyen'" :textmember2="'CEO'"></base-member>
            </div>
          </v-col>
          <v-col md="6" align="center">
            <div>
              <base-member img="/ctrang.jpg" :textmember1="'Annie Nguyen'" :textmember2="'Deputy CEO'"></base-member>
            </div>
          </v-col>
            </v-row>
          </div>
        </v-row>
      </div>
    
    <!-- OUR INFOMATION-->
    <v-row>
      <v-container>
        <div align="center">
          <base-logo-index>OUR INFOMATION</base-logo-index>
          <base-dirvider></base-dirvider>
        </div>
      </v-container>
    </v-row>

     <v-container>
        <v-card class="pa-2" outlined>
          <v-row no-gutters>
            <v-col cols="4" md="2">
              <v-card class="pa-2" outlined tile height="80">
                <strong>Company Name</strong>
              </v-card>
              <v-card class="pa-2" outlined tile height="80">
                <strong>Head Office</strong>
              </v-card>
              <v-card class="pa-2" outlined tile height="80">
                <strong>Founded</strong>
              </v-card>
              <v-card class="pa-2" outlined tile height="80">
                <strong>Phone Number</strong>
              </v-card>
              <v-card class="pa-2" outlined tile height="80">
                <strong>Services</strong>
              </v-card>
              <v-card class="pa-2" outlined tile height="80">
                <strong>Employees</strong>
              </v-card>
            </v-col>
            <v-col cols="8" md="6">
              <v-card class="pa-2" outlined tile height="80">XTEL.,JSC</v-card>
              <v-card
                class="pa-2"
                outlined
                tile
                height="80"
              >5th floor, A-D buidling, No 15, Lane 82 Dich Vong Hau, Cau Giay, Ha Noi</v-card>
              <v-card class="pa-2" outlined tile height="80">2015</v-card>
              <v-card class="pa-2" outlined tile height="80">(+84)24 3200 3138</v-card>
              <v-card
                class="pa-2"
                outlined
                tile
                height="80"
              >Software Outsourcing, IT Outsourcing, Game Development....</v-card>
              <v-card class="pa-2" outlined tile height="80">50+</v-card>
            </v-col>
            <v-col align="Center" class="my-5">
              <v-img src="/image-about-us.png" width="250" height="220"></v-img>
            </v-col>
          </v-row>
        </v-card>
      </v-container>
    <base-maps></base-maps>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.avatar {
  // border: 1px solid #dee2e6 !important ;
  text-align: left;
}
.text-our {
  padding: 15px 0px 0px 20px;
  font-weight: bold;
}
.text-our1 {
  padding: 15px 0px 0px 10px;
}
.core-center {
  margin: auto;
}
// .container {
//   margin-top: -50px
// }
</style>
