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
      <div class="apresentatation-subtitle">
        <h2>Web Developer</h2>
      </div>
      <div>
        <button class="btn btn-primary">Veja minha história</button>
      </div>
    </div>
    <div class="transaction"></div>
    <div class="about-container"></div>
    <div class="transaction"></div>
  </main>
</template>
<style scoped>
.apresentation-container {
  display: flex;
  justify-content: center;
  flex-direction: column;
  gap: 18px;
  height: 600px;
  max-width: 80%;
  margin: auto;
}
.apresentatition-title {
}

.background-subtitle {
  height: 32px;
  position: fixed;
  background: #714444;
  opacity: 20%;
}

.transaction {
  height: 20px;
  background: gray;
}

.about-container {
  height: 600px;
  background-color: #000000;
}
</style>
