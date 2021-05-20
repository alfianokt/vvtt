<template>
  <div class="flex justify-center bg-blue-50">
    <ul class="inline-flex py-3 font-bold text-gray-600">
      <li class="mr-3">
        <router-link to="/">Home</router-link>
      </li>
      <li>
        <router-link to="/about">About</router-link>
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: 'Navbar'
});
</script>
