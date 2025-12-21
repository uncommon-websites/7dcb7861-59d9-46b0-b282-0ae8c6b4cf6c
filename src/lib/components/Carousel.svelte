<script lang="ts">
  const images = [
    {
      src: "/generated/image-stylish-studio-apartment-interior-with-m-1766289828458-1.webp",
      title: "Studio",
      desc: "Modern furnishings"
    },
    {
      src: "/generated/image-cozy-furnished-one-bedroom-apartment-liv-1766289845554-8.webp",
      title: "One Bedroom",
      desc: "Spacious living"
    },
    {
      src: "/generated/image-modern-apartment-kitchen-with-subway-til-1766289830882-2.webp",
      title: "Kitchen",
      desc: "Subway tile backsplash"
    }
  ];
</script>

<section class="bg-white pb-24 overflow-hidden">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img.src} alt={img.title} class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Furnished & unfurnished options <span class="text-gray-400">Studios & 1-bedrooms</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
