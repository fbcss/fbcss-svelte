<script lang="ts">
  import './layout.css';

  let { children } = $props();
</script>

<svelte:head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sermon Search</title>
  <link rel="icon" href="/favicon.svg" />
  <link rel="manifest" href="/manifest.json" />
</svelte:head>
{@render children()}
