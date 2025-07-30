<script setup lang="ts">
const params =  useRoute().params
const id = params.id as string
</script>

<template>
  <div>
    Id: {{ id }}
  </div>
</template>

