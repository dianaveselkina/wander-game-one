<template>
  <button class="button"><slot></slot></button>
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
.button {
  cursor: pointer;
  z-index: 4;
  width: 540px;
  height: 120px;
  background-color: rgb(148, 148, 202);
  border-radius: 1rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-size: 50px;
}
</style>
