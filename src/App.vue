<script setup>
import Buttom from './components/buttom_up.vue'
import Middle from './components/middle.vue'
import Inputform from "@/components/inputform.vue";
</script>

<template>
  <div id="content">
    <Buttom />
    <Middle />
    <Inputform />
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
