<script>
    import Button from './../components/Button.svelte';
</script>

<nav>
    <a href="/">
        <Button buttonText="Hem"/>
    </a>
    <a href="./profile">
        <Button buttonText="Min profil"/>
    </a>
</nav>

<slot/>