<script>
    import Titlebar from '$lib/Titlebar.svelte'
</script>

<Titlebar />

<div class = "index">
    <h1>Home</h1>
    <p>Aspiring Software Engineer</p>
    <a href="/about">About me</a>
</div>

<style>
    .index {
        text-align: center;
        display: block;
        margin: 20px auto;
    }
    :global(body) {
        background-image: url(/bg.jpg);
    }
</style>