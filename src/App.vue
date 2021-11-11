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
@import "./assets/scss/common.scss";
@import "./assets/scss/variables.scss";
</style>
