<template>
  <div class="start">
    <p>Finish</p>
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
p {
  font-style: italic;
  color: #fffefd;
  font-size: 3rem;
}
.start {
  z-index: 4;
  width: 240px;
  height: 182px;
  position: absolute;
  bottom: 50px;
  left: 50px;
  background-color: rgb(148, 148, 202);
  border-radius: 3rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
