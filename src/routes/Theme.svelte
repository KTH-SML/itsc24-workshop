<script>
    export let id;
    export let title;
    export let subtitle;
</script>

<main id="{id}">
    <div class="bg-sky-700 pb-32">
        <header class="py-10">
            <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                <h1 class="text-3xl font-bold tracking-tight text-white">{title}</h1>
                <h2 class="text-xl font-bold tracking-tight text-white">{subtitle}</h2>
            </div>
        </header>
    </div>
  
    <div class="-mt-32">
        <div class="mx-auto max-w-7xl px-4 pb-12 sm:px-6 lg:px-8">
            <slot/>
        </div>
    </div>
</main>