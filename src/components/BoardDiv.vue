<template>
  <div class="container">
    <div class="background"></div>
    <div class="circle">1</div>
    <div class="circle">2</div>
    <div class="circle">3</div>
    <div class="circle">4</div>
    <div class="circle">5</div>
    <div class="circle">6</div>
    <div class="circle">7</div>
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
    <div class="circle">13</div>
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
    <div class="circle">20</div>
    <div class="circle">21</div>
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
    <div class="circle">26</div>
    <div class="background">33</div>
    <div class="circle">32</div>
    <div class="circle">31</div>
    <div class="circle">A</div>
    <div class="circle">30</div>
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
  background-color: #d1c6bb;
  top: 128px;
  left: 17px;
  position: absolute;
  margin: 2rem;
  border-radius: 3rem;
  display: grid;
  gap: 50px 50px;
  grid-template-columns: repeat(8, 1fr);
  grid-template-rows: (1fr, 2fr, 1fr, 2fr, 1fr, 2fr);
  color: black;
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
  background-color: #d1c6bb;
  border: none;
}
</style>
