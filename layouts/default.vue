<template>
  <div class="flex min-h-screen">
    <sidebar class="fixed"/>
    <Nuxt />
  </div>
</template>

<script>
import sidebar from '~/components/sidebar.vue'

export default {
  components: {
    sidebar
  }
}
</script>
