<script>
	const links = [
		{ label: 'GitHub', href: 'https://github.com/doremon3210' },
		{ label: 'LinkedIn', href: 'https://linkedin.com/in/huy-hue' },
		{ label: 'Email', href: 'mailto:huy.nguyen1478953@gmail.com' }
	];
</script>

<section class="mx-auto flex min-h-screen max-w-2xl flex-col justify-center px-6">
	<p class="mb-2 text-sm font-medium tracking-wide text-blue-500 uppercase">Hello, I'm</p>

	<h1 class="mb-4 text-5xl font-bold text-gray-900">Huy Nguyen</h1>

	<p class="mb-8 text-xl leading-relaxed text-gray-500">
		I automate the boring stuff, clean the messy stuff, and turn data into something people can
		actually use.
	</p>

	<div class="flex gap-4">
		{#each links as link}
			<a
				href={link.href}
				target="_blank"
				rel="noopener noreferrer"
				class="rounded-md border border-gray-300 px-4 py-2 text-sm font-medium text-gray-700 transition-colors hover:border-blue-500 hover:text-blue-500"
			>
				{link.label}
			</a>
		{/each}
	</div>
</section>
