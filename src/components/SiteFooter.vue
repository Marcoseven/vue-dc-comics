<template>
	<div id="SiteFooter">
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
					<div>
						<h4>DC</h4>
					</div>
				</div>
				<div class="col-6">
					<img src="../assets/img/dc-logo-bg.png" alt="" />
				</div>
			</div>
		</div>
	</div>
</template>

<script></script>

<style lang="scss">
@import "../assets/scss/common.scss";
@import "../assets/scss/variables.scss";
#SiteFooter {
	height: auto;
	background-image: url("../assets/img/footer-bg.jpg");
	background-repeat: no-repeat;
	background-position: center;
	.row {
		justify-content: space-between;
		h4 {
			color: #fff;
			margin: 1rem 0;
		}
		li {
			list-style: none;
			margin: 0.5rem 0;
			a {
				text-decoration: none;
				color: gray;
			}
		}
	}
}
</style>
