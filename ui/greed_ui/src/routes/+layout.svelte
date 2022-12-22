<script lang="ts">
  import CommandButton from "$lib/CommandButton.svelte";
  import Taskbar from "$lib/Taskbar.svelte";
  import "../app.css";
</script>

<div class="bg-base h-screen w-screen select-none">
  <main class="h-[96%] bg-surface0 w-full">
    <slot />
  </main>

  <CommandButton />
</div>
