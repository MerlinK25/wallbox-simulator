<script lang="ts">
  import Heading3 from "../components/Heading3.svelte";
  import { get } from "svelte/store";
  import { wallboxAuthMode } from "./store";

  let authMode = "unknown";

  wallboxAuthMode.subscribe((value) => {
    authMode = value;
  });
</script>

<Heading3>Currently set to {authMode}</Heading3>

<style></style>
