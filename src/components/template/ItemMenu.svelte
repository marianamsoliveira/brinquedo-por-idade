<script>
    export let itemMenu;
    export let href;
</script>

<a
    {href}
    class="relative font-medium text-blue-600 no-underline 
           transition-colors duration-300 ease-in-out
           after:content-['']
           after:absolute after:left-0 after:-bottom-1
           after:h-0.5 after:w-0
           after:bg-blue-400 
           after:trasition-all after:duration-300 after:ease-in-out
           hover:text-blue-400 hover:after:w-full
          "
>
    {itemMenu}
</a>
