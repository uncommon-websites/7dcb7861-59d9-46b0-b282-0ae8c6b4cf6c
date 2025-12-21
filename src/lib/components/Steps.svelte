<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Browse apartments",
      desc: "Explore our studio and one-bedroom options. Choose between furnished or unfurnished units.",
      img: "/generated/image-stylish-studio-apartment-interior-with-m-1766289828458-1.webp"
    },
    {
      num: "02",
      title: "Apply online",
      desc: "Complete your application through our AppFolio system. Quick, secure, and convenient.",
      img: "/generated/image-cozy-furnished-one-bedroom-apartment-liv-1766289845554-8.webp"
    },
    {
      num: "03",
      title: "Schedule a tour",
      desc: "Visit the property in person. See the amenities, meet our team, and envision your new home.",
      img: "/generated/image-chic-shallow-pool-with-cascading-waterfa-1766289833341-3.webp"
    },
    {
      num: "04",
      title: "Move in",
      desc: "Once approved, sign your lease and move into your new Strip-adjacent home. Welcome to BLVD!",
      img: "/generated/image-young-professional-unpacking-in-modern-f-1766289838112-5.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6" id="apply">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Move in with four simple steps. Your Vegas home awaits.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Ready to apply?</h3>
        <p class="text-gray-500 text-sm">Office hours: Mon-Fri 8am-5pm • Weekends by appointment</p>
      </div>
      <div class="flex gap-4">
        <a href="tel:7023500050" class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          Call (702) 350-0050
        </a>
        <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" x2="8" y1="13" y2="13"/><line x1="16" x2="8" y1="17" y2="17"/></svg>
          Start application
        </button>
      </div>
    </div>
  </div>
</section>
