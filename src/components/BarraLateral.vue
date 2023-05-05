<template>
<header>
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
</style>