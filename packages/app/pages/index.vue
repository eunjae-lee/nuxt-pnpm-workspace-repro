<script setup lang="ts">
const { data } = await useFetch("/api/test");
</script>

<template>
  <div>Hello, {{ data?.name }}!</div>
</template>
