<template>
<div>
    <h1>Component 2</h1>
    <b-container fluid class="bv-example-row">
        <b-row>
            <b-col sm="6" md="6">sm="5" md="6"</b-col>
            <b-col sm="6" offset-sm="2" md="6" offset-md="0">sm="5" offset-sm="2" md="6" offset-md="0"</b-col>
        </b-row>

        <b-row>
            <b-col sm="6" md="6" lg="6">sm="6" md="5" lg="6"</b-col>
            <b-col sm="6" md="6" offset-md="2" lg="6" offset-lg="0">sm="6" md="5" offset-md="2" col-lg="6" offset-lg="0"</b-col>
        </b-row>
    </b-container>

</div>
</template>

<script>
export default {
    name: "Component2",
}
</script>
