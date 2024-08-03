<template>
	<nav>
		<NuxtLink to="/home">Home</NuxtLink>
		<NuxtLink to="/experience">Experience</NuxtLink>
		<NuxtLink to="/education">Education</NuxtLink>
		<NuxtLink to="/projects">Projects</NuxtLink>
		<NuxtLink to="/contact">Contact</NuxtLink>
		<NuxtLink to="/about-me">About me</NuxtLink>
		<NuxtLink external target="_blank" to="https://resume.krane.dev/">Resume</NuxtLink>
	</nav>
</template>
<script>
export default {
	name: 'NavHeader'
}
</script>