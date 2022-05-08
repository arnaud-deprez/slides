<script setup lang="ts">
import { ref } from "vue";
</script>

<template>
  <footer class="absolute bottom-0 px-14 pb-4 pt-8 w-full flex">
    <div class="ml-auto text-xs text-gray-500">{{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}</div>
  </footer>
</template>