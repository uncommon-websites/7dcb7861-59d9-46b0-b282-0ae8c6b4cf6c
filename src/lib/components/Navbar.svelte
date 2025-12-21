<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="flex items-center gap-2">
      <div class="w-8 h-8 text-white">
        <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M20.5734 7.55963V11.331H15.9021V10.2568L20.5734 7.55963Z" fill="currentColor"/>
          <path opacity="0.9" fill-rule="evenodd" clip-rule="evenodd" d="M20.5724 7.55968L15.9011 10.2569L12.4567 8.26854V2.87418L20.5724 7.55968Z" fill="currentColor"/>
          <path opacity="0.8" fill-rule="evenodd" clip-rule="evenodd" d="M12.4578 2.87418V8.26854L9.01444 10.2569L4.34314 7.55968L12.4578 2.87418Z" fill="currentColor"/>
          <path opacity="0.7" fill-rule="evenodd" clip-rule="evenodd" d="M9.01353 10.2568V14.2333L4.34225 16.9302V7.55963L9.01353 10.2568Z" fill="currentColor"/>
          <path opacity="0.6" fill-rule="evenodd" clip-rule="evenodd" d="M12.4569 16.2217V21.616L4.34225 16.9303L9.01353 14.2333L12.4569 16.2217Z" fill="currentColor"/>
          <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M20.5724 16.9303L12.4567 21.616V16.2217L15.9011 14.2333L20.5724 16.9303Z" fill="currentColor"/>
          <path opacity="0.4" fill-rule="evenodd" clip-rule="evenodd" d="M20.5734 13.1591V16.9303L15.9021 14.2333V13.1591H20.5734Z" fill="currentColor"/>
        </svg>
      </div>
      <span class="text-2xl font-medium tracking-tight">BLVD</span>
    </a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#apartments" class="hover:text-white transition-colors">Apartments</a>
      <a href="#amenities" class="hover:text-white transition-colors">Amenities</a>
      <a href="#location" class="hover:text-white transition-colors">Location</a>
      <a href="#features" class="hover:text-white transition-colors">Features</a>
      <a href="#contact" class="hover:text-white transition-colors">Contact</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <a href="tel:7023500050" class="text-gray-300 hover:text-white transition-colors text-[13px] hidden lg:block">
      (702) 350-0050
    </a>
    <a href="#apply" class="bg-primary-600 hover:bg-primary-700 text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Apply Now
    </a>
  </div>
</nav>
