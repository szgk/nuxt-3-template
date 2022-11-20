<template>
  <header class="sm-header">
    <h1>{{ title }}</h1>
  </header>
</template>

<script setup lang="ts">
type Props = {
  title: string
}

const props = defineProps<Props>()
</script>

<style lang="scss">
.sm-header {
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
}
</style>
