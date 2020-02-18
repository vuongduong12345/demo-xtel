<template>
  <div>
    <base-home-img-top></base-home-img-top>

    <div class="container">
      <!-- ABOUT US -->
      <v-row>
        <v-container>
          <div align="center">
            <base-logo-index>ABOUT US</base-logo-index>
            <base-dirvider></base-dirvider>
          </div>
        </v-container>
      </v-row>
      <v-row>
        <div>
          <p align="center">
            Xtel Software Solution is an international software development
            company with the vision to become the global leading Company in
            Software Services, specified in Enterprise Web and Mobile app
            solutions.
          </p>

          <p align="center">
            Founded in 2015 by a small team of passionate minds, Xtel now has a
            balanced blend of technology skills and domain knowledge of seasoned
            IT professionals, powered by passion for Technology.
          </p>
          <div class="text-center ">
            <v-btn to="/about-us" class="ma-2 about-button" outlined color="blue darken-1"
              >View More</v-btn
            >
          </div>
        </div>
      </v-row>
    </div>
    <br />

    <!-- COMPANY -->
    <v-row>
      <v-container>
        <div align="center">
          <base-logo-index>COMPANY</base-logo-index>
          <base-dirvider></base-dirvider>
        </div>
      </v-container>
    </v-row>

    <v-row>
      <v-col cols="6" sm="3" align="center">
        <v-icon size="90" color="#009CD7">mdi-calendar-remove</v-icon>
        <p class="company-text" style="font-size:35px">2015</p>
        <p class="company-text">Since</p>
      </v-col>
      <v-col cols="6" sm="3" align="center">
        <v-icon size="90" color="#009CD7">mdi-apps</v-icon>
        <p class="company-text" style="font-size:35px">30+</p>
        <p class="company-text">Customers</p>
      </v-col>
      <v-col cols="6" sm="3" align="center">
        <v-icon size="90" color="#009CD7">mdi-projector</v-icon>
        <p class="company-text" style="font-size:35px">40+</p>
        <p class="company-text">Projects</p>
      </v-col>
      <v-col cols="6" sm="3" align="center">
        <v-icon size="90" color="#009CD7">mdi-account-group</v-icon>
        <p class="company-text" style="font-size:35px">50+</p>
        <p class="company-text">Employees</p>
      </v-col>
    </v-row>

    <!-- OUR SERVICES -->
    <v-row>
      <v-container>
        <div align="center">
          <base-logo-index> OUR SERVICES</base-logo-index>
          <base-dirvider></base-dirvider>
        </div>
      </v-container>
    </v-row>

    <v-row>
      <v-col align="center" cols="12" sm="6">
        <v-img max-width="140" src="/service.png"></v-img>
        <p>SOFTWARE OUTSOURCING</p>
        <p>
          It is through our foresight and expertise, that we surpass our
          client’s expectations, achieving rapid returns on investment and build
          exponential growth.
        </p>
      </v-col>
      <v-col align="center" cols="12" sm="6">
        <v-img max-width="140" src="/service2.png"></v-img>
        <p>IT OUTSOURCING</p>
        <p>
          It is through our foresight and expertise, that we surpass our
          client’s expectations, achieving rapid returns on investment and build
          exponential growth.
        </p>
      </v-col>
    </v-row>
    <div class="text-center ">
      <v-btn to="/service" class="ma-2 about-button" outlined color="blue darken-1"
        >View More</v-btn
      >
    </div>

    <!-- TECH STACK -->
    <v-row>
      <v-container>
        <div align="center">
          <base-logo-index>TECH STACK</base-logo-index>
          <base-dirvider></base-dirvider>
        </div>
      </v-container>
    </v-row>

    <div class="container">
      <v-row align="center">
        <v-col sm="3"><base-img img="/tech1.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech2.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech3.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech4.png"></base-img></v-col>
      </v-row>

      <v-row align="center">
        <v-col sm="3"><base-img img="/tech5.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech6.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech7.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech8.png"></base-img></v-col>
      </v-row>

      <v-row align="center">
        <v-col sm="3"><base-img img="/tech9.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech10.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech11.png"></base-img></v-col>
        <v-col sm="3"><base-img img="/tech12.png"></base-img></v-col>
      </v-row>
    </div>

    <!-- OUR PARTNERS -->
    <v-row>
      <v-container>
        <div align="center">
          <base-logo-index>OUR PARTNERS</base-logo-index>
          <base-dirvider></base-dirvider>
        </div>
      </v-container>
    </v-row>

    <v-row>
      <v-col sm="3"><base-img img="/thailand.png"></base-img></v-col>
      <v-col sm="3"><base-img img="/united.png"></base-img></v-col>
      <v-col sm="3"><base-img img="/poland.png"></base-img></v-col>
      <v-col sm="3"><base-img img="/singapore.png"></base-img></v-col>
    </v-row>

    <v-row>
      <v-col sm="4"><base-img img="/vietnam.png"></base-img></v-col>
      <v-col sm="4"><base-img img="/japan.png"></base-img></v-col>
      <v-col sm="4"><base-img img="/korea.png"></base-img></v-col>
    </v-row>

    <!-- TECH NEWS -->
    <v-row>
      <v-container>
        <div align="center">
          <base-logo-index>TECH NEWS</base-logo-index>
          <base-dirvider></base-dirvider>
        </div>
      </v-container>
    </v-row>
    <v-container>
      <v-row>
        <v-col md="8">
          <base-tech-new-all></base-tech-new-all>
        </v-col>
      </v-row>
    </v-container>

    <!-- REQUEST A PROPOSAL TODAY -->

    <base-today class="primary"></base-today>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import VuetifyLogo from "~/components/VuetifyLogo.vue";

export default {
  components: {
    Logo,
    VuetifyLogo
  }
};
</script>
<style lang="scss">
.about-button:hover {
  background-color: #007bff !important;
  color: white !important;
  span.v-btn__content {
    color: white !important;
  }
}
</style>
