<script>
    import Textbox from './../../components/Textbox.svelte'
    import Button from './../../components/Button.svelte';
    import SubmitButton from './../../components/SubmitButton.svelte';
</script>

<Textbox descriptionText="Användarnamn"/>
<Textbox descriptionText="Lösenord"/>

<SubmitButton/>

<a href="/login/newaccount">
    <Button buttonText="Skapa ett nytt konto"/>
</a>
