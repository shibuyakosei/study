<template>
  <div>
    <img src="item.img" />
    <p>{{ item.name }}</p>
    <p>{{ item.price }}</p>
  </div>
</template>

<script>
Vue.component("ice", {
  data: function () {
    return {
      img: "../../public/img/ガリガリ君.jpeg",
      name: "ガリガリ君ソーダ",
      price: "60円",
    };
  },
  template: `../../public/img/ガリガリ君.jpeg
  <p>{{ item.name }}</p>
  <p>{{ item.price }}</p>`,
});
</script>
