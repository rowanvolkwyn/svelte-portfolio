<script>

</script>

<style>
    * {
        font-family: sans-serif;
        color: white;
    }

    h4 {
        font-weight: bold;
        font-size: 2rem;
    }

    h4:hover {
        color: yellow;
        transition: color 0.5s ease-in-out;
    }

    .nav-background {
        z-index: 40;
        background-color: #010026;
        padding: 0px;
        width: 100%;
        display: flex;
        justify-content: space-between;
        position: fixed;
        top: 0px;
    }


    .nav-container {
        display: flex;
        justify-content: space-between;
        width: 80%;
        margin: 0 auto;
    }

    .link-container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 4rem;
    }

    .link {
        font-size: 1rem;
    }

    .link:hover {
        color: yellow;
        transition: color 0.5s ease-in-out;
    }
</style>

<nav class="nav-background">
    <div class="nav-container">
        <h4 class="rv-logo">RV</h4>
        <div class="link-container">
            <p class="link">Home</p>
            <p class="link">Skills</p>
            <p class="link">Projects</p>
            <p class="link">Contact</p>
        </div>
    </div>
</nav>