<template>
	<main id="SiteMain">
		<div class="container">
			<!-- .rowUp -->
			<div class="rowUp row">
				<div id="here">--> Content goes here</div>
			</div>
			<!-- /.rowUp -->

			<!-- .rowCards -->
			<div class="rowCards">
				<div class="col-2">
					<a href="#">
						<img src="../assets/img/buy-comics-digital-comics.png" alt="" />
						<h6>DIGITAL COMICS</h6>
					</a>
				</div>
				<div class="col-2">
					<a href="#">
						<img src="../assets/img/buy-comics-merchandise.png" alt="" />
						<h6>DC MERCHANDISE</h6>
					</a>
				</div>
				<div class="col-2">
					<a href="#">
						<img src="../assets/img/buy-comics-subscriptions.png" alt="" />
						<h6>SUBSCRIPTION</h6>
					</a>
				</div>
				<div class="col-2">
					<a href="#">
						<img src="../assets/img/buy-comics-shop-locator.png" alt="" />
						<h6>COMIC SHOP LOCATOR</h6>
					</a>
				</div>
				<div class="col-2">
					<a href="#">
						<img src="../assets/img/buy-dc-power-visa.svg" alt="" />
						<h6>DC POWER VISA</h6>
					</a>
				</div>
			</div>
			<!-- /.rowCards -->
		</div>
	</main>
</template>

<script></script>

<style lang="scss">
@import "../assets/scss/common.scss";
@import "../assets/scss/variables.scss";

#SiteMain {
	height: 50vh;
	position: relative;
	z-index: 10;
	background-image: linear-gradient(
		to bottom,
		#000 0px,
		#000 40%,
		$brand_color 40%,
		$brand_color 100%
	);

	.rowUp {
		height: 45%;
		align-items: center;
		justify-content: start !important;
		#here {
			color: #fff;
		}
	}
	.rowCards {
		height: 55%;
		display: flex;
		align-items: center;
		justify-content: space-around;

		.cards-2 {
			align-items: center;
		}

		h6 {
			margin: 0 0.5rem;
		}

		a {
			display: flex;
			align-items: center;
			text-decoration: none;
			color: #fff;
			img {
				width: 30%;
			}
			:nth-child(2) {
				margin: 0 0.5rem;
				font-size: 15px;
			}
		}
	}
}
</style>
