<script>
  import TogglePasswordItem from "../../components/TogglePasswordItem.svelte";
</script>

<svelte:head>
  <title>Toggle Password</title>
  <meta name="description" content="Toggle Password" />
</svelte:head>

<div>
  <div class="mb-10">
    <h2 class="mb-2">Toggle Password 1</h2>
    <TogglePasswordItem groupId="first-group" />
  </div>
  <div class="mb-10">
    <h2 class="mb-2">Toggle Password 2</h2>
    <TogglePasswordItem groupId="second-group" />
  </div>
</div>
