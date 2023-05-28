<script setup>
import Langue from './components/langue.vue'
import Middle from './components/middle.vue'
</script>

<template>
  <div id="content">
    <Langue />
    <Middle />
  </div>
</template>

<style scoped>
#content {
  width: 100%;
  max-width: 768px;
  margin: 0px auto;
  background-color: #fff;
  min-height: 100vh
}
</style>
