<script>
	import Header from '../components/Header.svelte';

	function test() {
		return 'Hey';
	}
</script>

<Header />
<h1>Welcome to Homepage.</h1>
{test()}
