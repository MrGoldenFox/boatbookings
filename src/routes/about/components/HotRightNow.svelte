<script>
	import { base } from '$app/paths';
</script>

<section style:background-image = "url('{base}/img/hot_background.svg')">
    <div class="name">
        <h2>What's HOT Right Now!</h2>
    </div>
    <div class="allContents">
        <div class="content">
            <a href="">> Luxury Yachts for Capri and Amalfi Coast</a><br>
            <a href="">> French Riviera Crewed Motor Yachts</a><br>
            <a href="">> Luxury Yacht Charters around Sardinia</a><br>
            <a href="">> Discover Croatia and Montenegro</a><br>
            <a href="">> BVI Crewed Catamaran Charters</a>
        </div>
        <div class="content">
            <a href="">> Sail around the Greek Islands!</a><br>
            <a href="">> Spring Break in the Bahamas</a><br>
            <a href="">> Crewed Catamarans and Tahiti Yacht Charters</a><br>
            <a href="">> See our Cannes Day Charter Yachts</a><br>
            <a href="">> Luxury Bahamas Motor Yachts</a>
        </div>
    </div>
</section>

<style>
    section {
        min-height: 50vh;
        width: 100%;
        position: absolute;
        background-size: cover;
        padding-top: 10px;
    }

    .name {
        color: white;
        font-family: "Yeseva One", serif;
        font-weight: 300;
        font-size: 1.5em;
        line-height: 55.44px;
        letter-spacing: 2px;
        text-align: Center;
    }

    .allContents {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 50px;
    }

    .content {
        line-height: 30px;
        max-width: 350px;
    }

    .content a {
        color: white;
        text-decoration: none;
    }

    .content a:hover {
        text-decoration: underline;
    }
</style>