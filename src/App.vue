<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <div class="app">
    {{firstName}}
    {{secondName}}
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
name: 'App',
components: {},
  data(){
    return{
      firstName:'Ласкин',
      secondName: 'Максим'
      }
    }
});
</script>

<style>

</style>
