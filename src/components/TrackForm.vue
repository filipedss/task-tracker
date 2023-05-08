<template>
  <div class="box">
    <div class="columns">
      <div class="column is-8" role="form" aria-label="Formulário para nova tarefa">
        <input type="text" class="input" placeholder="Qual tarefa você deseja iniciar?">  
      </div>
      <div class="column">
        <section>
          <strong>
            00:00:00
          </strong>
        </section>
        <button class="button">
          <span class="icon">
            <i class="fas fa-play"></i>
          </span>
          <span>play</span>
        </button>
        <button class="button">
          <span class="icon">
            <i class="fas fa-play"></i>
          </span>
          <span>pause</span>
        </button>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from 'vue'

  export default defineComponent({
    name:'TrackForm'
  })
</script>
<style lang="scss" scoped>

</style>