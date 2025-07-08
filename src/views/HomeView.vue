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

    <!-- ===== Tools Section ===== -->
    <section class="py-16 bg-gray-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <!-- Section Title -->
        <div class="text-center mb-12">
          <h2 class="text-2xl sm:text-3xl font-bold text-gray-900 mb-4">
            Explore Our Free Tools
          </h2>
        </div>
        
        <!-- Tools Grid - Mobile-first responsive -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          
          <!-- Invoice Maker Tool Card -->
          <div class="bg-white rounded-xl shadow-md hover:shadow-lg transition-shadow duration-200 p-6 text-center">
            <!-- Icon -->
            <div class="w-16 h-16 bg-primary-100 rounded-xl flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
              </svg>
            </div>
            
            <!-- Content -->
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Invoice Maker</h3>
            <p class="text-gray-600 mb-6">Create clean invoices in seconds</p>
            
            <!-- Button -->
            <a 
              href="https://invoice.stratonea.com" 
              target="_blank" 
              rel="noopener noreferrer"
              class="inline-flex items-center justify-center w-full px-4 py-3 bg-primary-600 hover:bg-primary-700 text-white font-medium rounded-lg transition-colors duration-200 min-h-[3rem]"
            >
              Open Invoice Tool
            </a>
          </div>

          <!-- Receipt Maker Tool Card -->
          <div class="bg-white rounded-xl shadow-md hover:shadow-lg transition-shadow duration-200 p-6 text-center">
            <!-- Icon -->
            <div class="w-16 h-16 bg-secondary-100 rounded-xl flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-secondary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v10a2 2 0 002 2h8a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path>
              </svg>
            </div>
            
            <!-- Content -->
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Receipt Maker</h3>
            <p class="text-gray-600 mb-6">Print or share professional receipts</p>
            
            <!-- Button -->
            <a 
              href="https://receipt.stratonea.com" 
              target="_blank" 
              rel="noopener noreferrer"
              class="inline-flex items-center justify-center w-full px-4 py-3 bg-secondary-600 hover:bg-secondary-700 text-white font-medium rounded-lg transition-colors duration-200 min-h-[3rem]"
            >
              Open Receipt Tool
            </a>
          </div>

          <!-- Sales Tracker Tool Card -->
          <div class="bg-white rounded-xl shadow-md hover:shadow-lg transition-shadow duration-200 p-6 text-center md:col-span-2 lg:col-span-1">
            <!-- Icon -->
            <div class="w-16 h-16 bg-green-100 rounded-xl flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
              </svg>
            </div>
            
            <!-- Content -->
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Sales Tracker</h3>
            <p class="text-gray-600 mb-6">Record and analyze your daily sales</p>
            
            <!-- Button -->
            <a 
              href="https://sales.stratonea.com" 
              target="_blank" 
              rel="noopener noreferrer"
              class="inline-flex items-center justify-center w-full px-4 py-3 bg-green-600 hover:bg-green-700 text-white font-medium rounded-lg transition-colors duration-200 min-h-[3rem]"
            >
              Open Sales Tracker
            </a>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script setup lang="ts">
import HeroSection from '@/components/layout/HeroSection.vue';

// ===== Landing Page Logic =====
// This is a static landing page with external links to tools
// No complex state management needed for this page
</script>