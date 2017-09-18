<template src="@/app.html"></template>

<script>
import Navbar from '@/modules/Navbar'
import Footer from '@/modules/Footer'
import Loading from '@/modules/Loading'
export default {
  name: 'app',
  data() {
    return {
      
    }
  },
  components: {
    "c-navbar": Navbar,
    "c-footer": Footer,
    "c-loading": Loading
  }
}
</script>

<style src="@/app.css" lang="css"></style>