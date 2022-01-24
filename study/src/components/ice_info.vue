<template>
  <div>
    <img class="ice" :src="img" />
    <p>{{ name }}</p>
    <p>{{ price }}</p>
  </div>
</template>

<script>
const name = "ガリガリ君";
const price = "60円";
export default {
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
