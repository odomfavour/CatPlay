<template>
  <div>
     <NavBar/> 
     <Jumbotron/>
    <nuxt/>
    <Footer/>
  </div>
</template>


<script>
    import NavBar from '~/components/Home/NavBar'
    import Jumbotron from '~/components/Home/Jumbotron'
    import Footer from '~/components/Home/Footer'
    export default {
        components: {
            NavBar,
            Jumbotron,
            Footer
        }
    }
</script>