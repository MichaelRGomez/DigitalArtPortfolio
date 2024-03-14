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
        "
        >Personal Art</h1>
    
    <nav class="
    flex
    space-x-4
    text-white 
    px-4 py-2
    ">
        <a class="hover:text-black">Home</a>
        <a class="hover:text-black">Full Arhive</a>
        <a class="hover:text-black">Artists I like</a>
        <a class="hover:text-black">About me</a>
    </nav>
</div>


<slot />