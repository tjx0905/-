<template>
  <div class="home">
    <navbar/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import navbar from '@/components/navbar.vue'

export default {
  name: 'home',
  components: {
    navbar
  }
}
</script>
