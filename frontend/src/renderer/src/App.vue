<template>
  <Header></Header>
  <div class="content-block">
    <section class="content softblock"></section>
    <section class="content softblock"></section>
    <section class="content softblock"></section>
  </div>
</template>

<script setup>
import Header from '@components/layouts/Header.vue'
</script>

<style lang="scss">
.content-block {
  display: grid;
  grid-template-columns: 0.3fr 2.2fr 0.5fr;
  column-gap: 10px;
  min-height: 800px;
  height: 100%;
}
</style>
