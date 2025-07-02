<template>
  <div class="flex min-h-screen">
    <sidebar class="w-1/4" />
    <div class="flex-1 p-8">
      <mycourse />
    </div>
    <kanan class="w-1/4 pr-6" />
  </div>
</template>

<script>
import sidebar from '~/components/sidebar.vue'
import mycourse from '~/components/mycourse.vue'
import kanan from '~/components/kanan.vue'

export default {
  components: {
    sidebar,
    mycourse,
    kanan
  }
}
</script>
