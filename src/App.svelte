<script>
	import Greeting from './Gretting.svelte';
	import EventDemo from './EventDemo.svelte';
	import BindDemo from './BindDemo.svelte';

	let inputValue = '';
</script>

<Greeting name={"Batata"} />

<EventDemo />

<hr />

<BindDemo value={inputValue} />

<p>Value: {inputValue}</p>