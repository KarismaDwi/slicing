<template>
  <div class="flex min-h-screen">
    <div class="flex-1 p-8 ml-64">
      <mycourse />
    </div>
    <kanan class="w-1/4 pr-6" />
  </div>
</template>

<script>
import mycourse from '~/components/mycourse.vue'
import kanan from '~/components/kanan.vue'

export default {
  components: {
    mycourse,
    kanan
  }
}
</script>
