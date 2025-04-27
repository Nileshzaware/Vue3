<script setup>
const name = "HelloWorld";
function add(x, y) {
  return x + y;
}
</script>

<template>
  <div>
    <h1>{{ name }}</h1>
    <h1>Add two number: {{ add(2, 10) }}</h1>
  </div>
</template>

<style></style>
