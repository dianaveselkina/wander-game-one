<template>
  <div class="board">
    <h1>Игра бродилка</h1>
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
h1 {
  font-size: 4rem;
  font-style: italic;
  color: #5c564f;
}
.board {
  max-width: 2400px;
  height: 1800px;
  background-color: #d1c6bb;
  position: relative;
  margin: 2rem auto;
  border-radius: 3rem;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
}
</style>
