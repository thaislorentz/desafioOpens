<template>
  <div id="app">
    <Landing />
  </div>
</template>

<script>
import Landing from './pages/Landing/Landing.vue'

export default {
  name: 'App',
  components: {
    Landing
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;500;600;700&display=swap");
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
  outline: none;
  -webkit-appearance: none;
}

body {
  background: #E5E5E5;
}

input {
  cursor: pointer;
}

button {
  cursor: pointer;
}

</style>
