<template>
  <main>
    <input type="text" v-model="currentNumber" />
    <div class="keys">
      <button class="op__key">C</button>
      <button class="op__key">+/-</button>
      <button class="op__key">%</button>
      <button class="op__key">/</button>
      <button class="num__key" @click="addNumber('7')">7</button>
      <button class="num__key" @click="addNumber('8')">8</button>
      <button class="num__key" @click="addNumber('9')">9</button>
      <button class="op__key">x</button>
      <button class="num__key" @click="addNumber('4')">4</button>
      <button class="num__key" @click="addNumber('5')">5</button>
      <button class="num__key" @click="addNumber('6')">6</button>
      <button class="op__key">-</button>
      <button class="num__key" @click="addNumber('1')">1</button>
      <button class="num__key" @click="addNumber('2')">2</button>
      <button class="num__key" @click="addNumber('3')">3</button>
      <button class="op__key">+</button>
      <span></span>
      <button class="num__key">0</button>
      <button class="num__key">.</button>
      <button class="eq__key">=</button>
    </div>
  </main>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      currentNumber: '',
    };
  },
  methods: {
    addNumber(number){
      this.currentNumber += number
    }
  }
};
</script>
