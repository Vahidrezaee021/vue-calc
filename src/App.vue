<template>
  <main>
    <input type="number" value="0" />
    <div class="keys">
      <button class="op__key" op="clear">C</button>
      <button class="op__key" op="negate">+/-</button>
      <button class="op__key" op="percent">%</button>
      <button class="op__key" op="divide">/</button>
      <button class="num__key">7</button>
      <button class="num__key">8</button>
      <button class="num__key">9</button>
      <button class="op__key" op="multiply">x</button>
      <button class="num__key">4</button>
      <button class="num__key">5</button>
      <button class="num__key">6</button>
      <button class="op__key" op="subtract">-</button>
      <button class="num__key">1</button>
      <button class="num__key">2</button>
      <button class="num__key">3</button>
      <button class="op__key" op="add">+</button>
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
};
</script>
