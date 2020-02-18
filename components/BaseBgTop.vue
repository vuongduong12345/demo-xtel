<template>
  <div class="bg-services">
    <div class="services">
      <h2>{{ name }}</h2>
      <p class="date">{{ date }}</p>
    </div>
  </div>
</template>
<script>
export default {
  props: ["name", "date"]
};
</script>
<style lang="scss">
.services {
  padding-top: 90px;
  text-align: center;
  text-decoration: none;
  color: #fff;
  height: 250px;
  background-image: linear-gradient(to right, #0584bc, #3ab2a2);
  .date {
    font-size: 12px;
  }
}
</style>
