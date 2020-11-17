<template>
  <div>
    <input v-model="result">
    <VueBarcode :value="result" />
  </div>
</template>

<script>
import VueBarcode from 'vue-barcode'

export default {

  components: {
    VueBarcode,
  },

  data() {
    return {
      result: 'testing',
    }
  },
}
</script>
