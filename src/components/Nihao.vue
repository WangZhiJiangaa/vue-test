<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>weegwfv</h2>
    <router-view></router-view>
    
  </div>
</template>

<script>
import {Toast, Indicator } from 'mint-ui'
export default {
  name: 'Nihao',
  data () {
    return {
      msg: 'nihao欢迎来到传智播客'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
