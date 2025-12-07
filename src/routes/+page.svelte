<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import TrustedBy from "$lib/components/TrustedBy.svelte";
  import Testimonials from "$lib/components/Testimonials.svelte";
  import Stats from "$lib/components/Stats.svelte";
  import Products from "$lib/components/Products.svelte";
  import Features from "$lib/components/Features.svelte";
  import Security from "$lib/components/Security.svelte";
  import Solutions from "$lib/components/Solutions.svelte";
  import Quote from "$lib/components/Quote.svelte";
  import FooterCTA from "$lib/components/FooterCTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen bg-white font-sans text-gray-900 selection:bg-gray-900 selection:text-white">
  <Navbar className="sticky top-0 z-50 bg-white/80 backdrop-blur-md" />
  
  <main>
    <Hero />
    <TrustedBy />
    <Testimonials />
    <Stats />
    <Products />
    <Features />
    <Security />
    <Solutions />
    <Quote />
    <FooterCTA />
  </main>

  <Footer />
</div>

