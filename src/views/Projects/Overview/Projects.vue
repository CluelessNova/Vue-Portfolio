<template>
    <TabMenu :model="items" :activeIndex="activeIndex" @tab-change="onTabChange" class="centered-tabs flex justify-content-center"></TabMenu>
    <component :is="items[activeIndex].component"></component>
</template>

<style src="./Projects.css"></style>
<script lang="ts" src="./Projects"></script>