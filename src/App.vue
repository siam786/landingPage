<script setup>
//load component
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import Service from './components/Service.vue'
import Features from './components/Features.vue'
import Testimonials from './components/Testimonials.vue'
import About from './components/About.vue'
import Blog from './components/Blog.vue'
import Info from './components/Info.vue'
import Pricing from './components/Pricing.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'


</script>

<template>
  <!--begin container -->
  <div id="container">
    <!--begin header_wrapper -->
    <Header/>
    <!--end header_wrapper -->

    <!--begin home_wrapper -->
    <Home/>
    <!--end home_wrapper -->
    <!--begin services -->
    <Service/>
    <!-- end section_wrapper -->

    <!--begin features -->
    <Features/>
    <!--end features -->

    <!--begin testimonials_wrapper -->
    <Testimonials/>
    <!--end testimonials_wrapper -->

    <!--begin about -->
   <About/>
    <!--end about -->

    <!--begin blog -->
    <Blog/>
    <!--end blog -->

    <!--begin info_wrapper -->
    <Info/>
    <!--end info_wrapper -->

    <!--begin pricing -->
    <Pricing/>
    <!--end pricing -->

    <!--begin contact -->
    <Contact/>
    <!--end contact -->

    <!--begin footer -->
    <Footer/>
    <!--end footer -->
  </div>
</template>

<style scoped></style>
