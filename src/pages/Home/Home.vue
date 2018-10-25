<template>
  <div class="hello">
{{msg}}
  </div>
</template>

<script>
import HomeHeader from './components/Header'
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    'header':HomeHeader
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
