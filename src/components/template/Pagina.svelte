<script>
    import Cabecalho from "./Cabecalho.svelte";
    import Rodape from "./Rodape.svelte";
</script>

<div
    class="flex flex-col py-8 
    bg-linear-to-b from-blue-50 via-blue-100 to-white 
    "
>
    <div
        class="flex flex-col 
               max-w-6xl mx-auto w-full min-h-[90vh]
               border border-[#e5e7eb] shadow-[0_2px_4px_rgba(0,0,0,0.04)] rounded-2xl
               bg-zinc-100              

"
    >
        <Cabecalho />
        <main class="flex-1">
            <slot></slot>
        </main>
        <Rodape />
    </div>

</div>
