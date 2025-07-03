<template>
  <div class="flex min-h-screen ">
    <mycourse />
    <kanan class="col-span-3 px-4 py-4"/>
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
