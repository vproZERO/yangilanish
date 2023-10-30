<template>
  <div class="">
      <Header/>
      <About/>
      <Books/>
      <Text/>
      <Accordion/>
      <Footer/>
  </div>
</template>
<script>
import Header from './components/header.vue'
import About from './components/about.vue'
import Books from './components/books.vue'
import Text from './components/text.vue'
import Accordion from './components/accordion.vue'
import Footer from './components/footer.vue'
export default {
  components: {
    Header,
    About,
    Books,
    Text,
    Accordion,
    Footer,
  }
}
</script>
<style >
  
</style>