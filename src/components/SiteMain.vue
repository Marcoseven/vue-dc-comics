<template>
	<main id="SiteMain">
		<!-- #jumbo -->
		<div id="jumbo"></div>
		<!-- /#jumbo -->

		<!-- #rowCards -->
		<div id="rowCards">
			<div class="container">
				<div id="buttonSeries">
					<span>
						<h2>CURRENT SERIES</h2>
					</span>
				</div>

				<div class="row">
					<Product
						v-for="card in cards"
						:key="card.series"
						:image="card.thumb"
						:title="card.series"
						class="col-2"
					/>
				</div>
				<div class="col-12" id="buttonMore">
					<button type="submit">LOAD MORE</button>
				</div>
			</div>
		</div>
		<!-- /#rowCards -->

		<!-- #rowIcons -->
		<div id="rowIcons">
			<div class="container row">
				<div class="col-2">
					<a href="#">
						<img
							src="../assets/img/buy-comics-digital-comics.png"
							alt="immagine di un tablet con raffigurato il logo della Digital Comics"
						/>
						<h6>DIGITAL COMICS</h6>
					</a>
				</div>
				<div class="col-2">
					<a href="#">
						<img
							src="../assets/img/buy-comics-merchandise.png"
							alt="immagine che raffigura una maglietta"
						/>
						<h6>DC MERCHANDISE</h6>
					</a>
				</div>
				<div class="col-2">
					<a href="#">
						<img
							src="../assets/img/buy-comics-subscriptions.png"
							alt="immagine di due card"
						/>
						<h6>SUBSCRIPTION</h6>
					</a>
				</div>
				<div class="col-2">
					<a href="#">
						<img
							src="../assets/img/buy-comics-shop-locator.png"
							alt="immagine che raffigura la localizzazione di un luogo"
						/>
						<h6>COMIC SHOP LOCATOR</h6>
					</a>
				</div>
				<div class="col-2">
					<a href="#">
						<img
							src="../assets/img/buy-dc-power-visa.svg"
							alt="immagine che raffigura una card"
						/>
						<h6>DC POWER VISA</h6>
					</a>
				</div>
			</div>
		</div>
		<!-- /#rowIcons -->
	</main>
</template>

<script>
import Product from "./Cards";
export default {
	components: {
		Product,
	},
	data() {
		return {
			cards: [
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
					price: "$19.99",
					series: "Action Comics",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
					price: "$3.99",
					series: "American Vampire 1976",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
					price: "$16.99",
					series: "Aquaman",
					type: "graphic novel",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
					price: "$2.99",
					series: "Batgirl",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
					price: "$3.99",
					series: "Batman",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
					price: "$2.99",
					series: "Batman Beyond",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
					price: "$3.99",
					series: "Batman/Superman",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
					price: "$4.99",
					series: "Batman/Superman Annual",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
					price: "$5.99",
					series: "Batman: The Joker War Zone",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
					price: "$6.99",
					series: "Batman: Three Jokers",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
					price: "$4.99",
					series: "Batman: White Knight Presents: Harley Quinn",
					type: "comic book",
				},
				{
					thumb:
						"https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
					price: "$16.99",
					series: "Catwoman",
					type: "graphic novel",
				},
			],
		};
	},
};
</script>

<style lang="scss">
@import "../assets/scss/common.scss";
@import "../assets/scss/variables.scss";

#SiteMain {
	height: auto;
	position: relative;
	z-index: 10;
	#jumbo {
		height: 330px;
		background-image: url("../assets/img/jumbotron.jpg");
		background-repeat: no-repeat;
		background-size: cover;
	}

	/* #rowCards */
	#rowCards {
		height: auto;
		background-color: #000;
		#buttonSeries h2 {
			width: 20%;
			padding: 0.5rem 1rem;
			font-size: 20px;
			background-color: $brand_color;
			color: white;
			text-align: center;
			position: relative;
			top: -15px;
			left: 0;
		}

		.row {
			flex-wrap: wrap;
		}

		#buttonMore {
			text-align: center;

			button {
				padding: 0.5rem 3rem;
				margin-bottom: 1rem;
				color: #fff;
				background-color: $brand_color;
				border: none;
				&:hover {
					cursor: pointer;
				}
			}
		}
	}
	/* /#rowCards */

	/* #rowIcons */
	#rowIcons {
		height: auto;
		background-color: $brand_color;
		.container {
			justify-content: space-between;
			align-items: center;
		}

		h6 {
			margin: 0 0.5rem;
		}

		a {
			display: flex;
			align-items: center;
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
	/* /#rowIcons */
}
</style>
