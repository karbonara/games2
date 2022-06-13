<template>
  <div class="recomendation">
    <div class="recomendation__wrapper">
      <div class="recomendation__lists" v-for="item in items" :key="item">
        <div>
          {{ item.title }}
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      items: [
        { title: "MMORPG" },
        { title: "Шутер" },
        { title: "Казуальные" },
        { title: "MMORPG" },
        { title: "Шутер" },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "./recomendation.scss";
</style>