<script>
	import Nav from '../components/Nav.svelte';
	import SearchMovie from '../components/SearchMovie.svelte';
</script>

<svelte>
	<title>Movie DB</title>
</svelte>
<div class="navbar">
	<Nav />
	<SearchMovie />
</div>

<slot />

<style>
    *{
        margin: 0;
        box-sizing: border-box;
    }
    .navbar{
        margin-top: -1rem;
        padding-left: 3rem;
        padding-right: 3rem;
        position: fixed;
        display: flex;
        align-items: center;
        height: 4rem;
        background: white;
        opacity: 0.9;
        width: 100vw;
    }

</style>

