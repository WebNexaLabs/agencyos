<template>
	<div class="min-h-screen flex items-center justify-center">
		<div class="text-center">
			<h1 class="text-4xl font-bold mb-4">Welcome to Agency OS</h1>
			<p class="text-lg mb-8">Your content management system is loading...</p>
			<div class="space-x-4">
				<NuxtLink to="/auth/signin" class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700">
					Sign In
				</NuxtLink>
				<NuxtLink to="/portal" class="bg-gray-600 text-white px-6 py-2 rounded hover:bg-gray-700">
					Portal
				</NuxtLink>
			</div>
		</div>
	</div>
</template>

<script setup>
// This is a temporary homepage that will be used if no content is found in Directus
// You can remove this file once you've created a homepage in your Directus CMS
definePageMeta({
	layout: 'default'
});
</script>
