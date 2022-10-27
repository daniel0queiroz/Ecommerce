<template>
  <div>

    <div class="py-4 bg-warning">
      <div class="container text-center">
        <h3>Sobre Nós</h3>
      </div>
    </div>
    
    <Aboutus />

  </div>
</template>

<script>
import AboutUs from '/components/Aboutus.vue';

export default {
  name: 'about',
  components: { AboutUs },
  head() {
    return {
      title: 'Sobre Nós',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'NUXT JS Website designing from Scratch - About Us'
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Vue, nuxt, javascript - About Us'
        }
      ]
    }
  }
}
</script>

<style>

</style>