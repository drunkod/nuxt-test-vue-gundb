<script setup lang="ts">
import { ChatRoom } from '@gun-vue/components'
</script>

<template>
    <div>
      ChatRoom
      <client-only><ChatRoom /></client-only>
      
    </div>
  </template>