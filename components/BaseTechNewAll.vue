<template>
  <div>
    <v-col cols="12">
      <v-card to="/news/viet-nam">
        <base-tech-new-image
          img="/technew.jpg"
          :title="'Việt Nam có thể trở thành cường quốc an ninh mạng'"
          :date="'2019-04-17'"
        ></base-tech-new-image> </v-card
    ></v-col>
    <v-col cols="12"
      ><v-card to="/news/the-feds">
        <base-tech-new-image
          img="/technew2.jpg"
          :title="
            'The Feds, Police Are Using Googles Location History Feature to Track Down Suspects'
          "
          :date="'2019-04-08'"
        ></base-tech-new-image> </v-card
    ></v-col>
    <v-col cols="12"
      ><v-card to="/news/damn">
        <base-tech-new-image
          img="/technew3.jpg"
          :title="'Damn, Could the Samsung Galaxy Fold Be Worth It?'"
          :date="'2019-04-08'"
        ></base-tech-new-image> </v-card
    ></v-col>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.row-tech-new {
  margin-top: 20px;
}
</style>
