<script lang="ts">
  import StatusBar from "$lib/app/StatusBar.svelte";
  import TabBar from "$lib/app/TabBar.svelte";
  import TitleBar from "$lib/app/TitleBar.svelte";
  import "../app.css";
</script>

<div id="app">
  <TitleBar />

  <TabBar />

  <main>
    <slot />
  </main>

  <StatusBar />
</div>

<style lang="postcss">
  div#app {
    @apply bg-base h-screen w-screen;
  }
</style>
