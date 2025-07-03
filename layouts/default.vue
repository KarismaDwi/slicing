<template>
  <div>
    <sidebar class="fixed col-span-2"/>
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
