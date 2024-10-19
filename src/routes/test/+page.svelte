<script>
	import Test from '../../components/Test.svelte';
	let inputBoxValue = '';
</script>

<Test onChange={(newValue) => (inputBoxValue = newValue)} />

<p>Input box value is: {inputBoxValue}</p>
