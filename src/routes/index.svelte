<script>
	import Inputs from './inputs.svelte';
	let bank = '/Visa.svg';
	let mail = '/mail.svg';
	let search = '/search.svg';
</script>

<Inputs leftIcon={bank} rightIcon={search} {mail} />
<Inputs leftIcon={bank} />
<Inputs rightIcon={search} />
<Inputs {mail} />

<style></style>
