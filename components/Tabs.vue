<template>
  <i-tabs v-model="active" color="light">
    <template #header>
      <i-tab-title for="tab-1">
        Tab 1
      </i-tab-title>
      <i-tab-title for="tab-2">
        Tab 2
      </i-tab-title>
      <i-tab-title for="tab-3">
        Tab 3
      </i-tab-title>
    </template>

    <i-tab name="tab-1">
      Tab 1 content
    </i-tab>
    <i-tab name="tab-2">
      Tab 2 content
    </i-tab>
    <i-tab name="tab-3">
      Tab 3 content
    </i-tab>
  </i-tabs>

  <i-tabs v-model="active" color="dark">
    <template #header>
      <i-tab-title for="tab-1">
        Tab 1
      </i-tab-title>
      <i-tab-title for="tab-2">
        Tab 2
      </i-tab-title>
      <i-tab-title for="tab-3">
        Tab 3
      </i-tab-title>
    </template>

    <i-tab name="tab-1">
      Tab 1 content
    </i-tab>
    <i-tab name="tab-2">
      Tab 2 content
    </i-tab>
    <i-tab name="tab-3">
      Tab 3 content
    </i-tab>
  </i-tabs>
</template>

<script setup lang="ts">
const active = ref('tab-1')
</script>
