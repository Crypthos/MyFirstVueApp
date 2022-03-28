<template>
  <div class="about">
    <h1>About: My First Vue3 App</h1>
  </div>
  <div>
    <p v-show="inStock">In Stock</p>
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
</style>

<script>


</script>