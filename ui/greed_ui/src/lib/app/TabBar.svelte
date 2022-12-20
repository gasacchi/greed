<script>
  import { page } from "$app/stores";

  import CodeEditorIcon from "@icons/CodeEditorIcon.svelte";
  import DashboardIcon from "@icons/DashboardIcon.svelte";
</script>

<aside class="bg-mantle border-b-2 border-base w-9 h-[92%]">
  <nav class="flex flex-col items-center">
    <a
      href="/"
      class="p-2 stroke-surface1 hover:stroke-overlay0"
      class:active={$page.route.id == "/"}
    >
      <DashboardIcon class="w-4" />
    </a>
    <a
      href="/editor"
      class="p-2 stroke-surface1 hover:stroke-overlay0"
      class:active={$page.route.id == "/editor"}
    >
      <CodeEditorIcon class="w-4" />
    </a>
  </nav>
</aside>

<style lang="postcss">
  a.active {
    @apply stroke-rosewater w-full bg-base;
  }
</style>
