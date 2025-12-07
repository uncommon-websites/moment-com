<script lang="ts">
  // Security Section
</script>

<section class="py-24 bg-gray-950 text-white">
  <div class="max-w-[1400px] mx-auto px-6">
    <h2 class="text-3xl md:text-4xl font-semibold text-center mb-20">
      Built with safety as a priority
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
      <!-- Card 1: Uptime -->
      <div class="bg-gray-900/50 border border-gray-800 rounded-xl p-8 relative overflow-hidden">
        <div class="relative z-10">
           <h3 class="font-bold text-lg mb-2"><span class="text-white">99.99% uptime.</span> <span class="text-gray-400 font-normal">Built for mission-critical performance. Infrastructure that delivers the stability and resilience that enterprise teams need.</span></h3>
        </div>
        <div class="mt-12 h-32 border-l border-b border-gray-700 relative">
           <div class="absolute bottom-0 right-0 text-xs text-gray-500 mb-2 mr-2">Dec 3, 3:15 PM = <span class="text-white font-bold">100%</span></div>
           <div class="absolute top-1/2 left-0 w-full h-px bg-gray-800 border-t border-dashed border-gray-600"></div>
           <div class="absolute right-4 top-4 w-2 h-2 bg-green-500 rounded-full shadow-[0_0_10px_rgba(34,197,94,0.5)]"></div>
           <div class="absolute right-4 top-4 h-full w-px bg-gray-700 border-l border-dashed border-gray-600 opacity-50"></div>
        </div>
      </div>

      <!-- Card 2: Certifications -->
      <div class="bg-gray-900/50 border border-gray-800 rounded-xl p-8 relative overflow-hidden flex flex-col justify-between">
        <div class="relative z-10">
           <h3 class="font-bold text-lg mb-2"><span class="text-white">Industry-standard certifications.</span> <span class="text-gray-400 font-normal">SOC 2 Type I & II certified. Meeting the highest standards for data protection and system reliability.</span></h3>
        </div>
        <div class="mt-8 flex justify-center relative">
           <!-- Concentric circles -->
           <div class="absolute inset-0 flex items-center justify-center">
              <div class="w-64 h-64 border border-gray-800 rounded-full"></div>
              <div class="absolute w-48 h-48 border border-gray-800 rounded-full"></div>
              <div class="absolute w-32 h-32 border border-gray-800 rounded-full"></div>
           </div>
           <div class="relative z-10 w-32 h-32 rounded-full bg-gray-900 border border-gray-700 flex flex-col items-center justify-center text-center p-4">
              <div class="text-xs text-gray-400 uppercase tracking-widest mb-1">SOC 2</div>
              <div class="text-xs text-gray-400 uppercase tracking-widest mb-1">TYPE II</div>
              <div class="text-[10px] text-gray-600 uppercase tracking-widest">CERTIFIED</div>
           </div>
        </div>
        <div class="mt-4 flex items-center gap-2 text-xs text-gray-500 border border-gray-800 rounded px-3 py-1 self-start">
           Trust center <svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
        </div>
      </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- Card 3: Encrypted -->
      <div class="bg-gray-900/50 border border-gray-800 rounded-xl p-8 relative overflow-hidden h-64">
        <h3 class="font-bold text-sm mb-2"><span class="text-white">Fully encrypted, end-to-end.</span> <span class="text-gray-400 font-normal">Secure at rest, in transit, and at every stage in between.</span></h3>
        <div class="absolute bottom-8 left-8">
           <div class="w-16 h-20 border border-gray-700 rounded flex flex-col items-center justify-center relative">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="gray" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="mb-2">
                 <path d="M21 2l-2 2m-7.61 7.61a5.5 5.5 0 1 1-7.778 7.778 5.5 5.5 0 0 1 7.777-7.777zm0 0L15.5 7.5m0 0l3 3L22 7l-3-3m-3.5 3.5L19 4"/>
              </svg>
              <span class="text-[10px] text-gray-500 absolute bottom-1 right-1">AES 256</span>
           </div>
        </div>
      </div>

      <!-- Card 4: SSO -->
      <div class="bg-gray-900/50 border border-gray-800 rounded-xl p-8 relative overflow-hidden h-64">
        <h3 class="font-bold text-sm mb-2"><span class="text-white">SAML SSO.</span> <span class="text-gray-400 font-normal">Enterprise-grade access control with secure SAML Single Sign-On.</span></h3>
        <div class="absolute bottom-0 left-0 right-0 flex justify-center items-end pb-8">
           <div class="w-32 h-20 border border-gray-700 rounded-t-lg relative">
              <div class="absolute inset-2 border border-gray-800 rounded-t"></div>
              <div class="absolute inset-4 border border-gray-800 rounded-t"></div>
           </div>
        </div>
      </div>

      <!-- Card 5: Permissioning -->
      <div class="bg-gray-900/50 border border-gray-800 rounded-xl p-8 relative overflow-hidden h-64">
        <h3 class="font-bold text-sm mb-2"><span class="text-white">Advanced user permissioning.</span> <span class="text-gray-400 font-normal">Set custom access at every level for rapid scaling.</span></h3>
        <div class="absolute bottom-0 left-0 right-0 h-32 flex items-center justify-center">
           <div class="w-48 h-48 border border-gray-800 rounded-full flex items-center justify-center relative top-12">
              <div class="w-32 h-32 border border-gray-800 rounded-full flex items-center justify-center">
                 <div class="w-16 h-16 border border-gray-700 rounded-full"></div>
              </div>
              <div class="absolute w-full flex justify-between px-4">
                 <div class="w-1 h-1 bg-white rounded-full"></div>
                 <div class="w-1 h-1 bg-white rounded-full"></div>
              </div>
              <div class="absolute text-[10px] text-gray-500 left-8">Trader</div>
              <div class="absolute text-[10px] text-gray-500 right-8">Advisor</div>
           </div>
        </div>
      </div>
    </div>
  </div>
</section>
