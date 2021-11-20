<template>
  <button @click="evt => $emit('click', evt)">{{text}}o</button>
</template>

<script>
export default {
  name: 'Button',
  props: {
    text: String
  }
}
</script>

<style lang="scss" scoped>
@import "@/assets/scss/_colors.scss";
button {
background: $predominant;
border-radius: 10px;
padding: 5px 10px;
color: $white;
}
</style>
