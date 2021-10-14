<template>
	<v-app>
		<router-view :key="$route.fullPath"></router-view>

		<!-- <img v-show="$root.loader.value" src="loader.svg" class="loader" /> -->
	</v-app>
</template>

<script>
export default {

}
</script>

<style>

</style>