<script lang="ts">
  export let href: string;
  const handleOnClick = (event) => {
    event.preventDefault();
    // TODO: Simulate a click on the link using svelte navigation
  };
</script>

<a href={href}
   class="flex w-full border-4 border-black px-2 py-4 text-2xl font-bold bg-green-200 hover:bg-green-400 transition-colors">
  <slot>Link</slot>
</a>

