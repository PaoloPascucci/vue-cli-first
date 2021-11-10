<template>
  <div id="app">
  <h1>
    <newTitle/>
  </h1>
  </div>
</template>

<script>
import newTitle from '@/components/newTitle.vue';

export default {
  
  components: {
    newTitle
  }
}
</script>

<style>
h1{
  text-align: center;
}
</style>
