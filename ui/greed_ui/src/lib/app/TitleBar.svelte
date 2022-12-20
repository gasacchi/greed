<script>
  import LogoIcon from "@icons/LogoIcon.svelte";
  import CommandPalette from "@app/CommandPalette.svelte";
  import MoreIcon from "@icons/MoreIcon.svelte";
  import MinimizeIcon from "@icons/MinimizeIcon.svelte";
  import MaximizeIcon from "@icons/MaximizeIcon.svelte";
  import CloseIcon from "@icons/CloseIcon.svelte";
</script>

<header class="flex flex-row justify-between items-center px-4 bg-mantle h-9">
  <LogoIcon class="w-5 fill-flamingo" />
  <CommandPalette />
  <div class="flex flex-row gap-6">
    <button class="stroke-surface2 hover:stroke-lavender">
      <MoreIcon class="w-4" />
    </button>
    <button class="stroke-surface2 hover:stroke-green">
      <MinimizeIcon class="w-4" />
    </button>
    <button class="stroke-surface2 hover:stroke-yellow">
      <MaximizeIcon class="w-4" />
    </button>
    <button class="stroke-surface2 hover:stroke-red">
      <CloseIcon class="w-4" />
    </button>
  </div>
</header>
