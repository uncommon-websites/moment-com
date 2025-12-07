<script lang="ts">
  // Stats Section
  // Background is a vertical bar chart pattern
</script>

<section class="py-24 relative overflow-hidden">
  <div class="max-w-[1400px] mx-auto px-6 relative z-10">
    <h2 class="text-3xl md:text-4xl font-semibold text-gray-900 max-w-xl mb-16 leading-tight">
      The first fixed income operating system designed to scale
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
      <div>
        <div class="text-4xl font-bold text-gray-900 mb-2">$5T+</div>
        <div class="text-sm text-gray-600 leading-relaxed">Assets held<br>by our clients</div>
      </div>
      <div>
        <div class="text-4xl font-bold text-gray-900 mb-2">3M+</div>
        <div class="text-sm text-gray-600 leading-relaxed">Orders processed<br>through our platform</div>
      </div>
      <div>
        <div class="text-4xl font-bold text-gray-900 mb-2">&lt;1s</div>
        <div class="text-sm text-gray-600 leading-relaxed">Median time to<br>execute an order</div>
      </div>
    </div>
  </div>

  <!-- Background Graph -->
  <div class="absolute bottom-0 left-0 right-0 h-64 flex items-end justify-between px-4 opacity-20 pointer-events-none gap-1">
    {#each Array(100) as _, i}
      <div 
        class="w-full bg-gray-900 rounded-t-sm"
        style="height: {Math.max(5, Math.sin(i * 0.1) * 50 + (i * i * 0.02) + Math.random() * 20)}%; opacity: {i > 80 ? 1 : 0.5}"
      ></div>
    {/each}
    <!-- Highlighted dot/line at the end -->
    <div class="absolute right-10 top-10 w-3 h-3 bg-gray-400 rounded-full border-2 border-white shadow-sm"></div>
  </div>
</section>
