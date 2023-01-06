<script>
    import {page} from '$app/stores'
</script>
<div>
    {#if $page.status === 404}
        <div>
            <h1 class="glitch" style="transform: translate(120%, -50%);">
                <span aria-hidden="true">404</span>
                404
                <span aria-hidden="true">404</span>
            </h1>
            <p class="glitch" style="transform: translate(-20%, 90%); animation-delay: -4s;">
                <span aria-hidden="true">Page Not Found</span>
                Page Not Found
                <span aria-hidden="true">Page Not Found</span>
            </p>
        </div>
        <a href="/" class="backbutton">Take me Back!</a>
    {/if}
</div>
<style>
    div{
        display: flex;
        width: 100%;
        height: 100%;
        font-size: 5vw;
        margin: auto;
        align-items:center;
        justify-content:center;
    }
</style>