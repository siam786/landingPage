<template>
  <header id="header_wrapper">
    <!--begin header -->
    <div id="header" class="clearfix" :class="{ small_device_active: isSmallScreen }">
      <!--begin row -->
      <div class="row">
        <!--begin logo -->
        <a href="/" id="logo">Simpl<span class="blue">é</span></a>
        
        <!--end logo -->

        <!--begin nav -->
        <nav id="navigation" role="navigation">
          <ul id="nav">
            <li v-for="item in navItems" :key="item.id">
              <a :href="item.href">{{ item.label }}</a>
            </li>
          </ul>
          <a href="#" id="responsive_nav_open" class="" @click.prevent="toggleMobileMenu">
            <Icon icon="bi:menu" width="20" />
          </a>
          <a href="#" id="responsive_nav_hide" class="" @click.prevent="toggleMobileMenu">
             <Icon icon="bi:menu" width="20" />
          </a>
        </nav>
        <!--end nav -->
      </div>
      <!--end row -->
    </div>
    <!--end header -->
  </header>
</template>

<script setup>
import { Icon } from "@iconify/vue";
import { ref } from 'vue';

const isSmallScreen = ref(false);
const navItems = [
  { id: 1, label: 'Home', href: '#home_wrapper' },
  { id: 2, label: 'Services', href: '#services' },
  { id: 3, label: 'Features', href: '#features' },
  { id: 4, label: 'About Us', href: '#about' },
  { id: 5, label: 'Blog', href: '#blog' },
  { id: 6, label: 'Pricing', href: '#pricing' },
  { id: 7, label: 'Contact', href: '#contact' },
];

const toggleMobileMenu = () => {
  isSmallScreen.value = !isSmallScreen.value;
};
</script>

<style scoped>
/* CSS for showing and hiding the mobile menu */
#responsive_nav_open {
  display: none;
}

#responsive_nav_hide {
  display: none;
}

.show_responsive_nav #responsive_nav_open {
  display: none;
}

.show_responsive_nav #responsive_nav_hide {
  display: block;
}

.small_device_active #responsive_nav_open {
  display: block;
}

/* Rest of your styles */

</style>
