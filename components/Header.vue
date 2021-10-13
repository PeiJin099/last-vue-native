<template>
    <view class="header">
        <Text class="title">{{ title }}</text>
    </view>
</template>

<script>
export default {
    props: ['title']
}
</script>

<style>
.header {
    height: 60px;
    background-color: #171717;
    align-items: center;
}
.title {
    padding-top: 5px;
    color: #F3F3F3;
    font-size: 28px;
    font-weight: 700;
    text-transform: uppercase;
}
</style>