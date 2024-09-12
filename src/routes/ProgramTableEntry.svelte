<script>
    export let time;
    export let vertical = true;
</script>


<tr>
    <div class={vertical ? "flex flex-col sm:table-row py-2" : ""}>
        <td class="align-top whitespace-nowrap">{time}</td>
        <td><slot/></td>
    </div>
</tr>