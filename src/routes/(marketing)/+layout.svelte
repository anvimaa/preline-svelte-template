<script>
  import { afterNavigate } from "$app/navigation";

  import "../styles.css";

  afterNavigate(() => {
    // @ts-ignore
    HSStaticMethods.autoInit();
  });
</script>

<slot />
