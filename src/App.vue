<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/header.vue'
</script>

<template>
<div class="header">
  <Header />
</div>
<div class="content">
  <RouterView />
</div>
  
</template>

<style scoped>
.header{
  width: 100%;
  height: 15dvh;
}

.content{
  width: 100%;
  height: 85dvh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
