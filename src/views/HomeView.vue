<script setup lang="ts">
import Card from "@/components/Card.vue";
import Description from "@/components/Description.vue";
import NavbarVue from "@/components/Navbar.vue";
</script>

<template>
  <main>
    <div class="flex flex-col">
      <NavbarVue />
      <img src="@/assets/images/gambar.png" alt="image" class="w-full h-200px"/>
      <Description />
      <Card />
    </div>
  </main>
</template>
