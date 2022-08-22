<template>
  <v-app>
    <NavbarVue class="index" />
    <DashboardVue />
    <FooterVue />
  </v-app>
</template>

<script>
import NavbarVue from '../components/NavbarVue.vue'
import DashboardVue from '../components/DashboardVue.vue'
import FooterVue from '../components/FooterVue.vue'

  export default {
    name: 'HomeView',

    components: {
    NavbarVue,
    DashboardVue,
    FooterVue
},
  }
</script>

<style scoped>
.index {
  z-index: 9999;
}
</style>