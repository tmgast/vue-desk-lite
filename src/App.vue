<template>
  <div class="ui">
    <Shelf/>
    <Drawer/>
  </div>
  <div id="nav">
    <router-link to="/">Home</router-link> |
  </div>
  <router-view/>
</template>

<script setup>
import Shelf from '@/components/Shelf.vue';
import Drawer from '@/components/Drawer.vue';
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
  background-color: #efefef;
  overflow: hidden;
}
</style>
