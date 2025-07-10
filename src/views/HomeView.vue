<template>
  <!-- ===== Hero Section ===== -->
  <main class="min-h-screen bg-white">
    
    <HeroSection />

    <!-- ===== About Stratonea Section ===== -->
    <section class="py-16 bg-white">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <h2 class="text-2xl sm:text-3xl font-bold text-gray-900 mb-8">
          About Stratonea?
        </h2>
        <p class="text-lg text-gray-600 leading-relaxed max-w-3xl mx-auto">
          Stratonea is a business consultancy helping African entrepreneurs run more efficiently. 
          We offer free tools to help small businesses create invoices, track sales, and issue receipts — 
          all built to work offline and on mobile.
        </p>
      </div>
    </section>

    <ToolsSection />
  </main>
</template>

<script setup lang="ts">
import HeroSection from '@/components/layout/HeroSection.vue';
import ToolsSection from '@/components/layout/ToolsSection.vue';

// ===== Landing Page Logic =====
// This is a static landing page with external links to tools
// No complex state management needed for this page
</script>