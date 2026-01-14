<script>
  const { label = 'Button', ...props } = $props();
</script>

<button
  {...props}
  class="rounded-md border-black bg-red-600 px-4 py-1.5 text-white shadow-md hover:bg-red-400"
>
  {label}
</button>
