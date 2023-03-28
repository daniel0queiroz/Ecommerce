<template>
    <div>
        <div class="py-4 bg-warning">
            <div class="container text-center">
                <h3>Contato</h3>
            </div>
        </div>

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
  export default {
      name: 'contact',
      head() {
    return {
      title: 'Fale Conosco',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'NUXT JS Website designing from Scratch - Contact Us'
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Vue, nuxt, javascript - Contact Us'
        }
      ]
    }
  }
  }
  </script>
  
  <style>
  
  </style>