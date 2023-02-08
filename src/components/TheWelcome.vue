<script setup>
import Navbar from "./Navbar.vue";
import Sidebar from "./Sidebar.vue";
import { RouterView } from "vue-router";
</script>

<template>
  <div>
    <Navbar />
    <div class="flex flex-row">
      <div class="w-1/5">
        <Sidebar />
      </div>
      <div class="w-4/5">
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>
