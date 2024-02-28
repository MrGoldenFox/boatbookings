<script>
	import { base } from '$app/paths';
</script>

<section>
    <div class="logo">
        <img src='{base}/img/Logo.svg' alt="Logo">
    </div>
    <div class="feedback">
        <img src="{base}/img/stars.svg" alt="stars">
        <p>Rating: 4.9 / 5 calculated on 1037 reviews</p>
        <a href="">See all of our client reviews</a>
    </div>
    <div class="contacts">
        <div class="numbers">
            <div class="number">
                <p>London +44 (0)20 7193 5450</p>
                <p>French Riviera +33 (0)9 70 46 39 79</p>
            </div>
            <div class="number">
                <p>Ft Lauderdale +1 954 892 5009</p>
                <p>USA +1 954 892 5009</p>
            </div>
            <div class="gmail">
                <p>General Email Contact:</p>
                <p>charter@boatbookings.com</p>
            </div>
        </div>
        <div class="other">
            <p>© Copyright 2022 Boatbookings</p>
            <p>T's and C's</p>
            <p>FAQ</p>
            <p>Site Map</p>
            <p>How to use</p>
            <p>Useful links</p>
            <p>Testimonials</p>
            <p>Press</p>
            <p>About Us</p>
        </div>
    </div>
</section>

<style>
    section {
        padding-block: 20px;
        color: white;
        min-height: 70vh;
        width: 100%;
        background-color: #000000;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
        gap: 40px;
    }

    .numbers {
        display: flex;
        gap: 40px;
        justify-content: center;
        text-align: left;
    }

    .other {
        padding-top: 100px;
        display: flex;
        gap: 20px;
        justify-content: center;
    }

    .logo img {
        width: 350px;
        height: auto;
    }

    .feedback p {
        color: #BBBBBB;
        font-family: "Inter", sans-serif;
        font-weight: 400;
        font-size: 1.2em;
        line-height: 24.2px;
    }

    .feedback a {
        font-family: "Inter", sans-serif;
        font-weight: 600;
        font-size: 1.1em;
        line-height: 21.78px;
        text-align: center;
        color: #EEF3F4;
        text-decoration: none;
    }

    .feedback a:hover {
        text-decoration: underline;
    }

    .number p {
        font-family: "Inter", sans-serif;
        font-weight: 400;
        font-size: 1em;
        line-height: 19.36px;
        text-align: left;
        color: #EEF3F4;
    }

    .other p {
        font-family: "Inter", sans-serif;
        font-weight: 400;
        font-size: 0.9em;
        line-height: 16.94px;
        text-align: center;
        color: #BBBBBB;
    }

    @media only screen and (max-width: 900px){
        .other {
            display: none;
        }
    }

    @media only screen and (max-width: 550px){
        .numbers {
            flex-direction: column;
        }
        
        .logo img {
            width: calc(100% - 1px);
        }
    }
</style>