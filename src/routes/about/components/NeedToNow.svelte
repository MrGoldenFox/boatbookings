<script>
	import { base } from '$app/paths';
</script>

<section>
    <div class="text">
        <h2>Everything You Need To Know</h2>
    </div>
    <div class="mainContainer">
        <div class="container1">
            <div class="txt2">
                <h3>World's Best Destination Guides</h3>
                <p>To inspire your next charter, we offer the largest online library of expert planning guides for all the key yachting destinations.</p>
                <div class="buttons2">
                    <button id="btn2">DISCOVER OUR GUIDES</button>
                </div>
            </div>
            <div class="img">
                <img src="{base}/img/needtoknow1.svg" alt="img">
            </div>
        </div>
        <div class="container2">
            <div class="img">
                <img src="{base}/img/needtoknow2.svg" alt="img">
            </div>
            <div class="txt1">
                <h3>World's Best Itineraries</h3>
                <p>Discover our favourite itineraries all in one place, designed from first-hand experience to make your search for the ultimate adventure in the globe’s most exclusive charter destinations simple.</p>
                <div class="buttons1">
                    <button id="btn2">OUR TOP ITINERARIES</button>
                </div>
            </div>
        </div>
        <div class="container1">
            <div class="txt2">
                <h3>Yachting Industry Memberships</h3>
                <p>We are proud members of the world's major yachting associations, granted due to our experienced brokers' unrivalled global expertise and professional excellence in the industry.</p>
                <div class="buttons2">
                    <button id="btn2">OUR MEMBERSHIP</button>
                </div>
            </div>
            <div class="img">
                <img src="{base}/img/needtoknow3.svg" alt="img">
            </div>
        </div>
        <div class="container2">
            <div class="img">
                <img src="{base}/img/needtoknow4.svg" alt="img">
            </div>
            <div class="txt1">
                <h3>Subscribe To Our Newsletter</h3>
                <p>Are you looking for inspiration? Join our mailing list for all the latest industry trends, desirable destinations and exclusive deals - straight to your inbox. </p>
                <div class="buttons1">
                    <button id="btn2">SIGN UP NOW</button>
                </div>
            </div>
        </div>
        <div class="container1">
            <div class="txt2">
                <h3>We Care About Our Oceans</h3>
                <p>The health of our oceans is central to Boatbookings. In our pursuit for a blue future we are proactively helping clients counteract the greenhouse gas impact of a yacht charter, with our Carbon Offset Calculator.</p>
                <div class="buttons2">
                    <button id="btn2">CALCULATOR</button>
                    <button id="btn3">LOW CARBON CHARTER GUIDE</button>
                </div>
            </div>
            <div class="img">
                <img src="{base}/img/needtoknow5.svg" alt="img">
            </div>
        </div>
        <div class="container2">
            <div class="img">
                <img src="{base}/img/needtoknow6.svg" alt="img">
            </div>
            <div class="txt1">
                <h3>Covid Charter Planning Advice</h3>
                <p>As the world opens up again, we have compiled an expert guide to where you can travel, providing global knowledge, industry expertise and a flexible booking process.</p>
                <div class="buttons1">
                    <button id="btn2">OUR COVID GUIDE</button>
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

    #btn3 {
        background-color: #2C84C9;
        padding: 22px, 32px, 22px, 32px;
        color: #FFFFFF;
        text-align: Center;
        line-height: 19.36px;
        font-size: 1em;
        font-weight: 600;
        font-family: "Inter", sans-serif;
        border: none;
        width: 14em;
        height: 4em;
    }

    #btn3:hover {
        background-color: #022135;
        transition: 0.5s ease;
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
            padding-left: 1px;
            display: block;
        }
    }
</style>