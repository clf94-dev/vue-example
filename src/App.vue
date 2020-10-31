<template>
<div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Component1 />
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Component1 from './components/Component1.vue'

export default {
    name: 'App',
    components: {
        HelloWorld,
        Component1
    }
}
</script>

<style>
@import './assets/styles/styles.css';
</style>
