<script lang="ts">
  export let className = "";
</script>

<nav class="flex items-center justify-between px-6 py-4 max-w-[1400px] mx-auto {className}">
  <div class="flex items-center gap-12">
    <a href="/" class="flex items-center gap-2 text-gray-900 font-bold text-xl tracking-tight">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-gray-900">
        <path d="M2 12C2 12 5 6 12 6C19 6 22 12 22 12" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M2 12C2 12 5 18 12 18C19 18 22 12 22 12" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
        <!-- Abstract shape approximation -->
        <path d="M12 8L12 16" stroke="currentColor" stroke-width="2.5" stroke-linecap="round"/>
      </svg>
      Moment
    </a>

    <div class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-600">
      <a href="#" class="hover:text-gray-900 transition-colors">Customers</a>
      <button class="flex items-center gap-1 hover:text-gray-900 transition-colors group">
        Solutions
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="group-hover:rotate-180 transition-transform">
          <path d="m6 9 6 6 6-6"/>
        </svg>
      </button>
      <button class="flex items-center gap-1 hover:text-gray-900 transition-colors group">
        About
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="group-hover:rotate-180 transition-transform">
          <path d="m6 9 6 6 6-6"/>
        </svg>
      </button>
    </div>
  </div>

  <div class="flex items-center gap-6 text-sm font-medium">
    <a href="#" class="text-gray-600 hover:text-gray-900 transition-colors">Sign in</a>
    <a href="#" class="bg-gray-900 text-white px-4 py-2 rounded-md hover:bg-gray-800 transition-colors flex items-center gap-2 group">
      Book a demo
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="group-hover:translate-x-0.5 transition-transform">
        <path d="M5 12h14"/>
        <path d="m12 5 7 7-7 7"/>
      </svg>
    </a>
  </div>
</nav>
