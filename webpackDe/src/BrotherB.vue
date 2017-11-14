<template>
  
</template>

<script>
import Bus from './bus'
export default {
  created: function () {
      Bus.$on('toBFlag',function (data) {
          console.log(data)
      })
  }
}
</script>

<style>

</style>
