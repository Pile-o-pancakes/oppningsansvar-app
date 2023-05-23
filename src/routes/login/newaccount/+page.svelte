<script>
    import Textbox from './../../../components/Textbox.svelte';
    import SubmitButton from './../../../components/SubmitButton.svelte';
</script>

<h2>Skapa nytt konto</h2>

<Textbox descriptionText="Förnamn"/>
<Textbox descriptionText="Efternamn"/>
<Textbox descriptionText="E-post adress"/>
<Textbox descriptionText="Bekräfta E-post adress"/>
<Textbox descriptionText="Telefonnummer"/>

<SubmitButton/>