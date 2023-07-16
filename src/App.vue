<script setup lang="ts">
import { Icon, IconConfigProvider } from './vicons-utils'
import { Up, Youzan } from "../es";
</script>

<template>
  <Icon color="red" size="48">
    <Up />
  </Icon>
  <IconConfigProvider color="red" size="48">
    <Icon>
      <Up />
    </Icon>
  </IconConfigProvider>
  <Icon color="red" size="48">
    <Youzan />
  </Icon>
</template>

<style scoped>
</style>
