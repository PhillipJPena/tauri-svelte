<script lang="ts">
  import Button from "$lib/components/ui/button/button.svelte";
  import Input from "$lib/components/ui/input/input.svelte";
</script>

<main class="grid place-content-center h-full w-full bg-gray-200 gap-4">
  <h1 class=" font-bold text-2xl">Hello World!</h1>
  <div class="flex gap-4">
    <Input placeholder="What is your name?" class="max-w-xs" />
    <Button variant="outline" class=" w-20">Submit</Button>
  </div>
</main>
