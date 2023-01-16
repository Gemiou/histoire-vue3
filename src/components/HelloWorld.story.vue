<script setup>
import HelloWorld from './HelloWorld.vue';
</script>

<template>
  <Story title="Hello world">
    <Variant title="default" :initial-state="() => ({})">
      <template #default="{ state }">
        <HelloWorld />
      </template>
    </Variant>
  </Story>
</template>
