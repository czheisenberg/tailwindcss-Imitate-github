<template>
  <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> | 
    <router-link to="/header">header</router-link>
  <router-view/> -->
  <div class="flex flex-col min-h-screen">
    <Header></Header>

    <Footer></Footer>
  </div>
</template>

<script>
import { defineComponent } from 'vue';
import Header from './views/HeaderView.vue'; // @ is an alias to /src
import Footer from './views/FooterView.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    Header,
    Footer
  },
});

</script>
