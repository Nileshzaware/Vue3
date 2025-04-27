<template>
  <div>
    <h1 class="text-red">Global Styling</h1>
    <p class="local">Trying local scop inthis component</p>
  </div>
</template>
<!-- Note: In scoped is not added the this style is applied on all other components -->
<style scoped>
.text-red {
  color: red;
}
</style>
