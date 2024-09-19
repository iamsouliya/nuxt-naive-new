<script setup lang="ts">
  import { useMessage } from 'naive-ui'
  const message = useMessage()
</script>

<template>
  <div>
    <n-button @click="message.success('click')"> click </n-button>
  </div>
</template>
