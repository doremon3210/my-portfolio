<script>
	const hobbies = ['Ping Pong', 'Cycling', 'Fishing', 'Video Games', 'Board Games'];
</script>

<section class="mx-auto max-w-2xl px-6 py-24">
	<p class="mb-2 text-sm font-medium tracking-wide text-blue-500 uppercase">What I do for fun</p>

	<h2 class="mb-6 text-3xl font-bold text-gray-900">Hobbies</h2>

	<div class="flex flex-wrap gap-4">
		{#each hobbies as hobby}
			<span class="rounded-full bg-gray-100 px-4 py-2 text-sm text-gray-700">{hobby}</span>
		{/each}
	</div>
</section>
