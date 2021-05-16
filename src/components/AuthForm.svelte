<script>
    export let auth;
    let mode = 'signIn';
    let email = '';
</script>

<h1 class='title has-text-info has-text-centered'>David's Svelte Chat App</h1>
<h2 class='title'> {mode === 'signIn' ? 'Sign In': 'Sign Up'}</h2>

<form>
    <div class="field">
        <label for="" class="label">Email</label>
        <input type="email" class="input" requiured bind:value={email} />
    </div>
</form>