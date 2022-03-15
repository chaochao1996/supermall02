<template>
  <div class="nav-bar">
    <div class="left"><slot name="left"></slot></div>
    <div class="center"><slot name="center"></slot></div>
    <div class="right"><slot name="right"></slot></div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {};
  },

  components: {},

  methods: {},
};
</script>

<style scoped>
.nav-bar {
  display: flex;
  line-height: 44px;
  text-align: center;
  box-shadow: 0 2px 2px rgba(0, 0, 0, 0.15);
  position: fixed;
  right: 0;
  left: 0;
  top: 0;
}

.left,
.right {
  width: 60px;
  /* background-color: #f30; */
}

div:nth-child(2) {
  flex: 1;
}
</style>