<script lang="ts">
import "../app.css";
</script>

<!-- HTML & body wrapper -->
<svelte:head>
  <title>Fametonic SvelteKit</title>
  <meta name="description" content="Fametonic SvelteKit Application" />
  <html lang="en"></html>
</svelte:head>

<body class="antialiased bg-dark text-white font-figtree">
  <slot />
</body>
