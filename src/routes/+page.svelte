<script>
  import Footer1 from "../components/sections/footers/Footer1.svelte";
  import FloatiangHeader from "../components/sections/header/FloatiangHeader.svelte";
  import Hero1 from "../components/sections/hero/Hero1.svelte";
  import Hero2 from "../components/sections/hero/Hero2.svelte";
  import Hero3 from "../components/sections/hero/Hero3.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<FloatiangHeader />

<!-- ========== MAIN CONTENT ========== -->
<main id="content">
  <div class="max-w-[85rem] mx-auto pt-12 pb-10 px-4 sm:px-6 lg:px-8 md:pt-24">
    <Hero1 />
    <Hero2 />
    <Hero3 />
  </div>
</main>
<!-- ========== END MAIN CONTENT ========== -->

<Footer1 />
