<template>
  <div>
    <img class="ice" :src="img" />
    <p>{{ name }}</p>
    <p>{{ price }}</p>
    <ice></ice>
  </div>
</template>

<script>
import { ice } from "./ice_database.vue";
const name = "ガリガリ君";
const price = "60円";

export default {
  components: {
    ice,
  },
  data: function () {
    return {
      img: require("../../public/img/ガリガリ君.jpeg"),
      name,
      price,
    };
  },
};
</script>

<style></style>
