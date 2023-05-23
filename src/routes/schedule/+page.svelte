<script>
    const days = ["Måndag", "Tisdag", "Onsdag", "Torsdag", "Fredag", "Lördag", "Söndag"];
</script>

<h2>Schema</h2> //TODO: Lägg till datum och dag


<section>
    {#each days as day}
        <a href="/schedule/dayschedule">
            <article>{ day }</article>
        </a>
    {/each}
</section>
