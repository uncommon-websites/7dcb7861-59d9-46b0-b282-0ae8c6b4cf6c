<script lang="ts">
  let selectedType = 'studio';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Two layouts. <span class="text-gray-400">Furnished or unfurnished.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Studio Apartment</h3>
      <p class="text-gray-500 text-sm">Perfect for individuals seeking modern, efficient living.</p>
    </div>

    <!-- Apartment Image -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4 z-10">
        <button class="w-10 h-10 rounded-full bg-white/90 flex items-center justify-center hover:bg-white shadow-lg">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-white/90 flex items-center justify-center hover:bg-white shadow-lg">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-stylish-studio-apartment-interior-with-m-1766289828458-1.webp" class="w-full h-full object-cover" alt="Studio Apartment" />
    </div>

    <!-- Type Toggle -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="px-6 py-2 rounded-full bg-gray-900 text-white text-sm font-medium">Studio</button>
      <button class="px-6 py-2 rounded-full bg-gray-200 text-gray-700 text-sm font-medium hover:bg-gray-300">One Bedroom</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>Studio</span>
      <span>1 bath</span>
      <span>Furnished option</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      <span class="font-bold text-gray-900">All utilities included</span> • High-speed Wi-Fi • Smart-home features<br>
      Flexible month-to-month options available
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Want to learn more?</span>
        <span class="text-primary-600">View floor plans</span>
      </button>
      <a href="#apply" class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" x2="8" y1="13" y2="13"/><line x1="16" x2="8" y1="17" y2="17"/><polyline points="10 9 9 9 8 9"/></svg>
        Apply now ->
      </a>
    </div>
  </div>
</section>
