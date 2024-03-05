<template>
  <div class="start">
    <p>Start</p>
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
  font-size: 3rem;
  font-weight: bold;
  font-style: italic;
  color: #5c564f;
}
.start {
  min-width: 180px;
  height: 120px;
  position: absolute;
  bottom: 50px;
  left: 50px;
  background-color: #e2a66a;
  border-radius: 1rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
