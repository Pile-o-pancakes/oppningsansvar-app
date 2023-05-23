<script>
    import Button from '../components/Button.svelte';
    export let adminRights = true;//TODO: Ändra till false och lägg till en tokencheck
    
</script>

<a href="/login">
    <Button buttonText={"Logga in"}/>
</a>

<a href="/schedule">
    <Button buttonText={"Öppningsschema"}/>
</a>

{ #if (adminRights) }
    <a href="/admin">
        <Button buttonText={"Administratör"}/>
    </a>
{ /if }

<style>

</style>