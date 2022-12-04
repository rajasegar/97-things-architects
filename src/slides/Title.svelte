<script>
    import { onMount } from 'svelte';
 import Slide from '../lib/Slide.svelte';
 import Code from '../lib/Code.svelte';

    let title;
    onMount(() => {
        let timeout;
        title = new Promise(resolve => {
            timeout = setTimeout(() => resolve('Whats nice together?'), 1000);
        });
        () => clearTimeout(timeout);
    });
</script>

<Slide twclass="bg-indigo-100">
    <h2 class="text-indigo-500">Collective Wisdom for the Architects </h2>
</Slide>
