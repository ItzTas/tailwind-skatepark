<script>
  const { label = 'Button', ...props } = $props();
</script>

<button
  class="cursor-pointer rounded-md bg-white px-3 py-1.5 shadow-md outline outline-slate-600"
  {...props}
  >{label}
</button>

