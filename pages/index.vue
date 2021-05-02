<template>
	<main class="lg:h-screen -mt-24 lg:pt-24 w-full flex flex-wrap">
		<div class="h-screen w-full lg:h-full lg:w-1/2 flex justify-center items-center">
			<div class="max-w-xl px-12 lg:px-32">
				<p class="font-sans text-xs text-gray-600 uppercase tracking-wide mb-3">Currently</p>

				<h1 class="text-2xl md:text-4xl leading-normal mb-8 font-serif">Websites Team Manager at <span class="inline-block" style="color: #6ce1ae">Invicti Security</span></h1>

				<div class="ml-12 -mr-12">
					<p class="pr-6 md:pr-0 text-xs leading-normal text-gray-900 mb-8">Hello, I’m Bilal, senior front-end heavy full-stack web developer. I create pixel-perfect web sites/apps. Working in the field professionally for about 10 years now, started programming on 2006. Currently living and working remotely in Turkey.</p>

					<Social />
				</div>
			</div>
		</div>

		<div class="h-screen w-full lg:h-full lg:w-1/2 relative">
			<div class="w-full h-full bg-cover bg-no-repeat bg-center" style="background-image: url('/bilal-tas1.jpg')"></div>

			<div class="absolute pin-l pin-b py-6 px-4 bg-white flex justify-around w-32 hidden">
				<a href="#" class="text-xs text-gray-600er hover:text-gray-900 no-underline">&larr;</a>
				<span class="text-xs text-gray-600er">1/3</span>
				<a href="#" class="text-xs text-gray-600er hover:text-gray-900 no-underline">&rarr;</a>
			</div>
		</div>
	</main>
</template>

<script>
export default {}
</script>
