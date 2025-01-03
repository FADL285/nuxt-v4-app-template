<script setup lang="ts">
const items = [
  {
    label: 'Home',
    icon: 'i-lucide-house',
  },
  {
    label: 'Components',
    icon: 'i-lucide-box',
    to: '/components',
  },
  {
    label: 'Breadcrumb',
    icon: 'i-lucide-link',
    to: '/components/breadcrumb',
  },
]
</script>

<template>
  <div>
    <UBreadcrumb :items="items" />

    <h1>Home page</h1>
    <p>Content of the home page</p>
    <UButton color="neutral">
      Button
    </UButton>
  </div>
</template>

<style scoped></style>
