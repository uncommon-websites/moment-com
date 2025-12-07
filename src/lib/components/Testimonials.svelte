<script lang="ts">
  // Testimonials Carousel
  // For simplicity in this recreation, I'll show the two visible cards as in the screenshot.
  // In a real app, this would be a carousel.
</script>

<section class="py-24 bg-white overflow-hidden">
  <div class="max-w-[1400px] mx-auto px-6">
    <div class="flex justify-between items-end mb-12">
      <h2 class="text-3xl md:text-4xl font-semibold text-gray-900 max-w-lg leading-tight">
        Powering fixed income for leading financial institutions
      </h2>
      <div class="flex gap-2">
        <button class="w-10 h-10 rounded-full border border-gray-200 flex items-center justify-center text-gray-400 hover:text-gray-900 hover:border-gray-900 transition-colors">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full border border-gray-200 flex items-center justify-center text-gray-400 hover:text-gray-900 hover:border-gray-900 transition-colors">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
    </div>

    <div class="flex gap-8 overflow-x-auto pb-8 snap-x">
      <!-- Card 1 -->
      <div class="min-w-[600px] bg-gray-50 rounded-xl p-8 border border-gray-100 snap-start">
        <div class="flex justify-between items-start mb-8">
          <div class="flex items-center gap-2">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" class="text-blue-600">
                <rect x="4" y="4" width="6" height="16" />
                <rect x="12" y="4" width="8" height="6" />
            </svg>
            <span class="font-bold text-gray-900">LPL Financial</span>
          </div>
          <div class="text-[10px] font-mono uppercase tracking-wider text-gray-500 bg-white px-2 py-1 rounded border border-gray-200">
            <span class="text-green-600">↗</span> 10x Increase in Productivity
          </div>
        </div>
        <blockquote class="text-xl font-medium text-gray-900 mb-8 leading-relaxed">
          “In my 25+ years of experience, Moment is the innovative solution we’ve been waiting for and the only player in the market offering a single, unified fixed income platform.”
        </blockquote>
        <div class="mb-8">
          <div class="font-semibold text-gray-900">Michael Haire</div>
          <div class="text-sm text-gray-500">Senior VP of Fixed Income at LPL</div>
        </div>
        <button class="text-sm font-medium text-gray-900 border border-gray-200 bg-white px-4 py-2 rounded hover:bg-gray-50 transition-colors">
          Read LPL announcement
        </button>
      </div>

      <!-- Card 2 -->
      <div class="min-w-[600px] bg-gray-50 rounded-xl p-8 border border-gray-100 snap-start">
        <div class="flex justify-between items-start mb-8">
          <div class="flex items-center gap-2">
            <span class="font-bold text-gray-900 lowercase text-xl">altruist</span>
          </div>
        </div>
        <blockquote class="text-xl font-medium text-gray-900 mb-8 leading-relaxed">
          “We haven’t had people building in this space with that caliber, a mix of best-in-class engineers and fixed income experts.”
        </blockquote>
        <div class="mb-8">
          <div class="font-semibold text-gray-900">Jason Wenk</div>
          <div class="text-sm text-gray-500">CEO of Altruist</div>
        </div>
        <button class="text-sm font-medium text-gray-900 border border-gray-200 bg-white px-4 py-2 rounded hover:bg-gray-50 transition-colors">
          Read Altruist study
        </button>
      </div>
    </div>

    <!-- Dots -->
    <div class="flex justify-center gap-2 mt-4">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
