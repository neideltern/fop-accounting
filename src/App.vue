<script setup lang="ts">
import { Button } from '@/components/ui/button'

import { useColorMode } from '@vueuse/core'
const mode = useColorMode()
mode.value = 'dark'
</script>

<template>
  <div>
    <Button>Click me</Button>
  </div>
</template>