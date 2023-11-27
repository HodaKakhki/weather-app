<template>
 <Suspense>
    <AsyncViewCity />
    <template #fallback>
      <p>Loading ...</p>
    </template>
 </Suspense>
</template>

<script setup>
import AsyncViewCity from '../components/AsyncCityView.vue'
</script>
