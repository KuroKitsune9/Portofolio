<template>
  <div>
    <NavrbarComponent></NavrbarComponent>
    <HeaderComponent></HeaderComponent>
    <MainComponent></MainComponent>
    <ContactComponen></ContactComponen>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script setup>
  import 'flowbite/dist/flowbite.js'
  import NavrbarComponent from './components/NavbarComponent.vue'
  import HeaderComponent from './components/HeaderComponent.vue'
  import MainComponent from './components/MainComponent.vue'
  import FooterComponent from './components/FooterComponent.vue'
  import ContactComponen from './components/ContactComponen.vue'
</script>