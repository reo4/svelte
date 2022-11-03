<script>
  import Navbar from "../lib/components/Navbar.svelte"
  import "./style.css"
</script>

<Navbar />

<div class="container">
  <slot />
</div>

<svelte:head>
  <link
    href="https://fonts.googleapis.com/css2?family=Heebo:wght@300;400;700&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<style>
  .container {
    max-width: 1200px;
    margin: 0 auto;
  }
</style>
