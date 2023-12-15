<script setup lang="ts">
// Error when import by foo due to path alias usage
import { message } from '@/utils/message'
</script>

<template>
  <div>{{ message }}</div>
</template>
