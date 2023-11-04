<script lang="ts">
  import ParaglideJsSvelteKitAdapter from "../lib/ParaglideSvelteKit.svelte"
  import * as runtime from "../paraglide-js/runtime";
</script>

<ParaglideJsSvelteKitAdapter {...runtime}>
  <slot></slot>
</ParaglideJsSvelteKitAdapter>