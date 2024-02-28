<script>
</script>

<section>
    <div class="nameOfSite">
        <h2>Trending Charter Destinations and Itineraries</h2>
    </div>
    <main>
        <div class="destination2Container">
            <img src={"/img/destination2_1.svg"} alt="">
            <h3>Greek Island Charm </h3>
            <p>Unveil a rich history, rustic Greek tavernas, olive groves and white-washed fishing villages by charter yacht.</p>
            <div class="buttons">
                <button id="btn-Guide">Greece Charter Guide</button>
                <button id="Itinerary">Greece Charter Guide</button>
            </div>
        </div>
        <div class="destination2Container">
            <img src={"/img/destination2_2.svg"} alt="">
            <h3>French Riviera </h3>
            <p>Cruise from the glamorous hangouts of Cannes and Monaco to the hushed haven of Hyères for the ultimate charter.</p>
            <div class="buttons">
                <button id="btn-Guide">French Riviera Charter Guide</button>
                <button id="Itinerary">French Riviera Itinerary</button>
            </div>
        </div>
        <div class="destination2Container">
            <img src={"/img/destination2_3.svg"} alt="">
            <h3>Amalfi Coast</h3>
            <p>Hike volcanoes, tour ancient ruins, dine with the jet set and pamper yourself on the Amalfi Coast.</p>
            <div class="buttons">
                <button id="btn-Guide">Amalfi Charter Guide</button>
                <button id="Itinerary">Amalfi Coast Itinerary</button>
            </div>
        </div>
        <div class="destination2Container">
            <img src={"/img/destination2_4.svg"} alt="">
            <h3>The Bahamas </h3>
            <p>Discover the enchanting Exumas. Dive Thunderball Grotto and explore Staniel Cay by tender and toys.</p>
            <div class="buttons">
                <button id="btn-Guide">Bahamas Charter Guide</button>
                <button id="Itinerary">Bahamas Itinerary</button>
            </div>
        </div>
        <div class="destination2Container">
            <img src={"/img/destination2_5.svg"} alt="">
            <h3>British Virgin Islands </h3>
            <p>Discover The Baths of Virgin Gorda and Jost Van Dyke's palm-fringed beaches for an exclusive winter revival.</p>
            <div class="buttons">
                <button id="btn-Guide">BVI Yacht Charter Guide</button>
                <button id="Itinerary">BVI Catamaran Itinerary</button>
            </div>
        </div>
    </main>
</section>

<style>
    section {
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        min-height: 50vh;
    }
    .nameOfSite {
        display: flex;
        justify-content: center;
    }

    main {
        min-height: 110vh;
        display: flex;
        gap: 20px;
        padding-left: 20px;
        overflow-x: auto;
    }

    .nameOfSite h2 {
        font-family: "Yeseva One", sans-serif;
        font-weight: 400;
        font-size: 3vw;
        letter-spacing: 0.2px;
        color: #022135;
    }

    .destination2Container h3 {
        color: #022135;
        font-family: "Yeseva One", sans-serif;
        font-weight: 400;
        font-size: 2vw;
        line-height: 36.96px;
    }

    .destination2Container p {
        color: #4A5C68;
        font-family: "Inter", sans-serif;
        font-weight: 400;
        font-size: 1vw;
        line-height: 25.6px;
    }
    .buttons {
        font-family: "Inter", sans-serif;
        display: flex;
        width: 35vw;
        height: 7vh;
        padding: 22px, 32px, 22px, 32px;
        font-size: 1vw; 
        gap: 1em;
    }

    .destination2Container img {
        width: 100%;
        height: 50%;
        object-fit: cover;
        object-position: 50% 50%;
    }
    
    #btn-Guide {
        background-color: #2C84C9;
        color: #FFFFFF;
        border: none;
    }

    #btn-Guide:hover {
        background-color: hsl(240, 100%, 10%);
        transition: 0.6s ease;
    }

    #Itinerary {
        background-color: transparent;
        text-decoration: underline;
        color: #022135;
        border: none;
        font-weight: 600;
        line-height: 19.36px;
    }

    #Itinerary:hover {
        text-decoration: none;
        transition: 1s ease;
    }

    @media only screen and (max-width: 800px){
        .nameOfSite h2 {
                font-size: 2em;
            }
        .nameOfSite {
            display: flex;
            justify-content: center;
            text-align: center;
        }
        .destination2Container h3 {
            color: #022135;
            font-family: "Yeseva One", sans-serif;
            font-weight: 400;
            font-size: 5vw;
            line-height: 36.96px;
        }

        .destination2Container p {
            color: #4A5C68;
            font-family: "Inter", sans-serif;
            font-weight: 400;
            font-size: 3vw;
            line-height: 25.6px;
        }
        main {
            padding-bottom: 5vh;
        }
    }

    @media only screen and (max-width: 400px){
        .buttons button {
            font-size: 2.5em;
        }
    }
</style>