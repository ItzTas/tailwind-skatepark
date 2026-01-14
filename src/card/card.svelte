<script>
  const { title = 'Card Title', description = '' } = $props();
</script>

<div class="rounded-md border border-slate-300 bg-slate-50 p-4">
  <h2 class="text-center text-lg font-semibold">{title}</h2>
  <p class="mt-1 text-center">{description}</p>
</div>
