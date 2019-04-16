<template>
  <div id='app'>
    <div id='nav'>
      <router-link to='/'></router-link>
      <router-link to='/'></router-link>
    </div>
    <router-view></router-view>
  </div>
</template>


<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
