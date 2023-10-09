<script>
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
export default {
name: "app",
components: {
Header,
Footer,

},

data() {
return {
titolo: "Ciao vue"
}

}

}
</script>


<template>
  <Header />
  <h1>{{ titolo }}</h1>

<Footer />

</template>


<style>

</style>