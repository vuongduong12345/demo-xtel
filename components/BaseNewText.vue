<template>
  <div>
    <v-col cols="12">
      <v-card to="/news/viet-nam" flat>
        <base-tech-new-image
          img="/technew.jpg"
          :title="'Việt Nam có thể trở thành cường quốc an ninh mạng'"
          :date="'2019-04-17'"
          :text1="
            'Tại Hội thảo về an toàn, an ninh mạng, BT Nguyễn Mạnh Hùng cho rằng, với nguồn nhân lực an ninh mạng vào loại tốt, với khát vọng dân tộc hùng cường'
          "
        ></base-tech-new-image>
      </v-card>
    </v-col>

    <v-col cols="12">
      <v-card to="/news/the-feds" flat>
        <base-tech-new-image
          img="/technew2.jpg"
          :title="
            'The Feds, Police Are Using Googles Location History Feature to Track Down Suspects'
          "
          :date="'2019-04-08'"
          :text1="
            'The Galaxy Fold represents more than eight years of design, engineering, and brand new tech, just to realize a phone with a flexible screen that works. We’re talking new malleable adhesives and complicated composite polymers made specifically to support the bendy display. And now after months of teasing, I’ve finally gotten a chance to check one out in the flesh. And despite its nearly $2,000 price tag, the Galaxy Fold is proof that the whole bendy phone trend could be more than just a fad.'
          "
        ></base-tech-new-image>
      </v-card>
    </v-col>
    <v-col cols="12">
      <v-card to="/news/damn" flat>
        <base-tech-new-image
          img="/technew3.jpg"
          :title="'Damn, Could the Samsung Galaxy Fold Be Worth It?'"
          :date="'2019-04-08'"
          :text1="
            'Law enforcement queries of Google’s massive mobile device Location History database, which employees call Sensorvault, has “risen sharply in the past six months,” the New York Times reported on Saturday, citing sources at the company.'
          "
        ></base-tech-new-image>
      </v-card>
    </v-col>
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
