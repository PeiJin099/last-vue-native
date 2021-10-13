<template>
    <view class="container">
        <flat-list
        :data="[{key: 'a'}, {key: 'b'}]"
        :render-item="(item) => renderList(item)"
        />
    </view>
</template>

<script>
import React from 'react';
import {Text} from 'react-native';

export default {
methods: {
    renderList: function(item) {
        return (<Text>{item.item.key}</Text>)
    }
}
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
.container {
    bottom: 0px;
    position: relative;
    background-color: black;
    height: 60px;
}
</style>