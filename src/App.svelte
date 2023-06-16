<script lang="ts">
import svelteLogo from "./assets/svelte.svg";
import TailwindCSS from "./TailwindCSS.svelte";
</script>

<TailwindCSS />
<main>
  <div class="flex h-screen flex-col items-center justify-center gap-4">
    <div
      class="animate-bounce rounded-3xl border-2 border-amber-500 p-10 drop-shadow-lg"
    >
      <img src="{svelteLogo}" alt="" class="h-56 animate-pulse" />
    </div>
    <div class="flex items-center justify-center gap-4">
      <div class="h-8 w-8 animate-pulse rounded-full bg-yellow-400"></div>
      <div class="h-8 w-8 animate-pulse rounded-full bg-yellow-500"></div>
      <div class="h-8 w-8 animate-pulse rounded-full bg-yellow-600"></div>
    </div>
  </div>
</main>
