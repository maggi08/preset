<template>
  <div>Tickets</div>
</template>

<script lang="ts" setup>
import { useRoute } from 'nuxt/app';

const route = useRoute();

console.log(route.params);
</script>
