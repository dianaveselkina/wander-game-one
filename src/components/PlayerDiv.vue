<template>
  <div class="player">
    <slot></slot>
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
.player {
  z-index: 6;
  width: 70px;
  height: 70px;
  position: absolute;
  top: 164px;
  left: 130px;
  background-color: rgba(201, 236, 42, 0.5);
  border-radius: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
