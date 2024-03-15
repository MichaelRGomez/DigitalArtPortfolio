<script>
    import '../app.css'

</script>

<div class="
    lg:flex 
    lg:items-center 
    justify-between
    bg-red-500 
    text-white 
    px-4 py-2
    ">
    <h1 class="
        text-3xl 
        text-white 
        font-mono 
        font-bold
        hover:text-black
        px-4
        ">
        <a href="/">Personal Art</a>
    </h1>
    
    <nav class="
    flex
    space-x-4
    text-white 
    px-4 py-2
        ">
        <a class="hover:text-black" href="/">Home</a>
        <a class="hover:text-black" href="/FullArchive">Full Archive</a>
        <a class="hover:text-black" href="/Artists">Artists I like</a>
        <a class="hover:text-black" href="/About">About me</a>
        <a class="hover:text-black  underline" href="/Admin">Admin Powers</a>
    </nav>
</div>


<slot />