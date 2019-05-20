<template>
  <view class="statusbar" :style="{ backgroundColor: color }"></view>
</template>

<script>
export default {
  props: ['color']
}
</script>


<style>
.statusbar {
  height: 20px;
}
</style>

