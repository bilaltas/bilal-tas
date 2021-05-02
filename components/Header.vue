<template>
	<header class="bg-white relative z-40 w-full h-24 px-12 flex justify-between items-center">
		<div class="w-full lg:w-auto">
			<NuxtLink to="/" class="font-serif block text-black no-underline hover:text-gray-600">
				<span class="text-2xl" v-if="$nuxt.$route.name == 'tr'">Bilal TAŞ</span>
				<span class="text-2xl" v-else>Bilal TAS</span> <br />
				<small class="relative -top-1 text-gray-500" v-if="$nuxt.$route.name == 'tr'">Wordpress Geliştiricisi, Vue Sever, Takım Lideri</small>
				<small class="relative -top-1 text-gray-500" v-else>Wordpress Developer, Vue Lover, Team Leader</small>
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
