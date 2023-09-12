<script setup>
import { ref } from 'vue'
const done = ref(true)
</script>

<template>
  <div>
    <div class="flex-container">
    <div class="flex-item-left"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1200px-Python-logo-notext.svg.png" width="80%"></div>
    <div class="flex-item-right"><img src="https://upload.wikimedia.org/wikipedia/commons/1/17/C_Sharp_Icon.png" width="80%">
    </div>
  </div>
  </div>
  <div>
    <hr>
    <form>
      <label>Request more Information</label><br>
      <input type="text">
      <button @click="done = !done" type="button" value="submit">Submit</button>
      <p v-if="done">Your Request has been submited</p>

    </form>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}

form{
  margin-left: 70px;
}

* {
  box-sizing: border-box;
}

.flex-container {
  display: flex;
  flex-direction: row;
  font-size: 30px;
  text-align: center;
}

.flex-item-left {
  padding: 10px;
  flex: 50%;
}

.flex-item-right {
  padding: 10px;
  flex: 50%;
}

/* Responsive layout - makes a one column-layout instead of two-column layout */
@media (max-width: 800px) {
  .flex-container {
    flex-direction: column;
  }
}
</style>
