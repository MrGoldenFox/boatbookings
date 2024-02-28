<script>
	import { base } from '$app/paths';
</script>

<section>
	<div class="mainContent">
		<div class="allContent">
			<div class="content">
				<p>POPULAR YACHT CHARTER REGIONS</p>
				<br />
				<a href="">Caribbean Sea Charter Yachts</a><br />
				<a href="">Mediterranean Sea Charter Yachts</a><br />
				<a href="">Pacific Ocean Charter Yachts</a><br />
				<a href="">Thailand and Indian Ocean Charter Yachts</a><br />
				<a href="">Recent Charter Articles </a><br />
				<a href="">Virgin Islands Yacht Charter</a><br />
				<a href="">Bahamas Yacht Charter</a><br />
				<a href="">Seychelles Yacht Charter</a><br />
				<a href="">Where We Charter</a>
			</div>
			<div class="content">
				<p>KEY CHARTER EVENTS AND TYPES</p>
				<a href="">Corporate Yacht Charter</a><br />
				<a href="">Event Yacht Charter</a><br />
				<a href="">Cannes Film Festival Yacht Charter</a><br />
				<a href="">Monaco Grand Prix Yacht Charter</a><br />
				<a href="">Charter Events in Cannes</a><br />
				<a href="">Weddings and Honeymoon Yacht Charters</a><br />
				<a href="">Family Charters with Children</a><br />
				<a href="">List your Charter Yacht on Boatbookings</a>
			</div>
			<div class="content">
				<p>BOATBOOKINGS NETWORK</p>
				<a href="">Stunning Yachts Charter</a><br />
				<a href="">Boating News and Blog</a><br />
				<a href="">Boat Itineraries</a><br />
				<a href="">France location de bateaux</a><br />
				<a href="">Boten Verhuur, Boot Charter</a><br />
				<a href="">Boot Charter/Location de Bateaux</a><br />
				<a href="">Alquiler de Embarcaciones</a><br />
				<a href="">Turkiye Yat Kiralama</a>
			</div>
		</div>
	</div>
	<div class="social">
		<a href=""><img src="{base}/img/facebook.svg" alt="img"></a>
		<a href=""><img src="{base}/img/instagram.svg" alt="img"></a>
		<a href=""><img src="{base}/img/linkd.svg" alt="img"></a>
		<a href=""><img src="{base}/img/twitter.svg" alt="img"></a>
		<a href=""><img src="{base}/img/youtube.svg" alt="img"></a>
		<a href=""><img src="{base}/img/pinterest.svg" alt="img"></a>
	</div>
</section>

<style>
	section {
		padding-top: clamp(50vh, 40vh, 150vh);
		background-color: #022135;
		min-height: 100vh;
		max-width: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		gap: 40px;
	}

	.allContent {
		display: flex;
		gap: 8vw;
	}

	.content p {
		font-family: 'Inter', sans-serif;
		font-size: 1.2em;
		line-height: 24.2px;
		color: #eef3f4;
		text-align: left;
	}

	.content a {
		font-family: 'Inter', serif;
		font-weight: 400;
		font-size: 1em;
		line-height: 30px;
		color: #eef3f4;
		text-decoration: none;
		letter-spacing: 1px;
	}

	.content a:hover {
		text-decoration: underline;
	}

	.social {
		display: flex;
		gap: 20px;
	}

	@media only screen and (max-width: 600px) {
		.content p {
			font-size: 0.8em;
		}

		.content a {
			font-size: 0.6em;
		}
		section {
			padding-top: clamp(80vh, 40vh, 150vh);
		}

		.social img {
			width: 6vw;
			height: auto;
		}
	}

	@media only screen and (max-width: 350px) {
        .content p {
			font-size: 0.6em;
		}

		.content a {
			font-size: 0.5em;
		}
		section {
			padding-top: clamp(100vh, 40vh, 150vh);
		}
	}
</style>
