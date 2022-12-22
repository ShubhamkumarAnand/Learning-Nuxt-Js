<template>
	<div class="flex flex-col items-center w-full h-full min-h-screen p-12 bg-gray-100">
		<div class="mb-12 prose">
			<h1>
				<span class="font-medium"> Course: <span class="font-bold">Mastering Nuxt</span> </span>
			</h1>
		</div>
		<div class="flex flex-row justify-center flex-grow">
			<div class="flex flex-col p-8 mr-4 prose bg-white rounded-md min-w-[20ch]">
				<h3>Chapters</h3>
			</div>
			<div class="p-12 prose bg-green-100 rounded-md w-[65ch]">
				<NuxtPage />
			</div>
		</div>
	</div>
</template>
