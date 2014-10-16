<style lang="scss">
    #a {
        h2 {
            color: red;
            font-style: italic;
        }
    }
</style>

<script>
    module.exports = {
        data: function () {
            return {
                msg: 'I am component A!',
                incrementNumber: 0
            }
        },
        methods: {
            increment: function () {
                this.$data.incrementNumber++;
            }
        }
    };
</script>

<template>
    <div id="a">
        <h2>{{msg}}</h2>
        <button v-on="click:increment()">click me</button>&nbsp;
        <span>{{incrementNumber}}</span>
    </div>
</template>