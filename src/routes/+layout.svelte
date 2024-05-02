<script>
  import { afterNavigate } from "$app/navigation";

  import "./styles.css";

  afterNavigate(() => {
    HSStaticMethods.autoInit();
  });
</script>

<div>
  <header>
    <div class="py-[20px] px-[50px]">
      <div class="flex flex-wrap gap-x-4">
        <a href="/">Home</a>
        <a href="/accordion">Accordion</a>
        <a href="/carousel">Carousel</a>
        <a href="/collapse">Collapse</a>
        <a href="/dropdown">Dropdown</a>
        <a href="/input-number">Input Number</a>
        <a href="/overlay">Overlay</a>
        <a href="/pin-input">Pin Input</a>
        <a href="/remove-element">Remove Element</a>
        <a href="/scrollspy">Scrollspy</a>
        <a href="/select">Select</a>
        <a href="/stepper">Stepper</a>
        <a href="/strong-password">Strong Password</a>
        <a href="/tabs">Tabs</a>
        <a href="/toggle-count">Toggle Count</a>
        <a href="/toggle-password">Toggle Password</a>
        <a href="/tooltip">Tooltip</a>
      </div>
    </div>
  </header>

  <div class="pb-[20px] px-[50px]">
    <slot />
  </div>
</div>
