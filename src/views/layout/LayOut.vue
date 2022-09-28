<template>
    <div>
        <!-- 主体内容 -->
        <router-view></router-view>
        <!-- 底部tabbar -->
        <tab-bar></tab-bar>
    </div>
</template>
<script lang="ts" setup>
import TabBar from "@/components/tabbar/TabBar.vue"
</script>