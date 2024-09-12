<script>
    export let name;
    export let affiliation;
    export let title;
    export let abstract = "";
</script>

<div>
    <p><b>{name}</b> ({affiliation})</p>
    <p><i>{title}</i></p>
    {#if abstract.length > 0}
    <p class="mt-2">{abstract}</p>
    {/if}
</div>
