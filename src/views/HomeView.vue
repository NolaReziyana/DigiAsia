<script setup lang="ts">
import CardBuild from "@/components/CardBuild.vue";
import CardList from "@/components/CardList.vue";
import DescriptionSection from "@/components/DescriptionSection.vue";
import LicensesSection from "@/components/LicensesSection.vue";
import NavbarSection from "@/components/NavbarSection.vue";
</script>

<template>
  <main>
    <div class="flex flex-col">
      <NavbarSection />
      <DescriptionSection />
      <CardBuild />
      <CardList />
      <LicensesSection />
    </div>
  </main>
</template>
