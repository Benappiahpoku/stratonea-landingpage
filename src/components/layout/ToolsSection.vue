<!--
  ToolsSection.vue
  Modern tools showcase section for Stratonea landing page.
  - Each card displays the full image (no cropping), centered, with rounded corners.
  - Image blends into the card's white background (no colored backgrounds).
  - Mobile-first responsive layout, optimized for Ghanaian users.
  - Clear comments for learning and maintainability.
-->

<template>
  <!-- ===== Tools Section ===== -->
  <section class="py-20 bg-gradient-to-b from-gray-50 to-white">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <!-- ===== Section Header ===== -->
      <div class="text-center mb-16">
        <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 mb-4">
          Our Free Business Tools
        </h2>
        <p class="text-lg text-gray-600 max-w-2xl mx-auto">
          Professional tools designed for Ghanaian entrepreneurs. No sign-up required.
        </p>
      </div>

      <!-- ===== Tools Grid ===== -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-8">
        <!-- ===== Invoice Maker Card ===== -->
        <div class="group bg-white rounded-2xl shadow-sm hover:shadow-xl transition-all duration-300 overflow-hidden border border-gray-100 flex flex-col">
          <!-- ===== [New Feature] START ===== -->
          <!-- Image: Full width, maintains aspect ratio, blends into white, rounded top corners -->
          <div class="w-full flex justify-center items-center bg-white pt-6">
            <img
              src="/invoiceteklumin.png"
              alt="Invoice Maker Tool Preview"
              class="w-auto h-56 max-h-60 object-contain rounded-t-2xl transition-transform duration-300 group-hover:scale-105"
              loading="lazy"
            />
          </div>
          <!-- ===== [New Feature] END ===== -->
          <!-- Card Content -->
          <div class="flex-1 flex flex-col justify-between p-6">
            <div>
              <h3 class="text-xl font-semibold text-gray-900 mb-2 text-center">Invoice Maker</h3>
              <p class="text-gray-600 mb-6 text-center">
                Create clean invoices in seconds.
              </p>
            </div>
            <a
              href="https://invoice.stratonea.com"
              target="_blank"
              rel="noopener noreferrer"
              class="inline-flex items-center justify-center w-full px-6 py-3 bg-blue-600 hover:bg-blue-700 text-white font-medium rounded-xl transition-all duration-200 min-h-[3rem] mt-auto"
            >
              Open Invoice Tool
            </a>
          </div>
        </div>

        <!-- ===== Receipt Maker Card ===== -->
        <div class="group bg-white rounded-2xl shadow-sm hover:shadow-xl transition-all duration-300 overflow-hidden border border-gray-100 flex flex-col">
          <!-- ===== [New Feature] START ===== -->
          <div class="w-full flex justify-center items-center bg-white pt-6">
            <img
              src="/receiptteklumin.png"
              alt="Receipt Maker Tool Preview"
              class="w-auto h-56 max-h-60 object-contain rounded-t-2xl transition-transform duration-300 group-hover:scale-105"
              loading="lazy"
            />
          </div>
          <!-- ===== [New Feature] END ===== -->
          <div class="flex-1 flex flex-col justify-between p-6">
            <div>
              <h3 class="text-xl font-semibold text-gray-900 mb-2 text-center">Receipt Maker</h3>
              <p class="text-gray-600 mb-6 text-center">
                Print or share professional receipts.
              </p>
            </div>
            <a
              href="https://receipt.stratonea.com"
              target="_blank"
              rel="noopener noreferrer"
              class="inline-flex items-center justify-center w-full px-6 py-3 bg-blue-500 hover:bg-blue-600 text-white font-medium rounded-xl transition-all duration-200 min-h-[3rem] mt-auto"
            >
              Open Receipt Tool
            </a>
          </div>
        </div>

        <!-- ===== Sales Tracker Card ===== -->
        <div class="group bg-white rounded-2xl shadow-sm hover:shadow-xl transition-all duration-300 overflow-hidden border border-gray-100 flex flex-col md:col-span-2 lg:col-span-1">
          <!-- ===== [New Feature] START ===== -->
          <div class="w-full flex justify-center items-center bg-white pt-6">
            <img
              src="/salestrackerteklumin.png"
              alt="Sales Tracker Tool Preview"
              class="w-auto h-56 max-h-60 object-contain rounded-t-2xl transition-transform duration-300 group-hover:scale-105"
              loading="lazy"
            />
          </div>
          <!-- ===== [New Feature] END ===== -->
          <div class="flex-1 flex flex-col justify-between p-6">
            <div>
              <h3 class="text-xl font-semibold text-gray-900 mb-2 text-center">Sales Tracker</h3>
              <p class="text-gray-600 mb-6 text-center">
                Record and analyze your daily sales.
              </p>
            </div>
            <a
              href="https://sales.stratonea.com"
              target="_blank"
              rel="noopener noreferrer"
              class="inline-flex items-center justify-center w-full px-6 py-3 bg-green-600 hover:bg-green-700 text-white font-medium rounded-xl transition-all duration-200 min-h-[3rem] mt-auto"
            >
              Open Sales Tracker
            </a>
          </div>
        </div>
      </div>

      <!-- ===== Trust Indicators ===== -->
      <div class="mt-16 text-center">
        <p class="text-sm text-gray-500 mb-4">Trusted by businesses across Africa</p>
        <div class="flex items-center justify-center gap-8 text-xs text-gray-400">
          <span class="flex items-center gap-2">
            <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20">
              <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
            </svg>
            No Sign-up Required
          </span>
          <span class="flex items-center gap-2">
            <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20">
              <path d="M3 4a1 1 0 011-1h12a1 1 0 011 1v2a1 1 0 01-1 1H4a1 1 0 01-1-1V4zM3 10a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H4a1 1 0 01-1-1v-6zM14 9a1 1 0 00-1 1v6a1 1 0 001 1h2a1 1 0 001-1v-6a1 1 0 00-1-1h-2z"></path>
            </svg>
            Works Offline
          </span>
          <span class="flex items-center gap-2">
            <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20">
              <path d="M10 2L3 7v11a1 1 0 001 1h3v-8h6v8h3a1 1 0 001-1V7l-7-5z"></path>
            </svg>
            100% Free
          </span>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
// ===== Static Tools Section =====
// No reactive logic needed - this is a presentation component
// All links open external tools in new tabs for better UX
</script>