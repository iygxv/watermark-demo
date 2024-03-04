<template>
  <div class="hello-world-page">
   <button @click="createWaterMark">生成水印</button>
  </div>
</template>

<script>
import watermark from '@/utils/waterMark'
export default {
  data() {
    return {
    }
  },
  methods: {
   createWaterMark() {
     watermark()
   }
  }
}
</script>

<style lang='scss' scoped>
.hello-world-page {
  width: 100vw;
  height: 100vh;
}
</style>
