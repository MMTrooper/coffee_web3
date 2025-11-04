<script> 
    import Header from "./Header.svelte";
    import SectionWrapper from "./SectionWrapper.svelte";
    import CTA from "./CTA.svelte";
</script>

<SectionWrapper>
    <Header />
    <div class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14">
        <h2 class="text-5xl sm:test-6xl md:text-7xl lg:text-8xl max-w-[1200px] mx-auto w-full text-center font-semibold">
            <span class="text-green-900"> Discover </span> the Best <span class="text-green-300"> Unroasted </span> Coffee Beans
        </h2>
        <p class="text-center sm:text-2xl max-w-[1000px] mx-auto w-full text-xl md:text-3xl text-gray-700">
            Elevate your coffee experience with our premium selection of unroasted beans, sourced from the finest growers in Kenya. Perfect for home roasters and coffee enthusiasts seeking unparalleled freshness and flavor.
        </p>
        <CTA dark={false} />
        <div class="flex flex-col gap-4"> </div>
    </div>

</SectionWrapper>