<template>
  <div><nav-component></nav-component></div>

<HelloWorld></HelloWorld>
<footer-component></footer-component>
</template>

<script>
import NavComponent from '@/components/NavComponent.vue'

import HelloWorld from '../components/HelloWorld.vue'
import FooterComponent from '@/components/FooterComponent.vue'

export default {
  name: 'HomeView',
  components: {
    NavComponent,
    HelloWorld,
    FooterComponent
  }
}
</script>
