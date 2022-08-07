<script>
    import Titlebar from '$lib/Titlebar.svelte'
</script>

<Titlebar />

<body>
<div class = "index">
    <h1>Home</h1>
    <p>Aspiring Software Engineer</p>
</div>
</body>

<style>
    
    body {
        height: 935px;
        background:linear-gradient(rgba(0, 0, 0, 0.35), rgba(0, 0, 0, 0.35)), url(/bg.jpg);
    }
    .index {
        color: white;
        justify-content: center;
        text-align: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }


</style>