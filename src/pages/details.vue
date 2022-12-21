<script setup lang="ts">
import NavigationBar from "@/components/NavigationBar.vue";
import SimiliarItem from "@/components/SimiliarItem.vue";
import ProductGallery from "@/components/ProductGallery.vue";
import ProductDescription from "@/components/ProductDescription.vue";
import ProductTitle from "@/components/ProductTitle.vue";
</script>

<template>
  <main>
    <NavigationBar />
    <div class="container mx-auto mb-10">
      <ProductTitle />
      <ProductGallery />
      <ProductDescription />
    </div>
    <SimiliarItem />
  </main>
</template>
