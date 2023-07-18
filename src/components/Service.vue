<template>
  <section id="services">
    <div v-for="service in services" :key="service.id" class="services_item">
      <div class="services_box">
        <div class="icon_wrapper">
          <Icon class="icon" :icon="service.icon" width="50" />
        </div>
        <h2>{{ service.title }}</h2>
        <p>{{ service.description }}</p>
        <a href="" class="services_button">Read More</a>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue';
import { Icon } from '@iconify/vue'; // Import your custom Icon component
const services = ref([
      {
        id: 1,
        icon: "ri:computer-line",
        title: "Super Design Layout",
        description: "Parumitsum clarits, it ets solemne fiant futurum magna et netsum adipisci elit, hendris itsum mis salit ets lorem ipsum sed interdut wisi net quis."
      },
      {
        id: 2,
        icon: "ph:pen-thin",
        title: "Responsive & Mobile Ready",
        description: "Parumitsum clarits, it ets solemne fiant futurum magna et netsum adipisci elit, hendris itsum mis salit ets lorem ipsum sed interdut wisi net quis."
      },
      {
        id: 3,
        icon: "clarity:picture-line",
        title: "Clean & Commented Code",
        description: "Parumitsum clarits, it ets solemne fiant futurum magna et netsum adipisci elit, hendris itsum mis salit ets lorem ipsum sed interdut wisi net quis."

      }]);


</script>

<style scoped>


.services_item:hover .icon {
    color: #fff !important;
}
</style>