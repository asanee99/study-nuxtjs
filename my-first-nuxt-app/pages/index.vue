<template>
  <section class="section">
    <div class="container">
      <h1>This is My First app with NUXT JS</h1>
      <nuxt-link class="button" to="/products">GO to Product Page</nuxt-link>
    </div>
  </section>
</template>

<script>
import BLogo from '@/components/Logo'

export default {
  name: 'HomePage',
  components: {BLogo},
  data() {
      return {
          features: [
              { icon: 'github-circle', title: 'Free', content: `<span>Open source on <a href="https://github.com/buefy/buefy"> GitHub</a></span>` },
              { icon: 'cellphone-link', title: 'Responsive', content: `<span><b class="has-text-grey">Every</b> component is responsive</span>` },
              { icon: 'alert-decagram', title: 'Modern', content: `<span>Built with <a href="https://vuejs.org/">Vue.js</a> and <a href="http://bulma.io/">Bulma</a></span>` },
              { icon: 'arrange-bring-to-front', title: 'Lightweight', content: `<span>No other internal dependency</span>` }
          ]
      }
  }
}
</script>
