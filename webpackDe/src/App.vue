<template>
    <div>
        <!-- <Son yy="hello"></Son>


        <Son @flag="receiveSonData"></Son> -->

        <brother-a></brother-a>
        <brother-b></brother-b>
    </div>
</template>

<script>
import Son from './Son.vue'

import BrotherA from './BrotherA.vue'
import BrotherB from './BrotherB.vue'

export default {
  components: {
      Son,
      BrotherA,
      BrotherB
  },
  methods:{
      receiveSonData: function (data) {
          console.log(data)
      }
  }
}
</script>

<style>

</style>
