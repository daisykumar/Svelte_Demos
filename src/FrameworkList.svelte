<script>
    let framworks = [
        {
            id: 1,
            name: 'Svelte'
        },
        {
            id: 2,
            name: 'Javascript'
        },
        {
            id: 3,
            name: 'HTML'
        },
        {
            id: 4,
            name: 'CSS'
        }
    ]
</script>

<main>
    <h1>List of Frameworks</h1>

    <ul>
        {#each framworks as {id, name}}
            <li>
                {id}: {name}
            </li>
        {/each}
    </ul>
</main>

<style>
    li{
        list-style: none;
    }
</style>