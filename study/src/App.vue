<template>
  <div>
    <h2>商品一覧</h2>
    <p>トップページ > 商品一覧</p>
    <div>
      <garigari></garigari>
      <mikan></mikan>
      <homerun></homerun>
      <sugar></sugar>
      <parumu></parumu>
    </div>
  </div>
</template>

<script>
import garigari from "@/components/garigari.vue";
import mikan from "@/components/mikan.vue";
import homerun from "@/components/homerun.vue";
import sugar from "@/components/sugar.vue";
import parumu from "@/components/parumu.vue";

export default {
  components: {
    garigari,
    mikan,
    homerun,
    sugar,
    parumu,
  },
};
</script>
