<script>
  import RemoveElementItem from "../../components/RemoveElementItem.svelte";
</script>

<svelte:head>
  <title>Remove Element</title>
  <meta name="description" content="Remove Element" />
</svelte:head>

<div>
  <div class="mb-10">
    <h2 class="mb-2">Remove Element 1</h2>
    <RemoveElementItem contentId="remove-element-1" />
  </div>
  <div class="mb-10">
    <h2 class="mb-2">Remove Element 2</h2>
    <RemoveElementItem contentId="remove-element-2" />
  </div>
</div>
