<template>
  <div class="bg-gray-100 overflow-auto h-screen flex flex-col justify-between">
    <navbar />
    <main-container />
    <app-footer class="align-end" />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import AppFooter from './components/AppFooter.vue';
import MainContainer from './components/MainContainer.vue';

export default {
  name: 'HomeLayout',
  components: {
    Navbar,
    MainContainer,
    AppFooter,
  },
  data() {
    return {
      items: [],
    }
  },
}
</script>
