<template>
  <div class="bg-services">
    <base-bg-top :name="'SERVICES'"></base-bg-top>
    <div>
      <v-row>
        <v-container>
          <div align="center">
            <base-logo-index>SOFTWARE OUTSOURCING</base-logo-index>
            <base-dirvider></base-dirvider>
            <p class="text-sw">
              It is through our foresight and expertise, that we surpass our
              client’s expectations, achieving rapid returns on investment and
              build exponential growth.
            </p>
          </div>
          <div align="center" class="row-img">
            <v-row col="12">
              <v-col col-sm-6 class="rounder">
                <v-img class="rounder-img" src="/pageservice.png"></v-img>
                <p>OFFSHORE DEVELOPMENT</p>
                <p>
                  It is through our foresight and expertise, that we surpass our
                  client’s expectations, achieving rapid returns on investment
                  and build exponential growth.
                </p>
              </v-col>
              <v-col col-sm-6 class="rounder">
                <v-img class="rounder-img" src="/pageservice2.png"></v-img>
                <p>WEB APPLICATION DEVELOPMENT</p>
                <p>
                  We are not only a web development company but a trustworthy
                  partner as well. We deeply understand your tech needs and are
                  ready to provide you with secure, scalable and high-performing
                  web application development services.
                </p>
              </v-col>
            </v-row>
            <v-row cols="12">
              <v-col col-sm-6 class="rounder">
                <v-img class="rounder-img" src="/mobile.png"></v-img>
                <p>MOBILE APPLICATION DEVELOPMENT</p>
                <p>
                  Being a top innovative mobile app development company
                  recognised as Top 30 Mobile App Developers by Clutch in 2018,
                  we have been building both native and cross-platform mobile
                  applications using cutting-edge technologies and programming
                  languages.
                </p>
              </v-col>
              <v-col col-sm-6 class="rounder">
                <v-img class="rounder-img" src="/game.png"></v-img>
                <p>GAME MOBILE DEVELOPMENT</p>
                <p>
                  It is through our foresight and expertise, that we surpass our
                  client’s expectations, achieving rapid returns on investment
                  and build exponential growth.
                </p>
              </v-col>
            </v-row>

            <div class="text-center">
              <v-btn class="ma-2 about-button" outlined color="blue darken-1"
                >Case Study</v-btn
              >
            </div>
          </div>
        </v-container>
      </v-row>
      <v-row cols="12">
        <v-container>
          <div align="center">
            <base-logo-index>IT OUTSOURCING</base-logo-index>
            <base-dirvider></base-dirvider>
            <p class="text-sw">
              It is through our foresight and expertise, that we surpass our
              client’s expectations, achieving rapid returns on investment and
              build exponential growth.
            </p>
          </div>
          <div align="center" class="row-img">
            <v-row>
              <v-col  class="rounder" >
                <v-img class="rounder-img" src="/pageservice5.png"></v-img>
                <p>OFFSHORE DEVELOPMENT</p>
                <p>
                  It is through our foresight and expertise, that we surpass our
                  client’s expectations, achieving rapid returns on investment
                  and build exponential growth.
                </p>
              </v-col>
            </v-row>
            <div class="text-center">
              <v-btn class="ma-2 about-button" outlined color="blue darken-1"
                >Case Study</v-btn
              >
            </div>
          </div>
        </v-container>
      </v-row>
    </div>
  </div>

</template>
<script>
export default {};
</script>
<style lang="scss">
.bg-services {
  width: 100%;
  
    .page-name {
      font-size: 50px;
    }
}
.text-sw {
  font-size: 16px;
  margin: 13px 0px 16px;
}
.row-img {
  margin: 0px 15px;
  padding: 35px 0px;
  
  .rounder {
    // max-width: 50%;
    // max-height: 300px;
    // padding: 0px 15px;
    .rounder-img {
      width: 330px;
      height: 334px;
    }
  }
}
.about-button:hover {
  background-color: #007bff !important;
  color: white !important;
  span.v-btn__content {
    color: white !important;
  }
}
</style>
