<template>
  <div class="dark">
    <header><h1>Nuxt.js ハンズオン</h1></header>
    <nuxt />
    <footer><p>2018.11.17</p></footer>
  </div>
</template>
​
<style scoped>
header,
footer {
  width: 100%;
  text-align: center;
  background: rgb(15, 253, 15);
}
footer {
  position: fixed;
  bottom: 0;
  background: rgb(15, 253, 15);
}
​ .dark {
  background-color: #000;
  color: rgb(72, 46, 190);
}
</style>
