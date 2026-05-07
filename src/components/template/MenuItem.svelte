<script>
    let { texto = "", href = "/" } = $props();
</script>

<li>
    <a href={href} class="
        flex gap-2 items-center flex-row cursor-pointer px-4 py-2
        text-zinc-300 hover:underline hover:text-white
        hover:bg-white/10
    "
    >
        <slot></slot>
        
        <span>{texto}</span>
    </a>
</li>