<script setup>
import { XIcon } from 'vue3-simple-icons'
import { ArrowRight } from 'lucide-vue-next'
</script>

<template>
  <a
    href="/"
    target="_blank"
    title="欢迎来到Sink！"
    class="inline-flex items-center px-3 py-1 mx-auto my-4 space-x-1 text-sm font-medium rounded-lg bg-muted"
  >
    <Separator
      orientation="vertical"
      class="h-4"
    />
    <span>Welcome to Sink!</span>
  </a>
</template>
