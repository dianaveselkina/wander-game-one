<template>
  <div class="wheel__small"></div>
</template>
<script>
export default {
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.wheel__small {
  position: absolute;
  top: 0;
  left: 0;
  background-image: url(../img/wheel2.png);
  z-index: 7;
  background-repeat: no-repeat;
  background-size: cover;
  width: 700px;
  height: 700px;
}
</style>
