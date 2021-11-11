<template>
	<header id="SiteHeader">
		<div class="container">
			<div class="row d-flex">
				<div class="">
					<img src="../assets/img/dc-logo.png" alt="immagine logo dc" />
				</div>
				<div class="">
					<nav class="menu">
						<a href="#">CHACTERS</a>
						<a href="#">COMICS</a>
						<a href="#">MOVIES</a>
						<a href="#">TV</a>
						<a href="#">GAMES</a>
						<a href="#">COLLECTIBLES</a>
						<a href="#">VIDEOS</a>
						<a href="#">FANS</a>
						<a href="#">NEWS</a>
						<a href="#">SHOP</a>
					</nav>
				</div>
			</div>
		</div>
	</header>
</template>

<script></script>

<style lang="scss">
@import "../assets/scss/common.scss";
@import "../assets/scss/variables.scss";
#SiteHeader {
	background-color: #fff;
	height: 100px;
	.row {
		justify-content: space-between;
	}
	.menu {
		a {
			margin: 0 0.5rem; 
			text-decoration: none;
			color: #333;
			&.active {
				background-color: $brand_backgroundColor;
			}
			&:hover {
				height: 100%;
				padding: 2rem 0;
				color: $brand_backgroundColor;
				border-bottom: 5px solid $brand_backgroundColor;
			}
		}
	}
}
</style>
