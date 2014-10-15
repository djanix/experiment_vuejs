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
        replace: true,
        data: function () {
            return {
                msg: 'I am component A!'
            }
        }
    };
</script>

<template>
    <div id="a">
        <h2>{{msg}}</h2>
    </div>
</template>