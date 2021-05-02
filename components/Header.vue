<template>
	<header class="static sm:fixed z-40 w-full h-24 px-6 sm:px-12 flex justify-between items-center">
		<div class="w-full lg:w-auto">
			<NuxtLink to="/" class="font-serif block text-black no-underline hover:text-gray-600">
				<span v-if="$nuxt.$route.name == 'tr'" class="text-2xl">Bilal TAŞ</span>
				<span v-else class="text-2xl">Bilal TAS</span> <br />
				<small v-if="$nuxt.$route.name == 'tr'" class="relative top-0 sm:-top-1 text-gray-500 block leading-4">Wordpress Geliştiricisi, <span class="hidden sm:inline">Vue Sever,</span> <span class="inline-block">Takım Lideri</span></small>
				<small v-else class="relative top-0 sm:-top-1 text-gray-500 block leading-4">Wordpress Developer, <span class="hidden sm:inline">Vue Lover,</span> <span class="inline-block">Team Leader</span></small>
			</NuxtLink>
		</div>

		<div class="grid grid-flow-col gap-2 justify-center text-sm lg:justify-end text-gray-600 language">
			<NuxtLink to="/" class="hover:text-black">EN</NuxtLink> |
			<NuxtLink to="/tr" class="hover:text-black">TR</NuxtLink>
		</div>
	</header>
</template>

<style lang="postcss">
.language {
	a.nuxt-link-exact-active {
		@apply font-bold;
	}
}
</style>
