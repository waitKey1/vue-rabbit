<script setup>
import LayoutNav from './components/Nav/index.vue'
import LayoutHeader from './components/Header/index.vue'
import LayoutFooter from './components/Footer/index.vue'
</script>

<template>
<LayoutNav></LayoutNav>
<LayoutHeader></LayoutHeader>
<RouterView></RouterView>
<LayoutFooter></LayoutFooter>

</template>