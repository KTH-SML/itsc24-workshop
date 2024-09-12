<script>
    export let title;
</script>

<div class="pb-2">
    <div class="border-b border-gray-200 pb-3">
        <h2 class="text-base font-semibold leading-6 text-2xl text-gray-900">{title}</h2>
    </div>
    <div class="py-6 px-2 text-black">
        <slot/>
    </div>
</div>