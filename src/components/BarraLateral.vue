<template>
<header class="sideBar__header">
  <h1>
    <img id="sidebar-logo" src="@/assets/task-tracker-logo.svg" alt="" class="sideBar__logo">
  </h1>
</header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  setup () {
    return {}
  }
})
</script>

<style scoped>
  .sideBar__logo{
    width: 200px;
    height: auto;
  }

  .sideBar__header{
    background-color: #f1f1f1;
    height: 100vh;
    width: 100%;
    box-shadow: -1px 0px 6px rgba(0,0,0,.5);
    padding: 1rem 0 0 1rem;
  }
</style>