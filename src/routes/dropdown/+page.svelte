<script>
  import DropdownItem from "../../components/DropdownItem.svelte";
</script>

<svelte:head>
  <title>Dropdown</title>
  <meta name="description" content="Dropdown" />
</svelte:head>

<div class="flex gap-4">
  <div>
    <h2 class="mb-2">Dropdown 1</h2>
    <DropdownItem title="Action" />
  </div>
  <div>
    <h2 class="mb-2">Dropdown 2</h2>
    <DropdownItem title="Action" />
  </div>
</div>
