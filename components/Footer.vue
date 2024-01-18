<script setup lang="ts">
import {version} from '../package.json'

const v = ref(version)
</script>

<template>
  <div class="mt-auto shrink-0 h-8">
    <div class="text-center text-xs font-light">
      V{{ v }}
    </div>
  </div>
</template>

<style scoped>

</style>