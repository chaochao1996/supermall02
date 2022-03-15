<template>
  <div class="back-top">
    <img src="~assets/img/common/top.png" alt="回到顶部" />
  </div>
</template>

<script>
export default {
  name: "BackTop",
  data() {
    return {};
  },

  components: {},

  methods: {},
};
</script>

<style scoped>
.back-top {
  position: fixed;
  right: 16px;
  bottom: 72px;
  /* visibility: hidden; */
}
.back-top img {
  width: 48px;
}
</style>