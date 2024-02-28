<section>
    <div class="mainWindow"></div>
    <div class="txt">
        <p>Click on the highlighted areas to see our yachts in the location you desire </p>
    </div>
</section>

<style>
    .mainWindow {
        height: 100vh;
        width: 100%;
        background-image: url("/img/map.svg");
        background-size: cover;
    }
    .txt {
        background-color: #2C84C9;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 5vh;
        color: white;
        padding-bottom: 8vh;
    }
    .txt p {
        font-family: "Inter", sans-serif;
        font-weight: 400;
        font-size: 0.9em;
        list-style: 24px;
        text-align: center;        
    }
    
    @media only screen and (max-width: 1200px){
        section {
            display: none;
        }
    }
</style>