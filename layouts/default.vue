<template>
  <div>
    <default-header />
    <nuxt />
    <default-footer />
  </div>
</template>

<script>
import DefaultHeader from '@/components/Header/DefaultHeader.vue'
import DefaultFooter from '~/components/Footer/DefaultFooter.vue'
export default {
  components: { DefaultHeader, DefaultFooter },
  
}
</script>

<style scoped>
html, body{
  font-family: 'Times New Roman', Times, serif;
  background-color: black;
}
</style>
