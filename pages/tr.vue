<template>
	<main class="h-auto sm:h-screen px-6 sm:px-0 pt-5 sm:pt-24 pb-6 sm:pb-0 w-full block sm:grid sm:grid-cols-2">
		<div class="h-full w-full block sm:flex justify-center items-center">
			<div class="max-w-xl px-0 sm:px-12 lg:px-32">
				<p class="font-sans text-xs text-gray-600 uppercase tracking-wide mb-1 sm:mb-3">Şuanda</p>
				<h1 class="text-2xl md:text-4xl leading-tight lg:leading-normal mb-5 sm:mb-8 font-serif"><span class="inline-block" style="color: #6ce1ae">Invicti Security</span>'de Websites Ekibi Yöneticisi</h1>

				<div class="mx-0 sm:ml-12 sm:-mr-12">
					<p class="pr-6 md:pr-0 text-xs leading-normal text-gray-900 mb-8">Merhabalar, Ben Bilâl, frontend ağırlıklı uzman full-stack web geliştiricisiyim. Son derece estetik ve kullanışlı web siteleri/uygulamaları geliştiriyorum. Programlamaya 2006'da başladım. 12 yıldır web geliştirme alanıyla ilgileniyorum ve bunun 3 yılı yurtdışında olmak üzere yaklaşık son 10 yılını profesyonel olarak çalışarak geçirdim. Çorum'da yaşıyorum, 6 yıldır da uzaktan çalışmaktayım.</p>
					<Social />
				</div>
			</div>
		</div>

		<figure class="h-60 sm:h-full w-full bg-cover bg-no-repeat bg-center" style="background-image: url('/bilal-tas1.jpg')"></figure>
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
