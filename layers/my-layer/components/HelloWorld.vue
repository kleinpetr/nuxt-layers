<script setup lang="ts">
const { myLayer } = useAppConfig()
</script>

<template>
  <div>
    <h1>Hello World!</h1>
    <pre>{{ myLayer }}</pre>
    <div>
      <div class="my-red-bg">
        This should have red background
      </div>
    </div>
  </div>
</template>
