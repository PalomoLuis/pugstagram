<script>
  import { loop_guard } from "svelte/internal";


    import Card from './Card.svelte';

    export let posts = [];
    
</script>

<div class="timeline">
    <div class="timeline-container">
        {#each posts as post}
            <Card {...post}/>
        {:else}
            <p>Loading...</p>
        {/each}
    </div>
</div>

<style>
    .timeline {
      padding: 4em 0 0 0;
    }
</style>