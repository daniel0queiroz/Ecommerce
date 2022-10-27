<template>
    <div>
        <div class="py-4 bg-warning">
            <div class="container text-center">
                <h3>Nossos Produtos</h3>
            </div>
        </div>
        <OurProducts />
    </div>

</template>
  
<script>
import OurProducts from '/components/OurProducts.vue';

export default {
    name: 'products',
    components: { OurProducts },
    head() {
        return {
            title: 'Nossos Produtos',
            meta: [
                {
                    hid: 'description',
                    name: 'description',
                    content: 'NUXT JS Website designing from Scratch - Products'
                },
                {
                    hid: 'keywords',
                    name: 'keywords',
                    content: 'Vue, nuxt, javascript - Products'
                }
            ]
        }
    }
}
</script>
  
<style>

</style>