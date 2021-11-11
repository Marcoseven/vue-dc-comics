<template>
	<main id="SiteMain">
		<div class="container">
			<div class="rowUp d-flex">
				<div id="here">--> Content goes here</div>
			</div>
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
		</div>
	</main>
</template>

<script></script>

<style lang="scss">
@import "../assets/scss/common.scss";
@import "../assets/scss/variables.scss";

#SiteMain {
	height: auto;
	background-image: linear-gradient(
		to bottom,
		#000 0px,
		#000 100px,
		$brand_backgroundColor 100px,
		$brand_backgroundColor 250px
	);

	.rowUp {
		height: 100px;
		align-items: center;
		justify-content: start !important;
		#here {
			color: #fff;
		}
	}
	.rowCards {
		height: 150px;
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
				width: 50px;
			}
			:nth-child(2) {
				margin: 0 0.5rem;
				font-size: 13px;
			}
		}
	}
}
</style>
