<template>
  <a-layout
    :style="{
      display: 'flex !important',
      flexDirection: 'column',
      minHeight: 'calc(100vh - 22px)'
    }"
    id="components-layout-demo-top"
    class="layout"
  >
    <HeaderComponent />
  </a-layout>
</template>

<script>
import HeaderComponent from './stubs/Header.vue'

export default {
  name: 'stubsComponents',
  components: {
    HeaderComponent,
  }
}
</script>
