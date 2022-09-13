<script>
    import Titlebar from '$lib/Titlebar.svelte'
</script>

<Titlebar />
<body>
<div class="about">
<h1>About me</h1>
<p style="
font-size:16px;
padding:15px;
margin:0px;">Welcome to my website! I'm an aspiring software engineer set to graduate with a degree in computer science in the spring of 2023.</p>
</div>
</body>

<style>
    body {
        margin: 0;
        padding: 0;
        text-align: center;
    }

    .about {
        background:linear-gradient(rgba(110, 211, 144, 1), rgba(182, 218, 194, 1 ));
        display: block;
        margin: 0px;
    }
</style>