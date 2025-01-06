<script>
    import CtAs from "./CTAs.svelte";
    import Header from "./Header.svelte";
    import SectionWrapper from "./SectionWrapper.svelte";
    import Stars from "./Stars.svelte";

</script>
<SectionWrapper id="hero">
    <Header/>
    <div class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14">
        <h2 class="text-5xl sm:text-6xl md:text-7xl Lg:text-8xl max-w-[1200px] mx-auto w-full text-center font-semibold">
            <span class="text-blue-400">Gym</span>
            Training 
            <span class="text-slate-600 line-through">Is Hard</span><br/>
            Just Got <span class="text-blue-400"> Easier</span>
        </h2>
        <p class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px0 mx-auto w-full">
            Tired of having absolutely <em>no muscle</em> to speak of? <br/>
            Tired of everybody overcomplicating whats supposed to be <em>simple?</em><br/>
            Reach a 225 Bench, 315 Squat, and 405 Deadlift in <em>less than a year.</em><br/>
        </p>
        <CtAs dark={false}/>
        <Stars/>
    </div>
</SectionWrapper>