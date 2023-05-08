<template>
  <div class="box m-3">
    <div class="columns">
      <div class="column is-8" role="form" aria-label="Formulário para nova tarefa">
        <input type="text" class="input" placeholder="Qual tarefa você deseja iniciar?">  
      </div>
      <div class="column">
        <div class="is-flex is-align-items-center">
          <div class="mr-3">
            <strong>
              {{ tempoEmSegundos }}
            </strong>
          </div>
          <button class="button mr-1" @click="iniciar">
            <span class="icon">
              <i class="fas fa-play"></i>
            </span>
            <span>play</span>
          </button>
          <button class="button" @click="pausar">
            <span class="icon">
              <i class="fa-solid fa-pause"></i>
            </span>
            <span>pause</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent } from 'vue'

  export default defineComponent({
    name:'TrackForm',
    data () {
      return {
        tempoEmSegundos: 0
      }
    },
    methods: {
      iniciar () {
        setInterval(() => {
          this.tempoEmSegundos += 1;
        }, 1000)
       
      },
      pausar () {
        console.log('pausa')
      }
    }
  })
</script>
<style lang="scss" scoped>

</style>