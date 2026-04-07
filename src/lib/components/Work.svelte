<script>
	const works = [
		{
			title: 'ETL Pipelines',
			description:
				'Moving data from ERP systems and user spreadsheets into a central PostgreSQL database, making it clean and ready for reporting.'
		},
		{
			title: 'Dashboards & Reports',
			description:
				'Building dashboards and reports in Streamlit, Power BI, and Crystal Report for teams and leadership to make sense of complex ERP data.'
		},
		{
			title: 'Workflow Automation',
			description:
				"Automating repetitive manual tasks for the team - if it involves data or Excel and it's done more than once, I find a way to script it."
		},
		{
			title: 'Custom Apps',
			description:
				'Building small focused tools when existing systems fall short - like a payroll export app or an external portal for viewing ERP data without extra licensing costs.'
		}
	];
</script>

<section class="mx-auto max-w-2xl px-6 py-24">
	<p class="mb-2 text-sm font-medium tracking-wide text-blue-500 uppercase">What I do</p>

	<h2 class="mb-6 text-3xl font-bold text-gray-900">My Work</h2>

	<div class="space-y-6">
		{#each works as work}
			<div class="rounded-lg border border-gray-200 p-6 transition-shadow hover:shadow-lg">
				<h3 class="mb-2 text-xl font-semibold text-gray-900">{work.title}</h3>
				<p class="text-gray-700">{work.description}</p>
			</div>
		{/each}
	</div>
</section>
