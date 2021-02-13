<template>
	<div id="app">
		<header>
			<nav-bar></nav-bar>
		</header>
		<main></main>
	</div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Main from './components/Main.vue';
import store from './vuex/store';

export default {
	store,

	components: {
		NavBar,
		Main,
	},
};
</script>

<style>
@import '~primer-css/build/build.css';
@import '~octicons/build/font/octicons.min.css';
</style>
