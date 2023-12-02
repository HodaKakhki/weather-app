<template>
 <Suspense>
    <AsyncViewCity />
    <template #fallback>
<CityViewSkeleton/> 
   </template>
 </Suspense>
</template>

<script setup>
import AsyncViewCity from '../components/AsyncCityView.vue'
</script>
