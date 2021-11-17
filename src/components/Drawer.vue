<template>
  <div class="drawer">
  </div>
</template>

<script setup>
</script>

<style type="scss">
  .drawer {
    position: relative;
    float: left;
    width: 200px;
    height: 1000px;
    top: 0;
    right: 0;

    background-color: #fefefe;
    box-shadow: 2px 2px 5px #999;
  }

  .drawer:after {
    content: '';
    position: absolute;
    left: 0;
    top: -10px;
    height: 10px;
    width: 120%;
    background-color: #fefefe;
  }
</style>
