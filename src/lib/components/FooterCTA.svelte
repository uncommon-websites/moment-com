<script lang="ts">
  // Footer CTA
</script>

<section class="py-32 bg-gray-900 relative overflow-hidden">
  <!-- Wave Pattern Background -->
  <div class="absolute inset-0 opacity-20 pointer-events-none">
     <svg width="100%" height="100%" viewBox="0 0 1440 600" preserveAspectRatio="none">
        <path d="M0,600 C300,500 400,300 800,400 C1200,500 1300,200 1440,300 L1440,600 L0,600 Z" fill="none" stroke="#4b5563" stroke-width="1"/>
        <path d="M0,600 C320,520 420,320 820,420 C1220,520 1320,220 1440,320 L1440,600 L0,600 Z" fill="none" stroke="#4b5563" stroke-width="1"/>
        <path d="M0,600 C340,540 440,340 840,440 C1240,540 1340,240 1440,340 L1440,600 L0,600 Z" fill="none" stroke="#4b5563" stroke-width="1"/>
        <path d="M0,600 C360,560 460,360 860,460 C1260,560 1360,260 1440,360 L1440,600 L0,600 Z" fill="none" stroke="#4b5563" stroke-width="1"/>
        <path d="M0,600 C380,580 480,380 880,480 C1280,580 1380,280 1440,380 L1440,600 L0,600 Z" fill="none" stroke="#4b5563" stroke-width="1"/>
        
        <!-- More lines for density -->
        {#each Array(20) as _, i}
           <path d={`M0,600 C${300 + i*10},${500 - i*5} ${400 + i*10},${300 + i*5} ${800 + i*10},${400 - i*5} ${1200 + i*10},${500 + i*5} ${1300 + i*10},${200 + i*5} 1440,${300 + i*5} L1440,600 L0,600 Z`} fill="none" stroke="#374151" stroke-width="1" opacity="0.5"/>
        {/each}
     </svg>
  </div>

  <div class="max-w-[1400px] mx-auto px-6 relative z-10 flex flex-col md:flex-row justify-end items-center">
    <div class="max-w-xl text-right"> <!-- Actually screenshot shows text on right? No, text is right aligned or centered? Let's check screenshot. Text "The Operating System for Fixed Income" is on the right side. -->
       <h2 class="text-4xl md:text-5xl font-semibold text-white mb-8 leading-tight">
          The Operating System<br>for Fixed Income
       </h2>
       <div class="flex justify-end">
          <a href="#" class="bg-white text-gray-900 px-6 py-3 rounded-md hover:bg-gray-100 transition-colors font-medium">
             Book a demo
          </a>
       </div>
    </div>
  </div>
</section>
