<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Browse catalog",
      desc: "Explore our extensive selection of flowering annuals, perennials, and specialty cultivars available for wholesale.",
      img: "/generated/image-variety-of-specialty-flowering-cultivars-1765573311002-8.webp"
    },
    {
      num: "02",
      title: "Place order",
      desc: "Contact our sales team to discuss your needs. We'll create a customized proposal based on your volume and delivery requirements.",
      img: "/generated/image-professional-garden-center-buyer-or-nurs-1765573296626-4.webp"
    },
    {
      num: "03",
      title: "We cultivate",
      desc: "Our expert growers ensure consistent quality through controlled greenhouse cultivation and rigorous quality control.",
      img: "/generated/image-greenhouse-workers-tending-to-flowering--1765573299839-5.webp"
    },
    {
      num: "04",
      title: "Reliable delivery",
      desc: "Your order arrives fresh via our regional distribution network. Consistent supply you can count on, season after season.",
      img: "/generated/image-delivery-trucks-at-loading-dock-of-green-1765573289800-2.webp"
    }
  ];
</script>

<section class="bg-white py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Wholesale ordering made simple. Consistent quality delivered on schedule.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-[oklch(0.696_0.17_162.48)] text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
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
        <h3 class="text-2xl font-light mb-2">Ready to partner with us?</h3>
        <p class="text-gray-500 text-sm">Learn more about our wholesale program and distribution network.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          How it works
        </button>
        <button class="px-6 py-3 bg-[oklch(0.696_0.17_162.48)] hover:bg-[oklch(0.596_0.145_163.225)] text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
          Download catalog
        </button>
      </div>
    </div>
  </div>
</section>
