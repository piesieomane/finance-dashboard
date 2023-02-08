<script setup>
import Navbar from "./Navbar.vue";
import Sidebar from "./Sidebar.vue";
</script>

<template>
  <div>
    <Navbar />
    <div>
      <div class="w-1/5">
        <Sidebar />
      </div>
      <div class="w-4/5">
        <router-view />
      </div>
    </div>
  </div>
</template>
