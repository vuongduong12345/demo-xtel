<template>
  <div class="img-top">
    <v-img class="img" src="/home.jpg">
      <div class="text-top">
        <v-row align="center">
          <v-col class="text-center" cols="12">
            <div class="my-2">
              <p class="text1">Reliable & Affordable Outsourcing</p>
            </div>
            <div class="my-2">
              <p class="text1">Powered by Technology & Talented Teams</p>
            </div>
            <div class="my-2">
              <v-btn class="btn" color="primary">Talk to us</v-btn>
            </div>
          </v-col>
        </v-row>
      </div>
    </v-img>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.img-top {
  margin-top: 2px;
  width: 100%;
  height: 380px;
}
.img {
  height: 380px;
  background-size: cover;
}
.btn:hover {
  background-color: #007bff !important;
  //   color: white !important;
  span.v-btn__content {
    color: white !important;
  }
}
.text1 {
  color: #fff;
  font-weight: bolder;
  font-size: 28px;
}

.text-top {
  padding: 70px;
  //   .btn:hover {
  //     // color: red;
  //   }
}
</style>
