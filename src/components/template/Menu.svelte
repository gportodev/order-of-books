<script>
    let { titulo = "Menu" } = $props();
</script>

<div class="flex flex-col gap-3">
    <span class="text-sm font-bold text-zinc-500">{titulo}</span>
    <ul class="flex flex-col">
        <slot><!-- optional fallback --></slot>
    </ul>
</div>