<section>
    <div class="text">
        <h2>Yachting Hot Spots and Events</h2>
    </div>
    <div class="mainContainer">
        <div class="container1">
            <div class="img">
                <img src={"/img/yachting1.svg"} alt="img">
            </div>
            <div class="txt1">
                <h3>The French Riviera</h3>
                <p>The French Riviera is one of the most glamorous yachting destinations in the world with the best restaurants and beach clubs in the Mediterranean - soak up the ambience during summer and explore Cannes, Monaco and St Tropez on one of our crewed motor yachts.</p>
                <div class="buttons1">
                    <button id="btn1">ITINERARY</button>
                    <button id="btn2">CHARTER GUIDE</button>
                </div>
            </div>
        </div>
        <div class="container2">
            <div class="txt2">
                <h3>Bahamas Yacht Charter</h3>
                <p>The Bahamas is a paradisal pocket where crystal-clear waters meet white sandy swathes. Each island has a unique identity, so whether you want to explore the tropical marine life whilst snorkelling, or wish to swim with the pigs, our expert brokers will tailor the perfect yacht charter itinerary.</p>
                <div class="buttons2">
                    <button id="btn1">ITINERARY</button>
                    <button id="btn2">CHARTER GUIDE</button>
                </div>
            </div>
            <div class="img">
                <img src={"/img/yachting2.svg"} alt="img">
            </div>
        </div>  
        <div class="container1">
            <div class="img">
                <img src={"/img/yachting3.svg"} alt="img">
            </div>
            <div class="txt1">
                <h3>Greek Glamour</h3>
                <p>Are you dreaming of turquoise waters, year-round sunshine and the best feta cheese you’ll ever have? Look no further than Greece. From the beautiful Dodecanese Islands to the stunning town of Mykonos, Greece is the place to charter a yacht this year.</p>
                <div class="buttons1">
                    <button id="btn1">ITINERARY</button>
                    <button id="btn2">CHARTER GUIDE</button>
                </div>
            </div>
        </div>
        <div class="container2">
            <div class="txt2">
                <h3>Spring Break in the US Virgin Islands</h3>
                <p>There is no better way to spend the holidays with your family and friends than island hopping in the magical US Virgin Islands. Charter a skippered or crewed catamaran and be pampered as you explore some of the most spectacular cruising grounds in the world.</p>
                <div class="buttons2">
                    <button id="btn1">ITINERARY</button>
                    <button id="btn2">CHARTER GUIDE</button>
                </div>
            </div>
            <div class="img">
                <img src={"/img/yachting4.svg"} alt="img">
            </div>
        </div>  
        <div class="container1">
            <div class="img">
                <img src={"/img/yachting5.svg"} alt="img">
            </div>
            <div class="txt1">
                <h3>Discover the Costa Rican Charm</h3>
                <p>Costa Rica offers adventure both above and below the waterline. Anchor in bays fringed by tropical rainforest abuzz with toucans and howler monkeys.</p>
                <div class="buttons1">
                    <button id="btn1">ITINERARY</button>
                    <button id="btn2">CHARTER GUIDE</button>
                </div>
            </div>
        </div>
        <div class="container2">
            <div class="txt2">
                <h3>Discover the Lagoons of Tahiti</h3>
                <p>Secluded anchorages, serene vistas, wonderful topography and an exuberant underwater world makes this Polynesian destination the ultimate charter vacation onboard a catamaran or motor yacht.</p>
                <div class="buttons2">
                    <button id="btn1">ITINERARY</button>
                    <button id="btn2">CHARTER GUIDE</button>
                </div>
            </div>
            <div class="img">
                <img src={"/img/yachting6.svg"} alt="img">
            </div>
        </div>  
        <div class="container1">
            <div class="img">
                <img src={"/img/yachting7.svg"} alt="img">
            </div>
            <div class="txt1">
                <h3>BVI Bliss</h3>
                <p>See in the New Year in style with a yacht charter in the British Virgin Islands. Consistent winds, idyllic islands, beach bars, and a mesmerising aquatic life makes the BVI is the perfect cruising ground.</p>
                <div class="buttons1">
                    <button id="btn1">ITINERARY</button>
                    <button id="btn2">CHARTER GUIDE</button>
                </div>
            </div>
        </div>
        <div class="container2">
            <div class="txt2">
                <h3>Monaco Grand Prix</h3>
                <p>Experience the most highly anticipated F1 event of the year with champagne in hand, from the most exclusive viewing platform in Monte Carlo - on deck.</p>
                <div class="buttons2">
                    <button id="btn1">MONACO F1</button>
                    <button id="btn2">CHARTER GUIDE</button>
                </div>
            </div>
            <div class="img">
                <img src={"/img/yachting8.svg"} alt="img">
            </div>
        </div>  
    </div>
</section>

<style>
    .text {
        width: calc(100% - 1px);
        font-family: "Yeseva One", serif;
        font-weight: 200;
        font-size: 2em;
        line-height: 55.44px;
        letter-spacing: 2px;
        text-align: center;
        display: flex;
        justify-content: center;

    }

    section {
        background-color: #EEF3F4;
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding-inline: 15vw;
        padding-block: 7vh;
    }

    .mainContainer {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 10vh;
    }

    .container1 {
        display: flex;
        gap: 20px;
    }

    .container1 h3 {
        font-family: "Yeseva One", sans-serif;
        font-weight: 400;
        font-size: 2em;
        line-height: 36.96px;
    }

    .container1 p {
        font-family: "Inter", serif;
        font-weight: 400;
        font-size: 1em;
        line-height: 25.6px;
        color: #4A5C68;
    }
    .container2 h3 {
        font-family: "Yeseva One", sans-serif;
        font-weight: 400;
        font-size: 2em;
        line-height: 36.96px;
    }

    .container2 p {
        font-family: "Inter", serif;
        font-weight: 400;
        font-size: 1em;
        line-height: 25.6px;
        color: #4A5C68;
    }

    .container2 {
        gap: 20px;
        display: flex;
    }

    #btn1 {
        background-color: #D9C2A6;
        padding: 22px, 32px, 22px, 32px;
        width: 10em;
        height: 4em;
        border: none;
        font-family: "Inter", sans-serif;
        font-weight: 600;
        font-size: 1em;
        line-height: 19.36px;
        text-align: Center;
        color: #022135;
    }

    #btn1:hover {
        background-color: transparent;
        border: 1px solid black;
        transition: 1s ease;
    }

    #btn2:hover {
        background-color:#022135;
        color: white;
        border: none;
        transition: 0.6s ease;
    }

    #btn2 {
        background-color: transparent;
        border: 1px solid black;
        padding: 22px, 32px, 22px, 32px;
        width: 14em;
        height: 4em;
        line-height: 19.36px;
        font-family: "Inter", sans-serif;
        font-weight: 600;
        font-size: 1em;
        line-height: 19.36px;
        text-align: center;
    }

    .buttons1 {
        display: flex;
        gap: 1em;
    }

    .buttons2 {
        display: flex;
        gap: 1em;
        justify-content: end;
    }

    .txt2 {
        text-align: right;
    }

    @media only screen and (max-width: 1000px) {
        .container1 {
            display: table;
        }
        .container2 {
            display: table;
        }

        .txt2 {
            display:table-footer-group;
            text-align: left;
        } 

        .img {
            width: calc(100% - 1px);
        }

        .buttons2 {
        display: flex;
        justify-content: start;
        }
        
        .mainContainer {
            width: calc(100% - 1px);
        }
    }

    @media only screen and (max-width: 550px) {
        .text h2 {
            font-size: calc(100% - 1px);
        }

        .img img {
            width: 100vw;
            height: auto;
        }
        .img {
            display: flex;
            justify-content: center;
        }

        .container2 h3{
            font-size: calc(2em - 1px);
        }
        
        .container1 h3{
            font-size: calc(2em - 1px);
        }

        .buttons2 {
            display: block;
            padding-left: 1px;
        }

        .buttons1 {
            display: block;
            padding-left: 1px;
        }
    }
</style>