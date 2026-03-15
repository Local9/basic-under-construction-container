<script lang="ts">
  import {
    Construction,
    HardHat,
    Wrench,
    Hammer,
    Ruler
  } from 'lucide-svelte';
</script>

<div
  class="min-h-dvh min-w-full flex flex-col items-center justify-center gap-8 bg-gradient-to-br from-amber-50 via-orange-50 to-yellow-100 text-stone-900 dark:from-stone-900 dark:via-stone-800 dark:to-amber-950 dark:text-stone-100"
>
  <div
    class="flex flex-wrap items-center justify-center gap-4 text-amber-600/80 dark:text-amber-400/80"
    aria-hidden="true"
  >
    <HardHat class="size-10 sm:size-12 animate-pulse" strokeWidth={1.5} />
    <Wrench class="size-9 sm:size-11 animate-pulse [animation-delay:0.1s]" strokeWidth={1.5} />
    <Construction class="size-12 sm:size-14 animate-pulse [animation-delay:0.2s]" strokeWidth={1.5} />
    <Hammer class="size-9 sm:size-11 animate-pulse [animation-delay:0.3s]" strokeWidth={1.5} />
    <Ruler class="size-10 sm:size-12 animate-pulse [animation-delay:0.4s]" strokeWidth={1.5} />
  </div>

  <h1
    class="text-4xl sm:text-5xl md:text-6xl font-bold tracking-tight text-stone-800 drop-shadow-sm dark:text-stone-100 dark:drop-shadow-md"
  >
    Under Construction
  </h1>

  <p class="text-stone-600 text-lg sm:text-xl max-w-sm text-center dark:text-stone-400">
    We're working on something great. Check back soon.
  </p>

  <div
    class="flex flex-wrap items-center justify-center gap-3 text-amber-600/70 mt-2 dark:text-amber-400/70"
    aria-hidden="true"
  >
    <Construction class="size-6 opacity-60" strokeWidth={2} />
    <Wrench class="size-5 opacity-50" strokeWidth={2} />
    <Hammer class="size-6 opacity-60" strokeWidth={2} />
  </div>
</div>
