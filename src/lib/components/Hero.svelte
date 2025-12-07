<script lang="ts">
  // Hero section
</script>

<section class="relative pt-20 pb-32 overflow-hidden">
  <!-- Background Pattern -->
  <div class="absolute inset-0 -z-10 flex items-center justify-center pointer-events-none opacity-40">
    <svg width="100%" height="100%" viewBox="0 0 1000 1000" preserveAspectRatio="xMidYMin slice">
      <defs>
        <radialGradient id="hero-grad" cx="50%" cy="50%" r="50%" fx="50%" fy="50%">
          <stop offset="0%" stop-color="white" stop-opacity="1" />
          <stop offset="100%" stop-color="white" stop-opacity="0" />
        </radialGradient>
      </defs>
      <g stroke="#e5e7eb" stroke-width="1">
        <!-- Generating radial lines -->
        {#each Array(60) as _, i}
            <line x1="500" y1="1200" x2={500 + 1000 * Math.cos((i * 3 - 90) * Math.PI / 180)} y2={1200 + 1000 * Math.sin((i * 3 - 90) * Math.PI / 180)} />
        {/each}
        {#each Array(60) as _, i}
            <line x1="500" y1="1200" x2={500 + 1000 * Math.cos((-i * 3 - 90) * Math.PI / 180)} y2={1200 + 1000 * Math.sin((-i * 3 - 90) * Math.PI / 180)} />
        {/each}
      </g>
      <!-- Fade out bottom/center -->
      <circle cx="500" cy="1200" r="400" fill="white" />
    </svg>
  </div>

  <div class="max-w-4xl mx-auto px-6 text-center">
    <h1 class="text-5xl md:text-6xl font-semibold tracking-tight text-gray-900 mb-6 leading-[1.1]">
      Solving the Hardest<br />Problems in Fixed Income
    </h1>
    <p class="text-lg text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed">
      Engineering the future of fixed income with the world's<br class="hidden md:block"/> leading financial institutions.
    </p>
    <div class="flex justify-center">
      <a href="#" class="bg-gray-900 text-white px-6 py-3 rounded-md hover:bg-gray-800 transition-colors flex items-center gap-2 group font-medium">
        Book a demo
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="group-hover:translate-x-0.5 transition-transform">
          <path d="M5 12h14"/>
          <path d="m12 5 7 7-7 7"/>
        </svg>
      </a>
    </div>
  </div>
</section>
