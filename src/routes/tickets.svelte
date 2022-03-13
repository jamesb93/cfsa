<script>
    import { goto } from '$app/navigation'
    import { onMount } from 'svelte';

    onMount(async() => {
        goto('https://wentworthwoodhouse.digitickets.co.uk/tickets')
    })
</script>