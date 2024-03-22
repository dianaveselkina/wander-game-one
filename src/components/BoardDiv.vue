<template>
  <div class="container">
    <div class="background"></div>
    <div class="circle">1</div>
    <div class="circle">2</div>
    <div class="circle">3</div>
    <div class="circle">4</div>
    <div class="circle5">5</div>
    <div class="circle">6</div>
    <div id="7" class="circle7">7</div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="circle">8</div>
    <div class="circle">16</div>
    <div class="circle">15</div>
    <div class="circle">14</div>
    <div class="circle13">13</div>
    <div class="circle">12</div>
    <div class="circle">11</div>
    <div class="circle">10</div>
    <div class="circle">9</div>
    <div class="circle">17</div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="circle">18</div>
    <div class="circle">19</div>
    <div class="circle20">20</div>
    <div class="circle21">21</div>
    <div class="circle">22</div>
    <div class="circle">23</div>
    <div class="circle">24</div>
    <div class="circle">25</div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="background"></div>
    <div class="circle26">26</div>
    <div class="background"></div>
    <div class="circle">33</div>
    <div class="circle">32</div>
    <div class="circle">31</div>
    <div class="circle30">30</div>
    <div class="circle">29</div>
    <div class="circle">28</div>
    <div class="circle">27</div>
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
.container {
  z-index: 3;
  opacity: 0.5;
  width: 2300px;
  height: 1590px;
  background: radial-gradient(
    circle,
    rgba(66, 66, 199, 0.7987570028011204) 9%,
    rgba(4, 113, 189, 1) 31%,
    rgba(0, 212, 255, 1) 60%,
    rgba(226, 244, 247, 1) 89%
  );
  top: 128px;
  left: 17px;
  position: absolute;
  margin: 2rem;
  border-radius: 3rem;
  display: grid;
  gap: 50px 50px;
  grid-template-columns: repeat(8, 1fr);
  grid-template-rows: (1fr, 2fr, 1fr, 2fr, 1fr, 2fr);
  font-style: italic;
  font-weight: bold;
  color: #020202;
  font-size: 3rem;
}
.container * {
  display: flex;
  border: 1px solid;
  border-radius: 50px;
  background-color: rgba(82, 29, 179, 0.5);
  text-align: center;
  align-items: center;
  padding: 10px;
}
.background {
  opacity: 0;
  border: none;
}
.circle5,
.circle20,
.circle30 {
  background-color: green;
}
.circle21 {
  background-color: blue;
}
.circle7 {
  background-color: yellow;
}
.circle13,
.circle26 {
  background-color: red;
}
</style>
