<template>
    <view class="statusbar" :style="{ backgroundColor: color }">
    <text></text>
    </view>
</template>

<script>
export default {
    props: ['color']
}
</script>

<style>
.statusbar {
  background-color: #FFCE00;
  height: 20px;
}