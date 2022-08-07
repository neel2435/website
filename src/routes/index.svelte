<script>
    import Titlebar from '$lib/Titlebar.svelte'
</script>

<Titlebar />

<body>
<div class = "index">
    <h1>Home</h1>
    <p>Aspiring Software Engineer</p>
    <a href="/about">About me</a>
</div>
</body>

<style>
    .index {
        height: 920px;
        text-align: center;
        color: white;
        background-image: url(/bg.jpg);
        top: 80px;
    }
    * {
        border: 1px solid red;
        margin: 0rem;
        padding: 0px;
    }

</style>