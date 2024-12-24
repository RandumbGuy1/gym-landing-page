<script>
    import Icon from "$lib/assets/Logos.png"
</script>

<header class="flex flex-col relative z-20">
    <div class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6">
        <a href="/">
            <!--<h1 class="font-semibold">Randumb <span class="text-blue-400">Fitness</span></h1>-->
            <img src={Icon} alt="Randumb Fitness" width="300px" height="300px">
        </a>
        <!-- svelte-ignore a11y_consider_explicit_label -->
        <button class="md:hidden grid place-items-center">
            <i class="fa-solid fa-bars"></i>
        </button>
        <nav class="hidden md:flex items-center gap-4">
            <a href="#product" class="duration-200 hover:text-indigo-400 curser-pointer">Product</a>
            <a href="#reviews" class="duration-200 hover:text-indigo-400 curser-pointer">Reviews</a>
            <a href="#faqs" class="duration-200 hover:text-indigo-400 curser-pointer">FAQs</a>
            <button class="specialBtn">
                <p>Start Free Today</p>
            </button>
        </nav>
    </div>
</header>