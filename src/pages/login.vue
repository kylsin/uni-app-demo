<template>
  <status-bar />
  <image :src="logo" mode="scaleToFill" />
</template>

<script lang="ts" setup>
import statusBar from '@/components/status-bar.vue'
const logo = `../static/logo/${import.meta.env.VITE_APP_LOGO}`
</script>
<style scoped lang="scss"></style>
