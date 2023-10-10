<script lang="ts">
	export const ssr = false;
	export const prerender = true;

	import { onMount } from 'svelte';

	onMount(() => {
		import EasyMDE from 'easymde';
		const mdparser = new EasyMDE();
	});
</script>

<div>
	<textarea name="" id="textarea" cols="30" rows="10" />
</div>
