<template>
  <div>
    <appbar/>
    <Hero/>
    <explore-component/>
  </div>
</template>

<script>
// @ is an alias to /src
import Appbar from '@/components/Appbar'
import Hero from '@/components/HeroComponent'
import ExploreComponent from '../components/ExploreComponent.vue'

export default {
  name: 'Home',
  components: {
    Appbar,
    Hero,
    ExploreComponent
  }
}
</script>
