<script lang="ts">
  // Features Section Container
  // Includes the toggle and the 3 feature blocks
</script>

<section class="py-24 bg-white">
  <div class="max-w-[1400px] mx-auto px-6">
    
    <!-- Toggle -->
    <div class="flex justify-center mb-24">
      <div class="inline-flex items-center bg-gray-100 p-1 rounded-full">
        <span class="px-4 py-2 text-sm font-medium text-gray-500">Purpose-built for modern</span>
        <button class="px-4 py-2 text-sm font-medium text-gray-900 bg-white rounded-full shadow-sm">Traders</button>
        <button class="px-4 py-2 text-sm font-medium text-gray-500 hover:text-gray-900">Portfolio managers</button>
        <button class="px-4 py-2 text-sm font-medium text-gray-500 hover:text-gray-900">Compliance</button>
      </div>
    </div>

    <!-- Feature 1: Traders -->
    <div class="flex flex-col md:flex-row gap-16 items-center mb-32">
      <div class="w-full md:w-1/3">
        <div class="text-xs font-semibold text-gray-500 uppercase tracking-widest mb-4">Traders</div>
        <h2 class="text-3xl md:text-4xl font-semibold text-gray-900 mb-6 leading-tight">
          Leverage the most powerful trader workstation on the street
        </h2>
        <p class="text-gray-600 mb-8 leading-relaxed">
          An order and execution management system with automated trading and advanced order management capabilities that scales with you.
        </p>
        <a href="#" class="text-sm font-medium text-gray-900 hover:underline mb-12 block">Read more</a>
        
        <div class="flex flex-wrap gap-4">
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2"/></svg> OMS
          </span>
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/></svg> EMS
          </span>
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M2 12h20"/></svg> Data and Analytics
          </span>
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/></svg> Risk and Compliance
          </span>
        </div>
      </div>

      <div class="w-full md:w-2/3 bg-gray-50 rounded-xl p-8 md:p-12">
        <div class="bg-white rounded-lg shadow-sm border border-gray-200 p-4 max-w-md mx-auto">
          <div class="text-xs text-gray-400 font-medium mb-4 uppercase tracking-wider">Trade blotter</div>
          <div class="flex items-start gap-4 mb-4">
            <div class="w-10 h-10 bg-blue-600 rounded flex items-center justify-center text-white font-bold text-xs">GM</div>
            <div class="flex-1">
              <div class="flex justify-between items-center mb-1">
                <span class="font-semibold text-gray-900 text-sm">Buy GM 1.2% 03/20/2025</span>
                <span class="text-xs text-gray-500">True</span>
              </div>
              <div class="flex gap-4 text-xs text-gray-500 mb-3">
                <span>Price $84.09</span>
                <span>Yield 4.582%</span>
                <span>QTY 28</span>
              </div>
              <div class="bg-green-50 text-green-700 text-xs px-3 py-2 rounded flex justify-between items-center">
                <span>Auto-routing rule matched: Send to smart order router</span>
                <div class="w-4 h-4 bg-green-500 rounded-full flex items-center justify-center text-white text-[10px]">✓</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Feature 2: Portfolio Managers -->
    <div class="flex flex-col md:flex-row-reverse gap-16 items-center mb-32">
      <div class="w-full md:w-1/3">
        <div class="text-xs font-semibold text-gray-500 uppercase tracking-widest mb-4">Portfolio Managers</div>
        <h2 class="text-3xl md:text-4xl font-semibold text-gray-900 mb-6 leading-tight">
          Deliver personalized portfolios across 100K+ accounts
        </h2>
        <p class="text-gray-600 mb-8 leading-relaxed">
          A powerful portfolio management system designed to handle multiple sleeves, millions of accounts, and flexible customizations.
        </p>
        <a href="#" class="text-sm font-medium text-gray-900 hover:underline mb-12 block">Read more</a>
        
        <div class="flex flex-wrap gap-4">
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3v18"/></svg> PMS
          </span>
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2"/></svg> OMS
          </span>
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16v16H4z"/></svg> Portfolio Accounting
          </span>
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M2 12h20"/></svg> Data and Analytics
          </span>
        </div>
      </div>

      <div class="w-full md:w-2/3 bg-gray-50 rounded-xl p-8 md:p-12">
        <div class="bg-white rounded-lg shadow-sm border border-gray-200 p-6 max-w-md mx-auto">
           <div class="flex items-center gap-3 mb-4">
              <div class="w-8 h-8 bg-green-600 rounded flex items-center justify-center text-white text-xs font-bold">DE</div>
              <div class="flex-1">
                 <div class="text-sm font-semibold text-gray-900">Buy DE 3.577%, 08/23/2032</div>
                 <div class="text-xs text-gray-500">24422ETH2</div>
              </div>
              <div class="px-2 py-1 bg-purple-100 text-purple-700 text-[10px] rounded font-medium">Finding optimal allocations...</div>
           </div>
           
           <div class="space-y-2">
              <div class="bg-orange-50 p-3 rounded border border-orange-100 flex justify-between items-center">
                 <span class="text-xs text-orange-800 font-medium">Finding accounts that can buy/hold this bond</span>
                 <div class="flex gap-1">
                    <div class="w-1.5 h-1.5 bg-orange-400 rounded-full"></div>
                    <div class="w-1.5 h-1.5 bg-orange-400 rounded-full"></div>
                    <div class="w-1.5 h-1.5 bg-orange-400 rounded-full"></div>
                 </div>
              </div>
              <div class="bg-orange-50 p-3 rounded border border-orange-100 flex justify-between items-center">
                 <span class="text-xs text-orange-800 font-medium">Allocating to accounts by best fit</span>
                 <div class="flex gap-1">
                    <div class="w-1.5 h-1.5 bg-orange-400 rounded-full"></div>
                    <div class="w-1.5 h-1.5 bg-orange-400 rounded-full"></div>
                    <div class="w-1.5 h-1.5 bg-orange-400 rounded-full"></div>
                 </div>
              </div>
           </div>
        </div>
      </div>
    </div>

    <!-- Feature 3: Compliance -->
    <div class="flex flex-col md:flex-row gap-16 items-center">
      <div class="w-full md:w-1/3">
        <div class="text-xs font-semibold text-gray-500 uppercase tracking-widest mb-4">Compliance</div>
        <h2 class="text-3xl md:text-4xl font-semibold text-gray-900 mb-6 leading-tight">
          Stay compliant at every layer, from pre-trade checks to post-trade audits
        </h2>
        <p class="text-gray-600 mb-8 leading-relaxed">
          Configure checks across every workflow. Set firmwide rules and account-level controls. Monitor activity in real time.
        </p>
        <a href="#" class="text-sm font-medium text-gray-900 hover:underline mb-12 block">Read more</a>
        
        <div class="flex flex-wrap gap-4">
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2"/></svg> OMS
          </span>
          <span class="inline-flex items-center gap-2 px-3 py-1 bg-gray-50 border border-gray-200 rounded-full text-xs font-medium text-gray-700">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/></svg> Risk and Compliance
          </span>
        </div>
      </div>

      <div class="w-full md:w-2/3 bg-gray-50 rounded-xl p-8 md:p-12">
        <div class="bg-white rounded-lg shadow-sm border border-gray-200 p-6 max-w-md mx-auto relative">
           <div class="text-xs text-gray-400 font-medium mb-4">Create risk control</div>
           <div class="flex items-center gap-3 mb-6">
              <span class="text-xl">✋</span>
              <span class="text-sm font-medium text-gray-900">Hold for manual review if</span>
              <span class="text-sm text-gray-400 border-b border-gray-200 pb-0.5">Callable</span>
              <span class="text-sm text-gray-400 border-b border-gray-200 pb-0.5">equals to</span>
              <span class="text-sm text-gray-400 border-b border-gray-200 pb-0.5">True</span>
              <span class="text-sm text-gray-400">for the bond</span>
           </div>

           <div class="space-y-3 mb-6">
              <div class="flex justify-between items-center text-xs">
                 <span class="text-gray-500">Apply this rule to</span>
                 <span class="bg-gray-100 px-2 py-1 rounded text-gray-700">All trades</span>
                 <span class="text-gray-400">All trades</span>
              </div>
              <div class="flex justify-between items-center text-xs">
                 <span></span>
                 <span class="bg-gray-100 px-2 py-1 rounded text-gray-700">All bonds</span>
                 <span class="text-gray-400">18,483 bonds</span>
              </div>
              <div class="flex justify-between items-center text-xs">
                 <span></span>
                 <span class="bg-gray-100 px-2 py-1 rounded text-gray-700">All organizations</span>
                 <span class="text-gray-400">5 organizations</span>
              </div>
              <div class="flex justify-between items-center text-xs">
                 <span></span>
                 <span class="bg-gray-100 px-2 py-1 rounded text-gray-700">All advisors</span>
                 <span class="text-gray-400">148 advisors</span>
              </div>
              <div class="flex justify-between items-center text-xs">
                 <span></span>
                 <span class="bg-gray-100 px-2 py-1 rounded text-gray-700">All households</span>
                 <span class="text-gray-400">361 households</span>
              </div>
              <div class="flex justify-between items-center text-xs">
                 <span></span>
                 <span class="bg-gray-100 px-2 py-1 rounded text-gray-700">All accounts</span>
                 <span class="text-gray-400">402 accounts</span>
              </div>
           </div>

           <div class="flex justify-center">
              <button class="bg-gray-900 text-white text-xs px-4 py-2 rounded">Create rule</button>
           </div>
           
           <!-- Cursor -->
           <div class="absolute top-12 right-1/3 pointer-events-none">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="black" stroke="white" stroke-width="1">
                 <path d="M3 3l7.5 18.5 3.5-8 7.5-3.5L3 3z"/>
              </svg>
           </div>
        </div>
      </div>
    </div>

  </div>
</section>
