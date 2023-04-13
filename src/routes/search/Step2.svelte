<script lang="ts">
	export let button: HTMLInputElement

	let className: string | undefined = undefined
	export { className as class }
</script>

<div class={className}>
	<h1 class="text-xl font-semibold">2. krok</h1>
	<p>Klikni na <em>{button.value}</em> tlačítko</p>
</div>
