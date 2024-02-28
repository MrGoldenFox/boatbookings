<section>
	<header>
		<div class="btn">
			<button>ADVICE</button>
			<button>DESTINATIONS</button>
			<button>NEWS</button>
			<button id="search"><img src={'img/search.svg'} alt="" /> SEARCH</button>
		</div>
		<div id="logo">
			<img src={'img/Logo.svg'} alt="" />
		</div>
		<div class="btn">
			<button>ABOUT US</button>
			<button>CONTACT US</button>
			<button>ENQUIRE</button>
			<button><img src={'img/vecktor3.svg'} alt="" /></button>
		</div>
	</header>
	<main>
		<div>
			<h1>Where would you like to charter?</h1>
		</div>
		<div class="mainContainer">
			<div class="inputs">
				<div>
					<p>DESTINATION</p>
					<input type="text" placeholder="Destination">
				</div>
				<div>
					<p>CREW TYPE</p>
					<input type="text" placeholder="Crewed/Bareboat">
				</div>
				<div>
					<p>BOAT TYPE</p>
					<input type="text" placeholder="Boat type">
				</div>
			</div>
			<div class="btn-GO">
				<button>LET’S GO!</button>
			</div>
		</div>
	</main>

</section>

<style>
	section {
		position: relative;
		background-image: url('img/Home.png');
		min-height: 100vh;
		background-size: cover;
		max-width: 100%;
	}
	header {
		min-height: 10vh;
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 0 20px;
	}
	#logo img {
		width: 275px;
		height: 36px;
	}

	.btn {
		display: flex;
		flex-direction: row;
		gap: 10px;
	}

	.btn button {
		font-family: 'Inter', sans-serif;
		font-weight: 400;
		font-size: 0.8em;
		line-height: 16.94px;
		color: white;
		background-color: transparent;
		border: none;
		letter-spacing: 0.5px;
	}

	.btn button:hover {
		opacity: 50%;
		transition: 0.5s;
	}

	#search img {
		height: 20px;
		width: 20px;
	}

	main {
		height: 90vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		position: relative;
	}
	
	.mainContainer {
		display: flex;
		flex-direction: column;
		gap: 20px;
	}

	main h1 {
		text-align: center;
		font-family: "Yeseva One", serif;
		font-weight: 400;
		font-style: normal;
		font-size: 5.5vw;
		line-height: 128px;
		color: #FFFFFF;
		width: fit-content;
	}

	.inputs {
		display: flex;
		gap: 20px;
	}

	.inputs p {
		font-family: "Inter", sans-serif;
		font-style: normal;
		font-weight: 600;
		font-size: 0.8em;
		line-height: 14.52px;
		letter-spacing: 2.5px;
		color: #D9C2A6;
	}

	.inputs input {
		padding: 20px, 24px, 20px, 24px;
		width: 40vh;
		height: 5vh;
	}

	.inputs input::placeholder {
		padding-left: 20px;
		color: #BBBBBB;
		font-family: "Inter", sans-serif;
		font-size: 1.1em;
		line-height: 24px;
	}

	.btn-GO {
		display: flex;
		justify-content: end;
	}

	.btn-GO button {
		border: none;
		background-color: #D9C2A6;
		width: 15vh;
		height: 7.5vh;
		padding: 22px, 32px, 22px, 32px;
		border: none;
		color: #022135;
		font-weight: 600;
		font-family: "Inter", serif;
		font-size: 1em;
		line-height: 19.36px;
		text-align: center;
	}

	.btn-GO button:hover {
		background-color: transparent;
		color: white;
		border: white 1px solid;
		transition: 0.5s ease-in-out;
	}

	@media only screen and (max-width: 1100px) {
		/* header */
		header {
			position: relative;
			display: flex;
			justify-content: center;
		}
		.btn {
			display: none;
		}
		#logo {
			width: auto;
			height: auto;
		}
		#logo img {
			max-width: calc(100% - 1px);
		}
		/* main */
		main {
		height: 90vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		position: relative;
	}
	.mainContainer {
		position: relative;
		flex-direction: column;
		gap: 20px;
	}
	.inputs {
		display: block;
	}

	}

	@media only screen and (max-width: 500px) {
		.inputs input {
			width: 80vw;
		}
	}
</style>
