---
title: About Shaping Hearts
permalink: /about-shaping-hearts/
variant: markdown
description: ""
---
<style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');

    * {
        margin: 0%;
        padding: 0;
        box-sizing: border-box;
        font-family: "Inter", sans-serif;
    }

    html {
        width: 100% !important;
    }

    body {
        overflow-x: hidden;
    }

    .col.is-offset-2,
    .col.is-offset-2-tablet {
        margin-left: 0% !important;
        width: 100% !important;
    }

    .content h1,
    .content h2,
    .content h3,
    .content h4,
    .content h5 {
        color: black !important;
    }

    .hero {
        display: flex;
        display: none;
        margin-top: -20px !important;
        height: 100vh;
        justify-content: center;
        align-items: center;
        position: relative;
        width: 100%;
        overflow: hidden;
        padding: 20px;
        background: url("https://i.ibb.co/BznXQFQ/Homepage-1.png") no-repeat;
        background-position: center;
    }

    .bp-section-pagetitle {
        display: none;
    }

    .bp-section {
        padding: 0px
    }


    .hero .canvas {
        height: 80vh;
    }

    .relative {
        position: relative;
    }

    .hero_img,
    .event_bg,
    .story_bg,
    .sponsors_bg {
        position: absolute;
        height: 100%;
        left: 0%;
        width: 100%;
        top: 0;
    }

    .hero .text {
        font-weight: bold;
        z-index: 32;
        color: #f5acbe !important;
    }

    .left {
        position: absolute;
        left: 0;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        top: 0;
    }

    .right {
        position: absolute;
        right: 0;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        top: 0;
    }

    .find {
        font-size: 5.5rem;
    }

    .art {
        font-size: 5.5rem;
    }

    .in {
        font-size: 5.5rem;
    }

    .meaning {
        font-size: 5.5rem;
    }

    .center-text {
        transform: translateY(-50%);
        font-size: 1.2rem;
        font-weight: bold;
        color: black;
        font-weight: normal;
    }


    /* 2nd section EVents */
    .events {
        height: 100%;
        width: 100%;
        background: #c5242f;
    }

    .events_flex {
        display: flex;
        justify-content: space-between;
        position: relative;
    }

    .events .event_left {
        width: 34%;
        z-index: 3000;
    }

    .bp-container {
        width: 100% !important;
        max-width: 100% !important;
        padding: 0px !important;
    }

    .has-float-btns {
        display: none;
    }

    .event_left p {
        font-size: 1.1rem;
        margin-top: 5px;
        color: white;
    }

    .events .event_right {
        width: 48%;
    }

    .events .secondimg {
        margin-top: -10px;
    }

    .events h1 {
        color: white !important;
    }

    .events .button {
        border: none !important;
    }

    /* Story */
    .story {
        background: #f5f0e7 !important;
    }

    .story .canvas {
        width: 80%;
    }

    .story_grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 16px;
    }

    .story_card h1 {
        font-size: 3rem;
        color: #c5242f;
        font-weight: bold;
        margin: 0px;
    }

    .story p {
        font-size: 1.1rem;
        margin: 0px;
    }

    /*Video */
    VideoPlayer {
        padding: 30px 0px;
        align-items: center;
        justify-content: center;
    }

    .VideoPlayer iframe {
        width: 100% !important;
        min-height: 70vh !important;
    }

    .hero_center {
        width: 65%;
        margin-left: auto;
        margin-right: auto;
        padding-top: 50px;
        padding-bottom: 50px;
        position: relative;
        z-index: 3000;
    }

    .col.is-offset-2,
    .col.is-offset-2-tablet {
        margin-left: 0% !important;
        width: 100% !important;
    }

    .hero_right img {
        width: 45%;
    }

    /* Sponsors */
    .sponsors .canvas {
        width: 70%;
    }

    .button a {
        color: #ffffff;
        text-decoration: none;
    }

    .sponsors .sponsors_grid {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        grid-column-gap: 80px;
        grid-row-gap: 40px;
    }

    .sponsors h3 {
        color: #c5242f !important;
        font-weight: bold
    }

    .sponsors h2 {
        margin-top: 3.75rem !important;
        margin-bottom: 0.75rem;
        font-size: 18px;
        font-weight: bold;
    }

    .sponsors_grid img {
        width: 150px;
        font-weight: bold;
        border-radius: 2px;
        margin: 0 !important;
    }

    .navbar .bp-container {
        width: 1280px !important;
        max-width: 1280px !important;
    }

    /* STORY */
    .story {
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 20px;
    }

    .story .canvass {
        width: 80%;
    }

    .team_grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 25px;
        width: 95%;
        margin: auto;
    }

    .team_grid .arrow {
        font-size: 1.2rem;
        margin-left: auto;
        height: 35px;
        width: 35px;
        border-radius: 50%;
        position: absolute;
        bottom: 20px;
        right: 20px;
    }

    .team_card {
        position: relative;
    }

    .team_card img {
        width: 100% !important;
        border-radius: 15px;
        margin: 0 !important;
    }

    .team_card a {
        position: absolute;
        bottom: 0%;
        left: 0%;
        margin-bottom: 0%;
        width: 100%;
        color: white !important;
        text-decoration: none !important;
        background: #97002b !important;
        padding: 10px 20px;
        text-transform: uppercase;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    /* General */
    body .canvas {
        width: 1280px !important;
        max-width: 1280px !important;
        margin-left: auto;
        margin-right: auto;
    }

    .relative {
        position: relative;
    }

    .text-end {
        text-align: end;
    }

    .text-center {
        text-align: center;
    }

    .main_heading {
        font-size: 3.5rem;
        line-height: 1.4;
        font-weight: bold;
    }

    .main_heading2 {
        font-size: 3rem;
        font-weight: bold;
    }

    .section {
        padding: 70px 0px;
    }

    .button {
        background: #e0125b;
        border: none !important;
        border-radius: 20px;
        padding: 12.5px 30px;
        width: 45%;
        transition: 0.2s all ease;
        cursor: pointer;
        text-decoration: none;
        color: black;
    }

    .button:hover {
        background: #f04a38 !important;
        color: white !important;
    }

    .button:hover a {
        color: white !important;
    }

    .flex {
        display: flex;
    }

    .justify-between {
        justify-content: space-between;
    }

    .bold {
        font-weight: bold;
    }

    .mt-5 {
        margin-top: 20px;
    }

    .bg_gray {
        background-color: rgba(244, 244, 244, 1);
    }

    .text-gray {
        color: rgb(78, 78, 78);
    }


    @media (max-width: 1280px) {
        .bp-container {
            width: 100% !important;
        }
    }


    @media (max-width: 1280px) {
        .navbar .bp-container {
            width: 100% !important;
            max-width: 100% !important;
        }
    }

    @media (max-width: 700px) {
body	.insta{
	justify-content: center !important;
	}
        .sponsors .sponsors_grid {
            grid-row-gap: 30px;
        }

        .VideoPlayer iframe {
            min-height: auto !important;
        }

        .hero {
            background: none;
        }

        .section {
            padding: 50px 0px;
        }

        .faqs_left,
        .faqs_right {
            width: 100%;
            max-width: 100%;
            text-align: center;
        }

        .faqs_left img {
            width: 100%;
        }

        .button {
            padding: 12.5px 20px;
        }

        body .canvas {
            width: 90% !important;
        }

        .events_flex {
            flex-direction: column-reverse;
        }

        .event_right,
        .event_left {
            width: 100% !important;
        }

        .main_heading {
            font-size: 3rem;
            line-height: normal;
        }

        .hero {
            min-height: 89vh;
            padding: 20px 10px;
        }

        .hero .canvas {
            height: auto;
        }

        .left {
            position: static;
            height: 100%;
            display: block;
        }

        .right {
            position: static;
            height: 100%;
            display: block;
        }

        .art {
            text-align: start;
        }

        .meaning,
        .art,
        .in,
        .find {
            font-size: 4rem;
        }

        .center-text {
            transform: translateY(0%);
            font-size: 1.2rem;
        }

        .main_heading {
            font-size: 2.5rem;
        }

        .main_heading2 {
            font-size: 2rem;
        }
.isomer-timeline-section{
	padding: 20px !important;
	}
    }


    /* TIMELINE */
    .isomer-timeline-section {
        background-color: #c7212e;
	padding: 20px 0px 30px 0px ;
    }

    body .content .isomer-timeline-section .timeline-title {
        text-align: center;
        margin-bottom: 20px;
        font-size: 36px;
        color: white !important;
		width: 90%;
	margin: auto;
    }

    body .content .isomer-timeline-section .isomer-timeline .timeline-title {
        text-align: start;
        margin-bottom: 0px
        font-size: 22px;
        color: white !important;
    }
    .isomer-timeline{
        margin-top: 10px !important;
    }
	.timeline-desc{
	color: white;
	width: 90%;
	margin: auto;
	margin-top: 5px !important;
	}
	
	.insta{
	display: flex;
	justify-content: space-between;
	flex-wrap: wrap;
	align-items: center;
	gap:  20px;
	}
	.insta iframe{
	width: 300px !important;
	min-width: 300px !important;
	}
</style>
<section>
    <section class="hero">
        <div class="canvas relative">
            <div class="hero_box">
                <div class="left">
                    <h1 class="text find">FIND</h1>
                    <p class="center-text">
                        Meaningful Art<br>
                        Made by Artists<br>
                        With Disabilities
                    </p>
                    <div class="text in">IN</div>
                </div>
                <div class="right">
                    <h1 class="text art text-end">ART</h1>
                    <h1 class="text meaning">MEANING</h1>
                </div>
            </div>
        </div>
    </section>

    <section style="z-index: 4000; position: relative;" class="events">
        <div class="events_flex canvas">
            <div class="event_left mt-5 section">
                <h1 class="main_heading">
                    SINGAPORE'S LARGEST<br>
                    INCLUSIVE<br>
                    ARTS FESTIVAL
                </h1>
                <p>What gives art meaning? Is it the artist behind the art? Is it the way it’s created? Or is it
                    meaningful because it speaks to you? Sometimes, we don’t need to find meaning in art - it’s already
                    there.</p>
                <div class="flex justify-between mt-5">
                    <button class="button bold"><a target="_blank" href="https://shop.shapinghearts.sg/">Shop</a></button>
									     <button class="button bold"><a target="_blank" href="https://shapinghearts.cdc.gov.sg/art-exhibition/">Visit Event</a></button>
                </div>
            </div>
            <div style="z-index: 4000; position: relative;" class="event_right section">
                <img style="width: 100%;  display: block;" src="https://i.ibb.co/FBZbLTf/Homepage-Header-Image.png">
            </div>
        </div>
    </section>

    <section class="story relative">
        <div style="z-index: 4000; position: relative;" class="canvas section">
            <div class="text-center">
                <p class="text-center bold">FOLLOW OUR HEARTS</p>
                <h1 class="main_heading2 text-center mt-5">Step into the world of talented artists with disabilities and
                    be awed by their art creations at the largest inclusive arts event!</h1>
                <button style="width: fit-content; background: #e0125b;" class="button bold mt-5">
                    <a target="_blank" href="https://shop.shapinghearts.sg/">Visit Shop</a></button>
                <br>
                <br>

                <div class="story_grid mt-5">
                    <div class="story_card">
                        <p class="text-gray">Over</p>
                        <h1>200</h1>
                        <p class="text-gray">
                            artists
                        </p>
                    </div>
                    <div class="story_card">
                        <p class="text-gray">More than</p>
                        <h1>500</h1>
                        <p class="text-gray">
                            paintings
                        </p>
                    </div>
                    <div class="story_card">
                        <p class="text-gray">Over</p>
                        <h1>30</h1>
                        <p class="text-gray">
                            SSAs and agencies
                        </p>
                    </div>
                    <div class="story_card">
                        <p class="text-gray">More than</p>
                        <h1>4 million</h1>
                        <p class="text-gray">
                            public engagements
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="VideoPlayer relative">
            <div class="hero_center">
                <iframe allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowfullscreen="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden" height="314" width="560" src="https://www.facebook.com/plugins/video.php?height=314&amp;href=https%3A%2F%2Fwww.facebook.com%2FNECDC%2Fvideos%2F246726828232464%2F&amp;show_text=false&amp;width=560&amp;t=0"></iframe>
            </div>
        </div>				
        <section class="sponsors relative">

            <div style="z-index: 4000; position: relative;" class="canvas section">
                <h1 class="main_heading2 bold text-center">Our Sponsors</h1>
                <br><br>
                <div class="text-center mt-5">
                    <h3>PLATINUM ELITE</h3>
                    <div class="sponsors_grid mt-5">
                        <img src="https://i.ibb.co/M2RJnK2/Neo-Group-Logo.png">
                    </div>
                </div>
                <br><br>
                <div class="text-center mt-5">
                    <h3>PLATINUM</h3>
                    <div class="sponsors_grid mt-5">
                        <img src="https://i.ibb.co/z6V9cRD/Logo-Sg-Pools-4-C-Hi-Res-Horizontal.jpg">
                    </div>
                </div>
                <br><br>
                <div class="text-center mt-5">
                    <h3>GOLD</h3>
                    <div class="sponsors_grid mt-5">
                        <img src="https://i.ibb.co/sQMB8Ny/SJ-Lockup-RGB-Blue.png">
                        <img src="https://i.ibb.co/2859Xy9/rigel.png">
                    </div>
                </div>
                <br><br>
                <div class="text-center mt-5">
                    <h3>SILVER</h3><br>
                    <div class="sponsors_grid">
                        <img src="https://i.ibb.co/JH1k3qJ/IMG-3520.png">
                    </div>
                    <div class="text-center mt-5">
                        <h3>BRONZE</h3><br>
                        <div class="sponsors_grid">
                            <img src="https://i.ibb.co/QMDJ9D4/Builders-Mart-Logo-DEC-2011.png">
                            <img src="https://i.ibb.co/XJNP4QL/BRONZE-GIIS-logo.jpg">
                            <img src="https://i.ibb.co/ZGF4vQx/KKPL.png">
                            <img src="https://i.ibb.co/CV8KMmJ/serial.png">
                        </div>
                        <br>
                        <div class="text-center mt-5">
                            <div class="sponsors_grid">
                                <img src="https://i.ibb.co/jLnvwrD/P-G-Logo.png">
                                <img src="https://i.ibb.co/VC4ddDz/UTAC-Logo.png">
                            </div>
                        </div>
                        <br>
                        <div class="text-center mt-5">
                            <div class="sponsors_grid">
                                <h2><span style="color:#000; font-size:18px">Dr Doreen Tan, PBM</span></h2>
                                <h2><span style="color:#000; font-size:18px">Jason Tang</span></h2>
                                <h2><span style="color:#000; font-size:18px">Stephen Lee Ching Yen</span></h2>
                            </div>
                        </div>
                        <br><br>
                        <div class="text-center mt-5">
                            <h3>TECH SPONSOR</h3>
                            <div class="sponsors_grid mt-5">
                                <img src="https://i.ibb.co/0rHJmvX/Avertek-Enterprises-Pte-Ltd.png">
                                <img src="https://i.ibb.co/BVf1PH6/HW-POS-CMYK-Horizontal-300ppi.jpg">
                            </div>
                        </div>
											<div class="text-center mt-5">
                            <h3>ART ADVOCATES</h3>
                            <div class="sponsors_grid mt-5">
                                <img src="https://i.ibb.co/k3K4QZQ/Appliedlogo-blue-102021-002.png">
                                <img src="https://i.ibb.co/HP8t2rr/SSIA-Logo-CMYK-002.jpg">
                            </div>
                        </div>
											
											<br>
												<div class="text-center mt-5">
                            <h3>SUPPORTING PARTNERS</h3>
                            <div class="sponsors_grid mt-5">
                                <img src="https://i.ibb.co/T2X587q/Buangkok-CCMC-1.png">
                                <img src="https://i.ibb.co/wMZcjh9/Central-CDC-Logo.png">
															 <img src="https://i.ibb.co/VwrfxzK/North-West-CDC-Logo.jpg">
																	 <img src="https://i.ibb.co/YjtwKby/SMRT-Trains-Logo200-Pantone-180205-01-01.png">
																 <img src="https://i.ibb.co/m57HM19/South-East-CDC-Logo.jpg">
																	 <img src="https://i.ibb.co/cr63yc8/South-West-Logo.jpg">
																	 <img src="https://i.ibb.co/xsLpn5r/Stellar-Ace-logo.png">
																 <img src="https://i.ibb.co/F5FRwbB/Temasek-Polytechnic.png">
                            </div>
                        </div>
											
                        <br>
                    </div>
                </div>
            </div>
        </section>
    </section>

    <section class="isomer-timeline-section">
        <h1 class="timeline-title">Growth of Shaping Hearts</h1>
        <p class="timeline-desc" style="text-align: center;">
            Initiated by North East CDC in 2019, Shaping Hearts was envisioned as an annual platform where persons with disabilities could build their future through art. Each artwork represents a step towards independence and recognition, showcasing talents that might otherwise go unnoticed. As Shaping Hearts has grown, so has our community's understanding of inclusion. We're creating a space in Singapore where art opens doors, improves lives, and enables everyone to contribute. Today, Shaping Hearts is Singapore's largest inclusive arts festival.
        </p>

        <br>
        <div class="isomer-timeline">
            <img alt="" style="margin: auto; display: block; width: fit-content" src="https://i.ibb.co/dbgJdJP/timeline-ske.png">
        </div>
    </section>

</section>