<template>
  <div>
    <v-row >
      <v-img class="image" max-width="178"
  max-height="80" :src="img" contain> </v-img>
    </v-row>
  </div>
</template>
<script>
export default {
  props: ["img"]
};
</script>
<style lang="scss" scoped>
.image {
  text-align: center;
  padding: 0px 15px 48px;
}
</style>
