<template>
<div>
    <hr>
    <h1>This is component 1</h1>
    <p>{{text}}</p>
    <hr>
</div>
</template>

<script>
export default {
    name: "Component1",
    data() {
        return {
            text: "this is some text"
        }
    },
}
</script>
