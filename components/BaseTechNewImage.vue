<template>
  <div>
    <v-row>
      <v-col md="4">
      <v-img max-height="150" width="100%" :src="img"></v-img>
    </v-col>
    <v-col md="8">
    <p class="text">{{ title }}</p>
    <p class="text">{{ date }}</p>
    <p class="text1">{{ text1 }}</p></v-col>
    </v-row>
  </div>
</template>
<script>
export default {
  props: ["img", "title", "date", "text1"]
};
</script>
<style lang="scss">
.text {
  font-size: 20px;
  margin: 0px 0px 12px;
  color: #007bff;
  &:hover {
    color: blue;
  }
}
.text1 {
  color: black;
  font-size: 13px;
  margin-top: 10px;
  &:hover {
    color: #007bff;
  }
}
</style>
