<script context="module">
    export async function preload(page) {
        console.log(page);
        let  {id} = page.params;
        return {id};        
    }
</script>
<script>
	import TitlePage from '../../../components/TitlePage.svelte';
</script>
<TitlePage titulo="Planeta Modelos"/>