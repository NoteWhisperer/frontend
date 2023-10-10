<script lang="ts">
	import MarkdownArea from '../components/MarkdownArea.svelte';
</script>

<div>
	<div>
		<input
			type="text"
			class="input input-ghost w-full focus:outline-none placeholder-neutral text-neutral bg-base-100 text-[21.4px] opacity-50"
			placeholder="# Title goes here..."
		/>
		<!-- <textarea class="textarea-ghost w-full h-full bg-base-100 box-border" name="" id="" /> -->
		<MarkdownArea />
	</div>
</div>
