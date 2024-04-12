<template>
  <div></div>
</template>

<script setup>
import axios from 'axios';
axios.get('http://localhost:3000/').then((res) => {
  console.log(res);
});
</script>

<style lang="scss" scoped></style>
