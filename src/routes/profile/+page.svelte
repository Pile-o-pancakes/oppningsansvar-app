<script>
    import Button from './../../components/Button.svelte';
    import SubmitButton from './../../components/Button.svelte';
</script>

<h2>Din profil</h2>

<label for="contact">Föredragen kontaktmetod</label>
<SubmitButton/>
<select id="contact">
    <option value="e-mail">E-post</option>
    <option value="discord">Discord</option>
    <option value="messenger">Messenger</option>
    <option value="sms">SMS</option>
</select>

<p>Tel. nummer:</p>
<!-- <p>TODO: Lägg till telefon nummer</p> -->
<p>E-post adress:</p>
<!-- <p>TODO: Lägg till censurerad E-post adress</p> -->
<Button buttonText="Redigera profil info"/>
