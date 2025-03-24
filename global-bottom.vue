<script setup lang="ts">
import { useNav } from '@slidev/client'
const { currentPage, total } = useNav()
</script>

<template>
  <footer class="absolute bottom-0 px-14 pb-4 pt-8 w-full flex">
    <div class="ml-auto text-xs text-gray-500">{{ currentPage }} / {{ total }}</div>
  </footer>
</template>