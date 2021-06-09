<template>
	<div class="max-w-xl px-0 sm:px-12 lg:px-32">
		<p class="font-sans text-xs text-gray-600 uppercase tracking-wide mb-1 sm:mb-3">Oops</p>
		<h1 class="text-2xl md:text-4xl leading-tight lg:leading-normal mb-5 sm:mb-8 font-serif">Are you lost?</h1>

		<div class="mx-0 sm:ml-12 sm:-mr-12">
			<p class="pr-6 md:pr-0 text-xs leading-normal text-gray-900 mb-8">I couldn't find the page you're looking for.</p>
		</div>
	</div>
</template>

<script>
export default {
	middleware: [
		function ({ redirect }) {
			return redirect(301, '/')
		},
	],
}
</script>
