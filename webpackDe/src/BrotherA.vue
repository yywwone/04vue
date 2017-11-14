<template>
    <div>
        <button @click="sendToB">toB</button>
    </div>
</template>

<script>
import Bus from './bus'
export default {
    methods:{
        sendToB: function () {
            Bus.$emit('toBFlag','111111')
        }
    }

}
</script>

<style>

</style>
