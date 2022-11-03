<script>
  let count = 0
  $: if (count > 10) {
    console.log(count)
  }
</script>

{#if count > 20}
  <h1>Contact-us</h1>
{/if}
<button on:click={() => (count = count + 1)}>Increase button</button>

<svelte:head>
  {#if count > 10}
    <title>Hello from Contact Us</title>
  {/if}
</svelte:head>
