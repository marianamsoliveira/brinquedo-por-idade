<script>
    import ItemMenu from "./ItemMenu.svelte";
    import Logo from "./Logo.svelte";

</script>
<header class="flex  items-center justify-between">
    <Logo/>
    <aside class="menu flex flex-1 justify-end items-end gap-10 px-5 ">
        <ItemMenu itemMenu="Início" href="/"/>    
        <ItemMenu itemMenu="Como Escolher?" href="/como-escolher"/>    
        <ItemMenu itemMenu="Sobre" href="/sobre"/>    

    </aside>
</header>