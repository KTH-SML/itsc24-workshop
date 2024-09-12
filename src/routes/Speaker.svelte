<script>
    export let name;
    export let affiliation;
    export let title;
    export let abstract = "";
</script>

<div>
    <p class="text-base pb-2">{title}</p>
    <p><b>{name}</b> ({affiliation})</p>
    {#if abstract.length > 0}
    <p class="mt-2">{abstract}</p>
    {/if}
</div>
