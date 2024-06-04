<script>
    export let title = "Hero";
</script>
  
<div class="hero">
    <div class="hero-content">
        <h1>{title}</h1>
    </div>
</div>
  
<style>
    .hero {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        width: 100vw;
        background: rgb(132,109,98);
background: linear-gradient(90deg, rgba(132,109,98,1) 0%, rgba(195,195,195,1) 100%);
    }
  
    .hero-content {
        text-align: center;
    }
  
    h1 {
        font-size: 4rem;
    }
</style>