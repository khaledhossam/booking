<template>
  <div>
    <nav-bar ></nav-bar>
    <b-img src="@/assets/img1.jpg" fluid alt="Fluid image"></b-img>
    <cards> </cards>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'
import Cards from "@/components/Cards"

export default {
  name: 'Home',
  components: {
    "nav-bar":NavBar,
    "cards" :Cards,
  }
}
</script>
