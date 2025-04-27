<script>
const success = "text-success";
</script>
<template>
  <div>
    <!-- To handle the Kebab case use following syntax -->
    <h1 :class="$style['text-green']">Hello</h1>
    <!-- To handle the camel case use following syntax -->
    <p :class="$style.textBlue">This is an example.</p>

    <!-- If module has name then insted of $style use module name -->
    <p :class="moduleStyle['text-yellow']">This is an example Named module</p>
    <p :class="success">This is an example Bootstrap class</p>
  </div>
</template>
<!-- 
    CSS Modules in Vue provide a way to scope CSS styles locally to a component, preventing naming collisions and making CSS more maintainable. 
    To use CSS Modules in Vue, add the module attribute to the <style> tag in a single-file component:  
 -->
<style module>
.text-green {
  color: green;
}
.textBlue {
  color: blue;
}
</style>

<style module="moduleStyle">
.text-yellow {
  color: yellow;
}
</style>
