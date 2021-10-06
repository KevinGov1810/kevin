<template>
  <baselayout>
    <HomePage/>
  </baselayout>
</template>

<script>
import  HomePage  from './components/HomePage.vue'
import baselayout from './components/BaseLayout.vue'

export default{
  name : 'App',
  components:{
    HomePage,
    baselayout,
  }
}
</script>


