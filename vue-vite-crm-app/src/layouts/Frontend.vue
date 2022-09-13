<template>
  <div>
    <Nav />
    <main>
      <router-view />
    </main>
    <Foot />
  </div>
</template>
<script>
import Nav from '@/components/fronted/Nav.vue'
import Foot from '@/components/fronted/Foot.vue'
export default {
  name: 'FrontendLayout',
  components: {
    Nav,
    Foot
  }
}
</script>
<style lang=""></style>
