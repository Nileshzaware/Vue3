<script setup>
const gooleLink = "http://www.google.co.in/";

// Daynamic binding or Bind the multiple attributes
const link = {
  href: "http://www.google.co.in/",
  target: "_blank",
};
</script>

<template>
  <div>
    <!-- Binding syntax :attribute-name -->
    <a :href="gooleLink" target="_blank">Google Link</a>
    <!-- Also possible to bind with v-bind:attribute -->
    <!-- <a v-bind:href="gooleLink" target="_blank">Google Link</a> -->

    <!-- Dynamic binding with object -->
    <a :="link">Google Link</a>
  </div>
</template>

<style></style>
