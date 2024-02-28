<script>
	import { base } from '$app/paths';
</script>

<section>
    <div class="name">
        <h2>News From Our Blog</h2>
    </div>
    <div class="allContent">
        <div class="content">
                <img src="{base}/img/blog1.svg" alt="img">
                <div class="txt">
                    <h3>Electric Yachts are coming – and Boatbookings is offering...</h3>
                    <p>The revolution in electric yachts is happening! </p>
                    <button>READ MORE</button>
                </div>
        </div>
        <div class="content">
                <img src="{base}/img/blog2.svg" alt="img">
                <div class="txt">
                    <h3>Yacht Of The Week: MAXIMUS</h3>
                    <p>Launched in 2021, MAXIMUS is Riva’s new 100 Corsaro available for charter on the French Riviera, Sardinia and Corsica. This crewed motor yacht offers the ideal chance to charter a b... </p>
                    <button>READ MORE</button>
                </div>
        </div>
        <div class="content">
                <img src="{base}/img/blog3.svg" alt="img">
                <div class="txt">
                    <h3>MEDYS: Charter Brokers’ Choice</h3>
                    <p>The Yachts Breaking Boundaries One of Greece’s most romantic cities, Nafplio – defined by its listed architecture and majestic Venetian castles – once again set the scene for th... </p>
                    <button>READ MORE</button>
                </div>
        </div>
    </div>
</section>

<style>
    section {
        max-width: 100%;
        min-height: 100vh;
        background-color: #EEF3F4;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .name h2 {
        color: #022135;
        text-align: Center;
        letter-spacing: 2px;
        line-height: 55.44px;
        font-size: 3em;
        font-weight: 400;
        font-family: "Yeseva One", serif;
    }
    
    .allContent {
        display: flex;
        gap: 20px;
        padding-bottom: 20px;
    }

    .content img{
        width: 30vw;
        height: auto;
    }

    .txt {
        width: 27vw;
        height: auto;
    }

    .content h3 {
        color: #022135;
        font-family: "Yeseva One", sans-serif;
        font-weight: 400;
        font-size: 1.7em;
        line-height: 36.96px;
    }

    .content p {
        color: #4A5C68;
        font-family: "Inter", serif;
        font-weight: 400;
        font-size: 1em;
        line-height: 25.6px;
    }

    .content button {
        color: #022135;
        font-family: "Inter", sans-serif;
        font-weight: 600;
        font-size: 1em;
        line-height: 19.36px;
        text-align: Center;
        padding: 22px, 32px, 22px, 32px;
        height: 8vh;
        width: 20vw;
        background-color: transparent;
        border: 1px solid black;
    }

    .content button:hover {
        background-color: #022135;
        color: white;
        transition: 0.4s ease;
    }

    @media only screen and (max-width: 700px){
        .content h3 {
        font-size: 1em;
        line-height: 28px;
        }
        .content p {
            font-size: 0.8em;
        }
        .name h2 {
            font-size: 2em;
        }
    }

    @media only screen and (max-width: 500px){ 
        .content img {
            display: none;
        }
        .txt h3 {
            font-size: 0.8em;
        }
        
        .txt {
            justify-content: center;
            text-align: center;
        }
        .txt button {
            font-size: 0.7em;
        }
    }
</style>