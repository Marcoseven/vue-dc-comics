<template>
	<div id="SiteFooter">
		<!-- .rowLinks -->
		<div class="rowLinks">
			<div class="container">
				<div class="row">
					<div class="col-6 row">
						<div>
							<div>
								<h4>DC COMICS</h4>
								<ul>
									<li>
										<a href="#">Characters</a>
									</li>
									<li>
										<a href="#">Comics</a>
									</li>
									<li>
										<a href="#">Movies</a>
									</li>
									<li>
										<a href="#">TV</a>
									</li>
									<li>
										<a href="#">Games</a>
									</li>
									<li>
										<a href="#">Videos</a>
									</li>
									<li>
										<a href="#">News</a>
									</li>
								</ul>
							</div>
							<div>
								<h4>SHOP</h4>
								<ul>
									<li>
										<a href="#">Shop DC</a>
									</li>
									<li>
										<a href="#">Shop DC Collectibles</a>
									</li>
								</ul>
							</div>
						</div>
						<div id="colDC">
							<h4>DC</h4>
							<ul>
								<li>
									<a href="#">Terms Of Use</a>
								</li>
								<li>
									<a href="#">Privacy policy (New)</a>
								</li>
								<li>
									<a href="#">Ad Choise</a>
								</li>
								<li>
									<a href="#">Advertising</a>
								</li>
								<li>
									<a href="#">Jobs</a>
								</li>
								<li>
									<a href="#">Subscriptions</a>
								</li>
								<li>
									<a href="#">Talent Workshops</a>
								</li>
								<li>
									<a href="#">CPSC Certificates</a>
								</li>
								<li>
									<a href="#">Ratings</a>
								</li>
								<li>
									<a href="#">Shop Help</a>
								</li>
								<li>
									<a href="#">Contact Us</a>
								</li>
							</ul>
						</div>
						<div>
							<h4>SITES</h4>
							<ul>
								<li>
									<a href="#">DC</a>
								</li>
								<li>
									<a href="#">MAD Magazine</a>
								</li>
								<li>
									<a href="#">DC Kids</a>
								</li>
								<li>
									<a href="#">DC Universe</a>
								</li>
								<li>
									<a href="#">DC Power Visa</a>
								</li>
							</ul>
						</div>
					</div>
					<div class="col-6" id="image">
						<img src="../assets/img/dc-logo-bg.png" alt="" />
					</div>
				</div>
			</div>
		</div>
		<!-- /.rowLinks -->

		<!-- .rowSocial -->
		<div class="rowSocial">
			<div class="container">
				<div class="row" id="rowPrimary">
					<div class="col-6 row">
						<button>SIGN-UP NOW!</button>
					</div>
					<div class="col-6 row">
						<h4>FOLLOW US</h4>
						<div class="row">
							<a href="#"
								><img src="../assets/img/footer-facebook.png" alt=""/>
							</a>
							<a href="#">
								<img src="../assets/img/footer-twitter.png" alt="" />
							</a>
							<a href="#">
								<img src="../assets/img/footer-youtube.png" alt="" />
							</a>
							<a href="#">
								<img src="../assets/img/footer-pinterest.png" alt="" />
							</a>
							<a href="#">
								<img src="../assets/img/footer-periscope.png" alt="" />
							</a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /.rowSocial -->
	</div>
</template>

<script></script>

<style lang="scss">
@import "../assets/scss/common.scss";
@import "../assets/scss/variables.scss";
#SiteFooter {
	height: auto;
	width: 100%;

	.rowLinks {
		justify-content: space-between;
		background-image: url("../assets/img/footer-bg.jpg");
		background-repeat: no-repeat;
		background-size: cover;

		#colDC {
			margin: 0 2rem;
		}

		h4 {
			color: #fff;
			margin: 1rem 0;
		}

		li {
			margin: 0.5rem 0;

			a {
				color: gray;
				&:hover {
					text-decoration: underline;
				}
			}
		}

		img {
			width: 65%;
			position: relative;
			bottom: 20%;
			right: 0;
		}
	}
}
.rowSocial {
	height: 100px;
	background-color: $footer_backgroundColor;
	color: #fff;

	#rowPrimary {
		height: 100%;
		justify-content: space-between;

		a {
			margin: 0 0.5rem;
		}
	}

	button {
		width: 20%;
		padding: 0.8rem;
		color: #fff;
		border: 1px solid $brand_color;
		background-color: $footer_backgroundColor;
		&:hover {
			cursor: pointer;
		}
	}

	.col-6 {
		align-items: center;
	}

	h4 {
		color: $brand_color;
		margin-right: 1rem;
	}
}
</style>
