<script>
    import Titlebar from '$lib/Titlebar.svelte'
</script>

<Titlebar />

<body>
    <div class = "typewriterH">
       Hey, I'm Neel
    </div>  
    <div class = "typewriterP">
        University of California, Riverside
    </div>
</body>

<style>
    
    body {
        height: 935px;
        background:linear-gradient(rgba(0, 0, 0, 0.35), rgba(0, 0, 0, 0.35)), url(/bg.jpg);
    }

    .typewriterH {
        color: white;
        justify-content: center;
        text-align: center;
        position: absolute;
        place-items: center;
        top: 40%;
        left: 50%;
        transform: translate(-50%, -50%);
        animation: typing1 1s steps(22), blink .5s step-end infinite alternate;
        white-space: nowrap;
        overflow: hidden;
        border-right: 3px solid;
        font-family: monospace;
        font-size: 4em;
        padding: 0px;
    }

    .typewriterP{
        color: white;
        justify-content: center;
        text-align: center;
        position: absolute;
        place-items: center;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        animation: typing2 1s steps(22), blink .5s step-end infinite alternate;
        white-space: nowrap;
        overflow: hidden;
        border-right: 3px solid;
        font-family: monospace;
        font-size: 2em;
        padding: 0px;
        display: inline-block;
    }

    @keyframes typing1 {
        from { width: 0 }
        to { width: 20% }
    }
           
    @keyframes typing2 {
        from { width: 0 }
        to { width: 27% }
    }

    @keyframes blink {
        50% {
            border-color: transparent
        }
    }

</style>