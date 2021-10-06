<template>
    <div class="container">
        <header>
            <baseheader/>
        </header>
        <main>
            <slot></slot>
        </main>
        <footer>
            <basefooter/>
        </footer>
    </div>
</template>

<script>
import baseheader from './base-header.vue'
import basefooter from './base-footer.vue'

export default{
  name : 'BaseLayout',
  components:{
    baseheader,
    basefooter
  }
}
</script>
