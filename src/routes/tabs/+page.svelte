<script>
  import TabsItem from "../../components/TabsItem.svelte";
</script>

<svelte:head>
  <title>Tabs</title>
  <meta name="description" content="Tabs" />
</svelte:head>

<div>
  <div class="mb-10">
    <h2 class="mb-2">Tabs 1</h2>
    <TabsItem groupId="first-group" />
  </div>
  <div class="mb-10">
    <h2 class="mb-2">Tabs 2</h2>
    <TabsItem groupId="second-group" />
  </div>
</div>
