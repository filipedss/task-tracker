<template>
  <main class="columns is-gapeless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral/>
    </div>
    <div class="column is-three-quarter">
      <TrackForm/>
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue'
import TrackForm from './components/TrackForm.vue'
export default defineComponent({
  name: 'App',
  components: {
    BarraLateral,
    TrackForm
  }
});
</script>

<style>

</style>
