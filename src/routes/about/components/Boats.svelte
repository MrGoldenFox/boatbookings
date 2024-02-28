<section>
    <main>
        <div class="mainContainer">
            <img src={"/img/boat1.svg"} alt="boats">
            <p>Discover our</p>
            <h3>Bareboats</h3>
        </div>
        <div class="mainContainer">
            <img src={"/img/boat2.svg"} alt="boats">
            <p>Discover our</p>
            <h3>Catamarans</h3>
        </div>
        <div class="mainContainer">
            <img src={"/img/boat3.svg"} alt="boats">
            <p>Discover our</p>
            <h3>Crewed Yachts</h3>
        </div>
    </main>
    <div class="txt">
        <p>Plan your bespoke charter with expert, unbiased advice on the yachts and crews we present. Our specialists are in constant contact with all the key charter locations to make sure you enjoy open, accessible and safe destinations with confidence.</p>
        <div class="btn-ENQUIRE">
            <button>ENQUIRE</button>
        </div>
    </div>
</section>

<style>
    section {
        display: flex;
        flex-direction: column;
        background-color: #EEF3F4;
        min-height: 100vh;
        width: 100%;
        position: relative;
        justify-content: center;
    }
    main {
        align-content: center;
        position: relative;
        display: flex;
        justify-content: center;
        gap: 10px;
    }

    .mainContainer img {
        width:100%;
        height: 37vh;
        object-fit:cover;
        object-position:50% 50%;
    }
    .mainContainer {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .mainContainer p {
        color: #4A5C68;
        font-family: "Inter", sans-serif;
        font-size: 1vw;
        height: 1px;
    }

    .mainContainer h3 {
        color: #022135;
        font-family: "Yeseva One", sans-serif;
        font-size: 2vw;
        font-weight: 400;
    }

    .txt p {
        font-family: "Yeseva One", serif;
        font-weight: 400;
        font-size: 2vw;
        text-align: center;
    }

    .txt {
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
    }

    .txt button {
        background-color: transparent;
        border: black 1px solid;
        width: 10vw;
        height: 7vh;
        padding: 22px, 32px, 22px, 32px;
        color: #022135;
        font-family: "Inter", sans-serif;
        font-weight: 600;
        font-size: 1vw;
        text-align: center;
        line-height: 19.36px;
    }
    .btn-ENQUIRE {
        display: flex;
        justify-content: center;
    }

    .btn-ENQUIRE button {
        width: 20vw;
        font-size: 2vw;
    }

    .btn-ENQUIRE button:hover {
        background-color: #022135;
        color: white;
        transition: 0.8s ease;
    }

    @media only screen and (max-width: 600px){
        .btn-ENQUIRE button {
            width: 100px;
            text-align: center;
            font-size: 3.5vw;
        }

        .mainContainer p {
        color: #4A5C68;
        font-family: "Inter", sans-serif;
        font-size: 3vw;
        height: 1px;
    }

    .mainContainer h3 {
        color: #022135;
        font-family: "Yeseva One", sans-serif;
        font-size: 4vw;
        font-weight: 400;
    }

    .txt p {
        font-family: "Yeseva One", serif;
        font-weight: 400;
        font-size: 5vw;
        text-align: center;
    }

    .txt {
        padding-bottom: 10px;
    }

    }
</style>