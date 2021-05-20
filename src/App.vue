<template>
  <div class="h-screen bg-green-500">
    <Navbar />

    <div class="h-full bg-red-400 flex justify-center items-center">
      <div class="bg-blue-50 rounded p-3 m-3 shadow hover:shadow-lg">
        <router-view />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Navbar from './components/Navbar.vue';

export default defineComponent({
  name: 'App',
  components: {
    Navbar
  }
});
</script>