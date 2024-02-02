<script lang='ts' setup>
/**
* Renders the sidebar and content areas
* @name 'PageIndex'
* @version 1.0.0
*/
</script>

<template lang="pug">
SidebarL.sidebarL
  aside Sidebar
  p content
</template>
<style lang='stylus' scoped>
.sidebarL
  min-block-size: 100%
  gap: var(--gap)
</style>
