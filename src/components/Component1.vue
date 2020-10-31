<template>
<div>
    <hr>
    <h1>This is component 1</h1>
    <p>{{text}}</p>
    <hr>
    <Component2></Component2>
</div>
</template>

<script>
import Component2 from './Component2.vue'
export default {
    name: "Component1",
    components: {
        Component2
    },
    data() {
        return {
            text: "this is some text"
        }
    },
}
</script>
