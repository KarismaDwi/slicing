<template>
  <div class="max-w-7xl mx-auto px-6 grid grid-cols-12 gap-5">
    <MyCourse class="col-span-9" />
    <Kanan class="col-span-3" />
  </div>
</template>

<script>
import MyCourse from '~/components/mycourse.vue'
import Kanan from '~/components/kanan.vue'

export default {
  components: {
    MyCourse,
    Kanan
  }
}
</script>
