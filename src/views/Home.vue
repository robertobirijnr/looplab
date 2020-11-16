<template>
  <div>
    <appbar/>
    <Hero/>
  </div>
</template>

<script>
// @ is an alias to /src
import Appbar from '@/components/Appbar'
import Hero from '@/components/HeroComponent'

export default {
  name: 'Home',
  components: {
    Appbar,
    Hero
  }
}
</script>
