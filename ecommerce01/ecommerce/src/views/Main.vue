<template lang="">
 <div>
  <Header />
  
  <Footer />
 </div>
</template>
<script>
import Header from "../components/includes/Header.vue"
import Footer from "../components/includes/Footer.vue"
export default {
 name:'main',
 components: {
  Header, 
  Footer
 }
}
</script>
