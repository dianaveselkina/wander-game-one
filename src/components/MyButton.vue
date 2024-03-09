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
.button:hover {
  box-shadow: 0 0 14px 14px rgba(57, 49, 133, 1.6);
}
</style>
