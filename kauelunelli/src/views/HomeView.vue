<script setup lang="ts">
import Header from '../components/Header.vue'
</script>

<template>
  <main>
    <Header />
    <div class="apresentation-container">
      <div class="apresentatition-title">
        <h1>Kauê Lunelli</h1>
      </div>
      <div class="apresentatition-title">
        <h2>Web Developer</h2>
      </div>
      <div class="apresentatition-title">
        <h1>Texto</h1>
      </div>
    </div>
  </main>
</template>
<style scoped>
.apresentation-container {
  display: flex;
  justify-content: center;
  height: 800px;
  max-width: 80%;
  margin: auto;
}
.apresentatition-title {
}
</style>
