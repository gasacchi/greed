<script lang="ts">
  import StatusBar from "$lib/app/StatusBar.svelte";
  import TabBar from "$lib/app/TabBar.svelte";
  import TitleBar from "$lib/app/TitleBar.svelte";
  import "../app.css";
</script>

<div class="bg-base h-screen w-scree">
  <TitleBar />

  <TabBar />

  <main class="absolute top-9 left-9 h-[91.8%] bg-red w-[97.3%]">
    <slot />
  </main>

  <StatusBar />
</div>
