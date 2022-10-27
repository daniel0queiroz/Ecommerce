<template>

  <div>
    <Slider />
    <AboutUs />
    
    <OurProducts />

    <div class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-8">
            <h1 class="main-heading">If you fave any queries ?</h1>
            <h4>Please reach out us at contact@example.com</h4>
          </div>
          <div class="col-md-4 text-center my-auto">
            <NuxtLink to="/contact" class="px-5 py-2 btn btn-primary">Contact Us</NuxtLink>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Slider from '/components/Slider.vue';
import AboutUs from '/components/Aboutus.vue';
import OurProducts from '/components/OurProducts.vue';

export default {
  name: 'IndexPage',
  components: { Slider, AboutUs, OurProducts },
  head() {
    return {
      title: 'Página Inicial',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'NUXT JS Website designing from Scratch - HomePage'
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Vue, nuxt, javascript - HomePage'
        }
      ]
    }
  }
}
</script>
