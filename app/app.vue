<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script setup>
definePageMeta({
  layoutTransition: { name: 'page', mode: 'out-in' }, 
})
</script>

<style>

</style>