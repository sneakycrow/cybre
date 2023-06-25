<script>
  import BarLink from "../components/BarLink.svelte";
</script>

<main class="w-screen h-screen flex flex-col items-center justify-center space-y-6">
  <header class="w-full md:w-1/2 space-y-2">
    <h1 class="text-4xl font-bold text-gray-800">cybre.gg</h1>
    <blockquote class="text-sm text-gray-400 italic">
      a community of friends who playing video games. This
      website acts as a "home base" of tools we utilize, including
      custom ladder boards, stat trackers, and more
    </blockquote>
  </header>
  <article class="w-full md:w-1/2">
    <h2 class="text-2xl font-bold text-gray-800">Coming Soon</h2>
    <BarLink href="/ladders">
      Ladders
    </BarLink>
  </article>
</main>