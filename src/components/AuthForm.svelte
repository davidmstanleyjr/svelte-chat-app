<script>
    export let auth;
    let mode = 'signIn'
</script>

<h1 class='title has-text-info has-text-centered'>David's Svelte Chat App</h1>
<h2 class='title'> {mode === 'signIn' ? 'Sign In': 'Sign Up'}</h2>