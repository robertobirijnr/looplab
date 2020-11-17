<template>
  <div>
    <appbar/>
    <Hero/>
    <explore-component/>
    <create-component/>
    <share-component/>
    <footer-component/>
  </div>
</template>

<script>
// @ is an alias to /src
import Appbar from '@/components/Appbar'
import Hero from '@/components/HeroComponent'
import ExploreComponent from '../components/ExploreComponent.vue'
import CreateComponent from '../components/CreateComponent.vue'
import ShareComponent from '../components/ShareComponent.vue'
import FooterComponent from '../components/FooterComponent.vue'

export default {
  name: 'Home',
  components: {
    Appbar,
    Hero,
    ExploreComponent,
    CreateComponent,
    ShareComponent,
    FooterComponent
  }
}
</script>
