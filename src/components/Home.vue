<template>
  <div>
    <h1>Trade or view your portfolio</h1>
    <h6>You may save your data</h6>
    <h6>Click on 'End Day' to begin a new day</h6>
    <hr>
    <p>Your funds: {{funds | currency}}</p>
  </div>
</template>
<script>
import {mapGetters} from 'vuex';
export default {
  computed: {
    ...mapGetters([
      'funds'
    ])
  }
}
</script>

