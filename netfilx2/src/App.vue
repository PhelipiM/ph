<script setup>
import HeaderComp from '@/components/HeaderComp.vue';
import MainComp from './components/MainComp.vue';
</script>

<template>
    <HeaderComp/>
  <main>
    <MainComp/>
  </main>
  <RouterView />
</template>

<style ></style>
