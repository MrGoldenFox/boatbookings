<section>
    <div class="name">
        <h2>Our Top Rated Yachts</h2>
        <p>AS REATED BY OUR CHARTER CLIENTS</p>
    </div>
    <div class="allContent">
        <div class="content">
            <img src={"/img/top1.svg"} alt="img">
            <div class="text">
                <h3>ANNE MARIE</h3>
                <img src={"/img/stars.svg"} alt="">
                <p>CLIENT REVIEW</p>
                <h6>Great choice from Boatbookings. Memorable holiday, everything was amazing.</h6>
                <button>CHECK OUT THIS YACHT</button>
            </div>
        </div>
        <div class="content">
            <img src={"/img/top2.svg"} alt="">
            <div class="text">
                <h3>PLAYTIME</h3>
                <img src={"/img/stars.svg"} alt="">
                <p>CLIENT REVIEW</p>
                <h6>We just left Playtime and said goodbye to Mario and Karine. We had an amazing time. I am so thankful you found me the boat on such short notice! We got very lucky. You were correct that Mario and ...</h6>
                <button>CHECK OUT THIS YACHT</button>
            </div>
        </div>
        <div class="content">
            <img src={"/img/top3.svg"} alt="img">
            <div class="text">
                <h3>VALERE</h3>
                <img src={"/img/stars.svg"} alt="">
                <p>CLIENT REVIEW</p>
                <h6>I do not think I have ever had a better charter (we have done eight).
                    The boat was in great shape, the crew from Ryan down was fantastic -- professional, nice and very service oriented. And that i...</h6>
                <button>CHECK OUT THIS YACHT</button>
            </div>
        </div>
        <div class="content">
            <img src={'/img/top4.svg'} alt="img">
            <div class="text">
                <h3>MALA</h3>
                <img src={"/img/stars.svg"} alt="">
                <p>CLIENT REVIEW</p>
                <h6>We had a great time on Mala exploring the Dalmatian coast.
                    Everything is great: the catamaran`s condition, Sanja, Zoki’s dedication, and the food we are having. Thanks for everything Boatbookings! ...</h6>
                <button>CHECK OUT THIS YACHT</button>
            </div>
        </div>
        <div class="content">
            <img src={"/img/top5.svg"} alt="img">
            <div class="text">
                <h3>Blade 6</h3>
                <img src={"/img/stars.svg"} alt="">
                <p>CLIENT REVIEW</p>
                <h6>The kids (5 of them) loved the crew and all the different water toys! Visited beautiful areas - the Captain knew how to keep us wowed!</h6>
                <button>CHECK OUT THIS YACHT</button>
            </div>
        </div>
    </div>
    <div class="btn">
        <button>See all of our top rated yachts</button>
    </div>
</section>

<style>
    .name {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .name h2 {
        color: #022135;
        font-family: "Yeseva One", sans-serif;
        font-weight: 400;
        font-size: 3em;
        letter-spacing: 2px;
        text-align: center;
        min-height: 1vh;
    }

    .name p {
        color: #4A5C68;
        font-family: "Inter", sans-serif;
        font-size: 1.4em;
        line-height: 29.05px;
        text-align: center;
    }

    .allContent {
        display: flex;
        gap: 10px;
        overflow-x: auto;
        padding-inline: 10px;
    }

    .content {
        padding-bottom: 5vw;
    }

    .content h3 {
        color: #022135;
        height: 3vh;
        font-size: 2em;
        font-weight: 400;
        font-family: "Yeseva One", sans-serif;
    }

    .content p {
        color: #022135;
        letter-spacing: 2px;
        line-height: 24px;
        font-size: 0.6em;
        font-weight: 600;
        font-family: "Inter", sans-serif;
        height: 1vh;
    }

    .content h6 {
        color: #4A5C68;
        font-family: "Inter", sans-serif;
        font-weight: 400;
        font-style: italic;
        font-size: 0.9em;
    }

    .content button {
        background-color: #2C84C9;
        padding: 22px, 32px, 22px, 32px;
        height: 8vh;
        width: 15vw;
        color: white;
        border: none;
        font-weight: 600;
    }

    .content button:hover {
        background-color: #022135;
        transition: 0.4s ease;
    }

    .btn {
        padding-bottom: 50px;
        display: flex;
        justify-content: center;
    }

    .btn button {
        background-color: transparent;
        border: 1px solid black;
        height: 8vh;
        width: 30vw;
        font-family: "Inter", serif;
        font-weight: 600;
        font-size: 1em;
        line-height: 19.36px;
        text-align: center;
    }

    .btn button:hover {
        background-color: #022135;
        color: white;
        transition: 0.4s ease;
    }

    @media only screen and (max-width: 700px){
        .content button {
            width: 35vw;
            height: 8vh;
        }
    }

    @media only screen and (max-width: 500px) {
        .btn button {
            width: 60vw;
        }
    }
</style>