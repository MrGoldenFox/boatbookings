<section>
    <main>
        <div class="destinationContainer">
            <h3>Mediterranean</h3>
            <img src={"/img/destination1_1.svg"} alt="destination1">
            <a href="">French Riviera</a>
            <a href="">Corsica</a>
            <a href="">Greece</a>
            <a href="">Spain</a>
            <a href="">Croatia<br></a>
            <a href="">Amalfi Coast</a>
            <a href="">Sardinia</a>
            <a href="">Sicily</a>
        </div>
        <div class="destinationContainer">
            <h3>Florida</h3>
            <img src={"/img/destination1_2.svg"} alt="destination1">
            <a href="">BVI</a>
            <a href="">US Virgin Islands</a>
            <a href="">Bahamas</a>
            <a href="">Florida</a>
            <a href="">St Barts<br></a>
            <a href="">St Martin</a>
            <a href="">St Vincent and the Grenadines</a>
        </div>
        <div class="destinationContainer">
            <h3>Asia Pacific</h3>
            <img src={"/img/destination1_3.svg"} alt="destination1">
            <a href="">Phuket</a>
            <a href="">Thailand</a>
            <a href="">Singapore</a>
            <a href="">Tahiti</a>
            <a href="">Fiji</a>
            <a href="">Indonesia<br></a>
            <a href="">New Caledonia</a>
            <a href="">Australia</a>
        </div>
    </main>
    <div class="btn-dest">
        <button>See all of our charter destinations</button>
    </div>
</section>    

<style>
    main {
        width: 100%;
        min-height: 75vh;
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 20px;
    }

    .destinationContainer {
        width: 30vw;
    }

    .destinationContainer h3 {
        text-align: center;
        color: #022135;
        font-family: "Yeseva One", sans-serif;
        font-weight: 400;
        font-size: 4vw;
        line-height: 36.96px;
    }

    .destinationContainer img {
        width:100%;
        height: 30vh;
        object-fit:cover;
        object-position:50% 50%;
    }

    .destinationContainer a:hover {
        text-decoration: underline;
    }

    .btn-dest {
        width: 100%;
        display: flex;
        justify-content: center;
        position: relative;
        min-height: 10vh;
        padding-block: 20px;
    }

    .btn-dest button {
        border: #022135 1px solid;
        padding: 22px, 32px, 22px, 32px;
        gap: 10px;
        width: 45vw;
        height: 10vh;
        background-color: transparent;
        color: #022135;
        text-align: Center;
        line-height: 19.36px;
        font-size: 2vw;
        font-weight: 600;
        font-family: "Inter", sans-serif;
    }

    main a {
        color: #000000;
        font-family: "Inter", sans-serif;
        font-weight: 400;
        font-size: 1em;
        text-decoration: none;
        padding-right: 20px;
    }

    .btn-dest button:hover {
        background-color: #022135;
        color: white;
        transition: 1s ease;
    }

    @media only screen and (max-width: 800px){
        .btn-dest button {
            width: 40vw;
            font-size: 3vw;
        }
    }

    @media only screen and (max-width: 500px){
        main a {
            text-align: center;
            font-size: 0.7em;
        }
        .destinationContainer {
            text-align: center;
        }
    }   
</style>