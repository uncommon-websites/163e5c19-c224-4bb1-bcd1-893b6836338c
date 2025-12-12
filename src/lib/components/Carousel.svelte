<script lang="ts">
  const images = [
    "/generated/image-interior-of-commercial-greenhouse-with-r-1765573285070-1.webp",
    "/generated/image-delivery-trucks-at-loading-dock-of-green-1765573289800-2.webp",
    "/generated/image-close-up-of-healthy-vibrant-flowering-pl-1765573293312-3.webp"
  ];
</script>

<section class="bg-white pb-24 overflow-hidden">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img} alt="Pleasant Valley Farms operations" class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Greenhouse cultivation <span class="text-gray-400">Regional distribution</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-[oklch(0.696_0.17_162.48)]"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
