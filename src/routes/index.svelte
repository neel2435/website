<script>
    import Titlebar from '$lib/Titlebar.svelte'
</script>

<Titlebar />

<body>
<div class = "index">
    <div class = "typewriterH">
        <h1>Hey, I'm Neel</h1>
    </div>  
    <div class = "typewriterP">
        <p>University of California, Riverside</p>
    </div>
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
        place-items: center;
        top: 45%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    
    .typewriterH {
        animation: typing 2s steps(22), blink .5s step-end infinite alternate;
        white-space: nowrap;
        overflow: hidden;
        border-right: 3px solid;
        font-family: monospace;
        font-size: 2em;
        border-style: solid;
        border-color: red;
    }

    .typewriterP{
        animation: typing 2s steps(22), blink .5s step-end infinite alternate;
        white-space: nowrap;
        overflow: hidden;
        border-right: 3px solid;
        font-family: monospace;
        font-size: 2em;
        border-style: solid;
        border-color: red;
    }

    @keyframes typing {
        from { width: 0 }
        to { width: 100% }
    }
            
    @keyframes blink {
        50% {
            border-color: transparent
        }
    }

</style>