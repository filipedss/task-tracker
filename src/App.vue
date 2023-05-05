<template>
  <main class="columns is-gapeless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral/>
    </div>
    <div>
      
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue'
export default defineComponent({
  name: 'App',
  components: {
    BarraLateral
  }
});
</script>

<style>

</style>
