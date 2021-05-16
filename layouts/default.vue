<template>
	<div id="page">
		<Header />

		<main class="h-auto sm:h-screen px-6 sm:px-0 pt-5 sm:pt-24 pb-6 sm:pb-0 w-full block sm:grid sm:grid-cols-2">
			<div class="h-full w-full block sm:flex justify-center items-center">
				<Nuxt />
			</div>

			<figure class="h-60 sm:h-full w-full bg-cover bg-no-repeat bg-center" style="background-image: url('/bilal-tas1.jpg')"></figure>
		</main>

		<Footer />
	</div>
</template>

<style lang="postcss">
html {
	letter-spacing: 0.5px;
	-ms-text-size-adjust: 100%;
	-webkit-text-size-adjust: 100%;
	-moz-osx-font-smoothing: grayscale;
	-webkit-font-smoothing: antialiased;
	box-sizing: border-box;
}
</style>
