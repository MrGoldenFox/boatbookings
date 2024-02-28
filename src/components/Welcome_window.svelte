<script>
    import { base } from '$app/paths';

</script>

<section style:background-image = "url('{base}/img/background.svg')">
    <a href="{base}/about"><img src="{base}/img/Logo.svg" alt=""></a>
</section>

<style>
    section{
        overflow: hidden;
        padding: 0px 10px 0px 10px;
        min-width: 100%;
        height: 100vh;
        background-size:cover;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    img {
        max-width: calc(100% - 1px);
    }
    section a {
        padding-inline: 35px;
    }
</style>