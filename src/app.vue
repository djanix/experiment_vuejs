<style lang="scss">
    #app {
        font-family: 'Helvetica Neue', Arial, sans-serif;
    }
</style>

<script>
    module.exports = {
        components: {
            a: require('./components/component-a.vue'),
            b: require('./components/component-b.vue')
        },
        data: {
            title: 'Hello Browserify & Vue.js!'
        }
    };
</script>

<template>
    <h1>{{title}}</h1>
    <div v-component="a"></div>
    <div v-component="b"></div>
</template>