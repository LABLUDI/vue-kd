<template>
	<div class="app">
		<Header />
		<List />
	</div>
</template>

<script>
import Header from './components/Header.vue'
import List from './components/List.vue'

export default {
	components: {
		Header,
		List,
	}
}
</script>

<style lang="scss">
@import "./assets/layouts/normalize.module.scss";

*,
*::before,
*::after {
	box-sizing: border-box;
	padding: 0;
	margin: 0;
	background: #fff;
	list-style: none;
}

.container {
		max-width: 1280px;
		margin: 0 auto;
		background: #FFFFFF;
	}
</style>