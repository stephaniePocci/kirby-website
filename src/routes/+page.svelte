<script>
    import Header from '/src/components/Header.svelte';
    import Footer from '/src/components/Footer.svelte';
</script>

<body>
    <Header />
    <main>
        <p> test </p>
    </main>
    <Footer />
</body>

<style>
    body{
        background: linear-gradient(180deg, #fff261,#f780ff);;
    }
    main {
        max-width: 2em;
        margin: 1em auto;
    }
</style>
