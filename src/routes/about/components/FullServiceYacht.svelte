<section>
	<div class="text">
		<h2>Your Full Service Yacht Charter Broker</h2>
	</div>
	<div class="content">
		<div class="txt">
			<h3>The Boatbookings Worldwide Team</h3>
			<p>
				Boatbookings is a full service independent yacht charter broker - our only business is
				putting clients on charter yachts. Whether it's a crewed luxury motor yacht, bareboat
				sailing yacht or a crewed catamaran our experts will get you on the perfect yacht.
			</p>
			<div class="btn">
				<button>MEET THE TEAM</button>
			</div>
		</div>
		<div class="img">
			<img src={'/img/fullServiceYacht.svg'} alt="img" />
		</div>
	</div>
</section>

<style>
	section {
		background-color: #eef3f4;
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		min-width: 100%;
	}

	.content {
		display: flex;
		justify-content: center;
		gap: 20px;
		padding-inline: 20px;
	}

	.txt {
		max-width: 448px;
	}

	.text h2 {
		font-family: 'Yeseva One', sans-serif;
		font-weight: 400;
		font-size: 3em;
		line-height: 55.44px;
		letter-spacing: 2px;
		text-align: center;
		color: #022135;
		padding-bottom: 50px;
	}

	.txt h3 {
		font-family: 'Yeseva One', sans-serif;
		font-weight: 400;
		font-size: 2em;
		line-height: 36.96px;
		text-align: right;
		color: #022135;
	}

	.txt p {
		font-family: 'Inter', sans-serif;
		font-weight: 400;
		font-size: 1em;
		line-height: 25.6px;
		text-align: Right;
		color: #4a5c68;
	}

	.btn {
		display: flex;
		justify-content: end;
	}

	.btn button {
		padding: 22px, 32px, 22px, 32px;
		border: 1px solid black;
		width: 14vw;
		height: 9vh;
		background-color: transparent;
		font-family: 'Inter', sans-serif;
		font-weight: 600;
		font-size: 1em;
		line-height: 19.36px;
		text-align: center;
	}

	.btn button:hover {
		background-color: #022135;
		color: white;
		transition: 0.5s ease;
	}

	@media only screen and (max-width: 1060px) {
		.content {
			display: table;
		}

		.img {
			display: table-header-group;
		}

		.txt {
			padding-bottom: 50px;
		}

		.txt h3 {
			text-align: center;
		}

		.txt p {
			text-align: center;
		}
		.btn {
			justify-content: center;
		}
		.btn button {
			width: 40vw;
		}
	}

	@media only screen and (max-width: 600px) {
		.img img {
			width: calc(100% - 1px);
			height: auto;
		}

	.text h2 {
		font-weight: 700;
        font-size: 2em;
	}

	.txt {
		width: calc(100% - 1px);
	}

    .txt h3 {
        font-size: 1.7em;
    }
}
</style>
