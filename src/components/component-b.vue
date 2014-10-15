<style lang="scss">
    #b {
        h2 {
            font-family: Georgia;
        }
    }
</style>

<script>
    module.exports = {
        data: function () {
            return {
                msg: 'I am component B!'
            }
        }
    };
</script>

<template>
    <div id="b">
        <h2>{{msg}}</h2>
    </div>
</template>