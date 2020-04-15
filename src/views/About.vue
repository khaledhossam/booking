<template>
  <div> 
    <nav-bar ></nav-bar>
    <h1>This is an about page</h1>
  </div>
</template>


<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'Home',
  components: {
    "nav-bar":NavBar,
  }
}
</script>