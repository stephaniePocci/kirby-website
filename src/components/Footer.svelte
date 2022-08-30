<script>
    import Github from './social_media/github.svelte';
    import LinkedIn from './social_media/linkedin.svelte';
</script>

<LinkedIn />
<Github />

<footer>
    <div class = 'copyright'> Copyright 2022 Nintendo </div> 
</footer>

<style>
    footer {
        background: #FFCBCF;
        padding: 1em;
        text-align: right;
    }

    .copyright {
        color: rgb(58, 55, 55);
        font-size: 1em;
        display: inline-block;
        padding: 1em;
        border-top: 1px solid rgb(58, 55, 55);
    }
</style>