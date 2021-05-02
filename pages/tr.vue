<template>
	<main class="lg:h-screen -mt-24 lg:pt-24 w-full flex flex-wrap">
		<div class="h-screen w-full lg:h-full lg:w-1/2 flex justify-center items-center">
			<div class="max-w-xl px-12 lg:px-32">
				<p class="font-sans text-xs text-gray-600 uppercase tracking-wide mb-3">Şuanda</p>

				<h1 class="text-2xl md:text-4xl leading-normal mb-8 font-serif"><span class="inline-block" style="color: #6ce1ae">Invicti Security</span>'de Websites Ekibi Yöneticisi</h1>

				<div class="ml-12 -mr-12">
					<p class="pr-6 md:pr-0 text-xs leading-normal text-gray-900 mb-8">Merhabalar, Ben Bilâl, frontend ağırlıklı uzman full-stack web geliştiricisiyim. Son derece estetik ve kullanışlı web siteleri/uygulamaları geliştiriyorum. Programlamaya 2006'da başladım. 12 yıldır web geliştirme alanıyla ilgileniyorum ve bunun 3 yılı yurtdışında olmak üzere yaklaşık son 10 yılını profesyonel olarak çalışarak geçirdim. Çorum'da yaşıyorum, 6 yıldır da uzaktan çalışmaktayım.</p>

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
export default {
	head: {
		title: 'Bilal TAŞ | Wordpress Geliştiricisi, Vue Sever, Takım Lideri',
		htmlAttrs: {
			lang: 'tr',
		},
		meta: [{ charset: 'utf-8' }, { name: 'viewport', content: 'width=device-width, initial-scale=1' }, { hid: 'description', name: 'description', content: 'Kişisel internet sitem.' }],
	},
}
</script>
