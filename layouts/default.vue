<template>
  <div class="flex">
    <Sidebar class="fixed"/>
  <div class="flex-1 p-8 min-h-screen">
    <Nuxt />
  </div>
  </div>
</template>

<script>
import Sidebar from '~/components/sidebar.vue'

export default {
  components: {
   Sidebar
  }
}
</script>
