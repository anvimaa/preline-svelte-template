<script>
  import Clientes1 from "../../components/sections/clientes/Clientes1.svelte";
  import Clientes2 from "../../components/sections/clientes/Clientes2.svelte";
  import Contact1 from "../../components/sections/contacts/Contact1.svelte";
  import Contact2 from "../../components/sections/contacts/Contact2.svelte";
  import Faq1 from "../../components/sections/faq/FAQ1.svelte";
  import Feature1 from "../../components/sections/features/Feature1.svelte";
  import Feature2 from "../../components/sections/features/Feature2.svelte";
  import Feature3 from "../../components/sections/features/Feature3.svelte";
  import Feature4 from "../../components/sections/features/Feature4.svelte";
  import Feature5 from "../../components/sections/features/Feature5.svelte";
  import Footer1 from "../../components/sections/footers/Footer1.svelte";
  import FloatiangHeader from "../../components/sections/header/FloatiangHeader.svelte";
  import HeaderMegaMenu from "../../components/sections/header/HeaderMegaMenu.svelte";
  import StickyFloatingHeader from "../../components/sections/header/StickyFloatingHeader.svelte";
  import Hero1 from "../../components/sections/hero/Hero1.svelte";
  import Hero2 from "../../components/sections/hero/Hero2.svelte";
  import Hero3 from "../../components/sections/hero/Hero3.svelte";
  import HeroForm1 from "../../components/sections/hero/HeroForm1.svelte";
  import Table1 from "../../components/sections/tables/Table1.svelte";
  import Table2 from "../../components/sections/tables/Table2.svelte";
  import Testimonial1 from "../../components/sections/testimonials/Testimonial1.svelte";
  import Testimonial2 from "../../components/sections/testimonials/Testimonial2.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<!-- <FloatiangHeader /> -->
<!-- <HeaderMegaMenu /> -->
<StickyFloatingHeader />

<!-- ========== MAIN CONTENT ========== -->
<main id="content">
  <div class="max-w-[85rem] mx-auto pt-12 pb-10 px-4 sm:px-6 lg:px-8 md:pt-24">
    <Hero1 />
    <Hero2 />
    <Hero3 />
    <HeroForm1 />

    <Clientes1 />
    <Clientes2 />

    <Feature1 />
    <Feature2 />
    <Feature3 />
    <Feature4 />
    <!-- <Feature5 /> -->

    <Contact1 />
    <Contact2 />
    <Table1 />
    <Table2 />

    <Testimonial1 />
    <Testimonial2 />

    <Faq1 />
  </div>
</main>
<!-- ========== END MAIN CONTENT ========== -->

<Footer1 />
