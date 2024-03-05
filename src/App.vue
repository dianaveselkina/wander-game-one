<template>
  <div class="board">
    <h1>Игра бродилка</h1>
    <StartDiv></StartDiv>
    <FinishDiv></FinishDiv>
    <BoardDiv></BoardDiv>
  </div>
</template>
<script>
import BoardDiv from './components/BoardDiv.vue';
import StartDiv from './components/StartDiv.vue';
import FinishDiv from './components/FinishDiv.vue';
export default {
  components: {
    BoardDiv,
    StartDiv,
    FinishDiv,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style>
h1 {
  font-size: 4rem;
  font-style: italic;
  color: #5c564f;
}
.board {
  max-width: 2400px;
  height: 1800px;
  background: radial-gradient(
    circle,
    rgba(66, 66, 199, 0.7987570028011204) 9%,
    rgba(4, 113, 189, 1) 31%,
    rgba(0, 212, 255, 1) 60%,
    rgba(226, 244, 247, 1) 89%
  );
  position: relative;
  margin: 4rem auto;
  border-radius: 3rem;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
}
</style>
