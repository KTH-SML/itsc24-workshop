<script>
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
    export let home;
    export let sections;
</script>

<nav class="navbar sticky top-0 bg-white z-[1100] flex justify-center">
    <div class="hidden sm:flex sm:grow">
        <a href="{home.href}"
           class="btn btn-ghost text-xl">{home.name}</a>
    </div>
    {#each sections as section, i}
    <div>
        <a href="{section.href}" on:click={scrollToTarget}
           class="btn btn-ghost text-xl">{section.name}</a>
    </div>
    {#if i+1 < sections.length}
    <div class="divider divider-horizontal"/>
    {/if}
    {/each}
</nav>