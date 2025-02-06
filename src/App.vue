<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div class="lila">
      <div class="kek"></div>
      <div class="kek"></div>
      <div class="kek"></div>
    </div>
  <div class="container">
    <div class="zold">

    </div>
  </div>
</template>

<style scoped>
.container{
  background-color: yellow;
  display: flex;
  height: 400px;
}
.lila{
  background-color: purple;
  display: flex;
  padding: 10px;

}
.kek{
  background-color: aqua;
  height: 30px;
  width: 100px;
  margin-right: 10px;
}
.zold{
  background-color: green;
}
</style>
