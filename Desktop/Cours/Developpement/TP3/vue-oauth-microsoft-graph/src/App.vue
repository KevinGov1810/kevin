<template>
  <baseheader/>
  <HomePage/>
  <basefooter/>
</template>

<script>
import  HomePage  from './components/HomePage.vue'
import baseheader from './components/base-header.vue'
import basefooter from './components/base-footer.vue'

export default{
  name : 'App',
  components:{
    HomePage,
    baseheader,
    basefooter,
  }
}
</script>


