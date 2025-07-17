<script setup lang="ts">
import Page from './components/Page.vue'
import Footbar from './components/Footbar.vue';
</script>

<template>
  <div>
    <a href="https://github.com/OOM-WG/SakitinSU">
      <img src="/logo.webp" class="logo"  alt="SakitinSU logo"/>
    </a>
  </div>
  <Page msg="SakitinSU"/>
  <br>
  <br>
  <div>
    <Footbar/>
  </div>
</template>

<style scoped>
.logo {
  height: 12em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
</style>
