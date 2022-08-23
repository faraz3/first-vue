<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="poto">
      <img alt="Vue logo" src="@/assets/foto.jpg" width="400" height="480" />
    </div>

    <!-- <div class="wrapper">
      <HelloWorld msg="You did it!" />

      
    </div> -->
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
  margin-left: 80px;
  display: flex;
  place-items: center;
  padding-right: calc(var(--section-gap) / 1);
}
</style>
