<script lang="ts">
	export let btnI: HTMLInputElement | undefined = undefined
	export let btnK: HTMLInputElement | undefined = undefined
</script>

<div class="flex flex-row gap-4 align-middle">
	<input
		bind:this={btnK}
		aria-label="Hledat Googlem"
		class="rounded border border-transparent bg-zinc-100 py-2 px-4 dark:bg-zinc-700 hover:dark:border-zinc-500"
		name="btnK"
		tabindex="0"
		type="submit"
		value="Hledat Googlem"
	/>

	<input
		bind:this={btnI}
		aria-label="Zkusím štěstí"
		class="rounded border border-transparent bg-zinc-100 py-2 px-4 dark:bg-zinc-700 hover:dark:border-zinc-500"
		name="btnI"
		type="submit"
		value="Zkusím štěstí"
	/>
</div>
