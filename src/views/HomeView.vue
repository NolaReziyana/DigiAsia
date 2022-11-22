<script setup lang="ts">
import CardBuild from "@/components/CardBuild.vue";
import CardList from "@/components/CardList.vue";
import DescriptionSection from "@/components/DescriptionSection.vue";
import NavbarSection from "@/components/NavbarSection.vue";
</script>

<template>
  <main>
    <div class="flex flex-col">
      <NavbarSection />
      <img
        src="@/assets/images/gambar.png"
        alt="image"
        class="w-full h-200px"
      />
      <DescriptionSection />
      <CardBuild />
      <CardList />
    </div>
  </main>
</template>
