<template>
	<main>
		<NavHeader />
		<slot />
	</main>
</template>
<script setup lang="ts">
import NavHeader from "~/components/NavHeader.vue";
</script>