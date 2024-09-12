<script>
    import Theme from "./Theme.svelte"
    import FirstTheme from "./FirstTheme.svelte"
    import SecondTheme from "./SecondTheme.svelte"

    //@ts-ignore
    function scrollToTarget(event) {
        event.preventDefault();
        const link = event.currentTarget;
        const anchorId = new URL(link.href).hash.replace('#', '')
        const anchor = document.getElementById(anchorId);
        const navbarHeight = document.querySelector('.navbar')?.offsetHeight || 0;
        console.log(anchor.offsetTop - navbarHeight);
        window.scrollTo({
            top: anchor.offsetTop - navbarHeight,
            behavior: 'smooth'
        })
    }
</script>

<div class="min-h-full">
    <nav class="navbar sticky top-0 bg-white z-[1100] flex justify-center">
        <div class="hidden sm:flex sm:grow">
            <a href="https://ieee-itsc.org/2024"
               class="btn btn-ghost text-xl">IEEE ITSC 2024</a>
        </div>
        <div>
            <a href="#small-scale" on:click={scrollToTarget}
               class="btn btn-ghost text-xl">Small-Scale CAVs</a>
        </div>
        <div class="divider divider-horizontal"/>
        <div>
            <a href="#smart-mobility" on:click={scrollToTarget}
               class="btn btn-ghost text-xl">Smart Mobility</a>
        </div>
    </nav>
    
    <Theme 
        id="small-scale"
        title="Small-Scale Testbeds for Connected and Automated Vehicles in Research and Education"
        subtitle="at IEEE ITSC 2024">
            <FirstTheme/>
    </Theme>

    <Theme
        id="smart-mobility"
        title="Smart Mobility: AI and Intelligent Decision-Making for Future Transportation Systems"
        subtitle="at IEEE ITSC 2024">
            <SecondTheme/>
    </Theme>

</div>
  