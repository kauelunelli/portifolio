<script setup lang="ts">
import { IconDarkMode, IconLinkedl } from './icons/index'
</script>
<template>
  <div>
    <div class="header-container">
      <div class="header-icon-container">
        <IconLinkedl class="icon" />
        <IconDarkMode class="icon" />
      </div>
    </div>
  </div>
</template>
<style scoped>
.header-container {
  background: rgb(241, 236, 236);
  width: 100%;
  max-height: 100px;
  padding: 0 1.5rem;
}
.header-icon-container {
  display: flex;
  justify-content: right;
}

.icon {
  margin: 12px 24px;
}
</style>
