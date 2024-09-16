<script>
    export let name;
    export let affiliation;
    export let email = "";
    export let image;
</script>

<div class="flex items-center px-4">
    <div class="avatar">
        <div class="w-16 rounded">
            <img src="{image}" />
        </div>
    </div>
    <div class="ml-3">
        <p class="text-l font-medium text-gray-700 group-hover:text-gray-900">{name}</p>
        <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">{affiliation}</p>
        {#if email.length > 0}
        <p class="text-xs font-medium text-gray-500 group-hover:text-gray-700">{email}</p>
        {/if}
    </div>
</div>