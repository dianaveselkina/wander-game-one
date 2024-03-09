<template>
  <div class="wheel__small">
    <div class="wheel__big"></div>
  </div>
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
.wheel__big {
  position: relative;
  background-image: url(../img/wheel1.png);
  z-index: 8;
  background-repeat: no-repeat;
  background-size: cover;
  width: 700px;
  height: 700px;
}
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
