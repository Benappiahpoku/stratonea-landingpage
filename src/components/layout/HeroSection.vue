<!--
  HeroSection.vue
  Stratonea landing page hero section.
  - Mobile-first: image on top, text below.
  - Desktop: text left, image right.
  - Buttons are always below the text.
  - Image has margin/padding and rounded corners.
  - Caption always below buttons.
  - All styling via Tailwind utility classes.
-->

<template>
  <!-- ===== Hero Section ===== -->
  <section class="bg-gradient-to-b from-gray-50 to-white py-12 lg:py-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <!--
        Mobile: 1 column (image on top, text below)
        Desktop: 2 columns (text left, image right)
      -->
      <div class="flex flex-col-reverse lg:flex-row items-center gap-8 lg:gap-16">
        <!-- ===== [New Feature] START ===== -->
        <!-- Left: Text Content (always below image on mobile, left on desktop) -->
        <div class="w-full lg:w-1/2 text-center lg:text-left space-y-8">
          <!-- Main Headline -->
          <h1 class="text-3xl sm:text-4xl lg:text-5xl font-bold text-gray-900 leading-tight">
            Smart, Free Tools for
            <span class="text-primary-600">African Businesses</span>
          </h1>
          <!-- Subheading -->
          <p class="text-lg sm:text-xl text-gray-600 max-w-2xl mx-auto lg:mx-0">
            Run your business better — create invoices, issue receipts, and track sales in seconds.
          </p>
          <!-- Action Buttons -->
          <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">
            <a href="https://invoice.stratonea.com" target="_blank" rel="noopener noreferrer"
              class="inline-flex items-center justify-center px-6 py-4 bg-primary-600 hover:bg-primary-700 text-white font-semibold rounded-lg transition-colors duration-200 min-h-[3rem] shadow-md">
              Create an Invoice
            </a>
            <a href="https://receipt.stratonea.com" target="_blank" rel="noopener noreferrer"
              class="inline-flex items-center justify-center px-6 py-4 bg-secondary-600 hover:bg-secondary-700 text-white font-semibold rounded-lg transition-colors duration-200 min-h-[3rem] shadow-md">
              Issue a Receipt
            </a>
            <a href="https://sales.stratonea.com" target="_blank" rel="noopener noreferrer"
              class="inline-flex items-center justify-center px-6 py-4 bg-green-600 hover:bg-green-700 text-white font-semibold rounded-lg transition-colors duration-200 min-h-[3rem] shadow-md">
              Track Sales
            </a>
          </div>
          <!-- Caption Text -->
          <p class="text-sm text-gray-500 text-center lg:text-left">
            Used by small shops, freelancers, and service providers across Africa.
          </p>
        </div>
        <!-- ===== [New Feature] END ===== -->

        <!-- ===== [New Feature] START ===== -->
        <!-- Right: Hero Image (on top for mobile, right for desktop) -->
        <div class="w-full lg:w-1/2 flex justify-center items-center mb-8 lg:mb-0">
          <!--
            - Mobile: margin-bottom for spacing
            - Desktop: no margin-bottom, image right
            - Image: rounded corners, a little padding/margin, responsive
          -->
          <img src="/stratoneaheropic.webp" alt="African entrepreneurs using mobile tools"
            class="w-full max-w-xs sm:max-w-sm md:max-w-md lg:max-w-lg rounded-3xl shadow-lg object-cover bg-white p-2"
            loading="lazy" />
        </div>
        <!-- ===== [New Feature] END ===== -->
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// No logic needed for static hero section
</script>