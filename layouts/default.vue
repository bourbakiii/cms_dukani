<template>
  <div class="layout default-layout">
    <Sidebar class="sidebar"/>
    <slot/>
  </div>
</template>

<style lang="scss">
.sidebar{
  height:100%;
}
</style>