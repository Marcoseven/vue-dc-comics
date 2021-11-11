<template>
	<div id="app">
		<SiteHeader />
		<!-- /#SiteHeader -->

		<SiteMain />
		<!-- /#SiteMain -->

		<SiteFooter />
		<!-- /#SiteFooter -->
	</div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";
import SiteFooter from "./components/SiteFooter.vue";

export default {
	name: "App",
	components: {
		SiteHeader,
		SiteMain,
		SiteFooter,
	},
};
</script>

<style lang="scss">
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
