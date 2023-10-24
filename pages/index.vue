<script setup lang="ts">
const { data } = await useFetch("/api/test");
console.log("💡 data", data);
</script>

<template>
  <div>Hello, {{ data?.name }}!</div>
</template>
