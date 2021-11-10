<template>
  <div id="app">
  <h1>
    <newTitle/>
    <jumbo/>
  </h1>
  </div>
</template>

<script>
import newTitle from '@/components/newTitle.vue';
import jumbo from '@/components/jumbo.vue';

export default {
  
  components: {
    newTitle,
    jumbo
  }
}
</script>

<style>
h1{
  text-align: center;
}
</style>
