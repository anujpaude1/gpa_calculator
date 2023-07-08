<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<script>

</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<h1 class="text-6xl font-bold">GPA Calculator</h1>

		<h1 class="text-2xl font-bold">Choose your grade</h1>
		<!-- two buttons to choose grades, 10 or 12 -->
		<div class="flex space-x-10">
			<a href="/10" data-sveltekit-preload-data="tap" class="btn variant-filled-primary hover:brightness-150">10</a>
			<a href="/12" data-sveltekit-preload-data="tap" class="btn variant-filled-primary hover:brightness-150">10+2</a>
		</div>
	</div>
</div>

<style lang="postcss">
	.btn {
		@apply w-32 h-16;
	}
</style>
