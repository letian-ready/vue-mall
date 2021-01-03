<template>
  <div id="app">
    <div id="app">
    <router-view></router-view>
  </div>
    <router-view/>
  </div>
</template>

<script>

// import jsonp from 'jsonp'
import storage from '../src/storage'
export default {
  name: 'app',
  components: {
    
  },
  data(){
    return {
      
    }
  },
  mounted(){
    // storage.setItem('a', 1);
    // storage.setItem('user', {a:1});
    // storage.setItem('abc', {a:1}, 'user');
    // storage.clear('a');
    storage.clear('a', 'user');
  },
  methods:{
    
  }
}
</script>

<style lang="scss">

</style>
