<template>
  <div class="board">
    <MyButton
      v-if="spinVisibility"
      class="button"
      @click="removeWheel(), removeWheelBig()"
      >Крутить барабан</MyButton
    >
    <MyButton
      v-if="startVisibility"
      class="button"
      @click="deleteStartBtn(), addSpin(), addWhee(), addWheelBig()"
      >Начать игру</MyButton
    >
    <StartDiv></StartDiv>
    <PlayerDiv>1</PlayerDiv>
    <PlayerDiv class="player2">2</PlayerDiv>
    <div class="wheel__big" v-show="wheelBigVisibility">
      <transition name="rotate">
        <WheelDiv v-if="wheelVisibility" class="wheel"></WheelDiv>
      </transition>
    </div>
    <FinishDiv></FinishDiv>
    <BoardDiv></BoardDiv>
  </div>
</template>
<script>
import MyButton from './components/MyButton.vue';
import PlayerDiv from './components/PlayerDiv.vue';
import BoardDiv from './components/BoardDiv.vue';
import StartDiv from './components/StartDiv.vue';
import FinishDiv from './components/FinishDiv.vue';
import WheelDiv from './components/WheelDiv.vue';
export default {
  components: {
    MyButton,
    BoardDiv,
    StartDiv,
    FinishDiv,
    PlayerDiv,
    WheelDiv,
  },
  data() {
    return {
      startVisibility: true,
      wheelVisibility: false,
      spinVisibility: false,
      isRotate: false,
      wheelBigVisibility: false,
    };
  },
  methods: {
    deleteStartBtn() {
      this.startVisibility = false;
    },
    addSpin() {
      this.spinVisibility = true;
    },
    addWhee() {
      this.wheelVisibility = true;
    },
    addWheelBig() {
      this.wheelBigVisibility = true;
    },
    removeWheel() {
      this.wheelVisibility = false;
    },

    removeWheelBig() {
      this.wheel = setTimeout(() => {
        this.wheelBigVisibility = false;
      }, 2000);
    },
    wheelSpin() {},
  },
};
</script>
<style scoped>
.button {
  margin: 20px auto;
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
.player2 {
  background-color: rgba(236, 71, 42, 0.5);
  top: 268px;
  left: 130px;
}
.wheel {
  position: absolute;
  top: 1.5em;
  left: 1.5em;
  margin: 0;
  text-align: center;
}
.wheel__big {
  position: relative;
  background-image: url(img/wheel1.png);
  z-index: 10;
  background-repeat: no-repeat;
  background-size: cover;
  width: 750px;
  height: 750px;
}
.rotate-enter-active,
.rotate-leave-active {
  transition: all 2s ease-in-out;
}
.rotate-enter,
.rotate-leave-to {
  transform: rotate(180deg);
}
</style>
