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

    }


    /* TIMELINE */
    .isomer-timeline-section {
        background-color: #c7212e;
	padding-top: 20px;
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
	margin-top: 5px;
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

        <section class="section story bg_gray">
            <div class="canvass">
                <div class="text-center">
                    <h1 class="main_heading2 bold">Our Heartists</h1>
                    <br><br>
                    <div class="team_grid">
                        <div class="team_card">
                            <img src="https://i.ibb.co/jTgGjSr/Shaping-Hearts-Artist-Ashley-01.jpg">
                            <a href="/ashley/">Ashley <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/hZrXVkH/Shaping-Hearts-Artist-EZRA-01.jpg">
                            <a href="/ezra/">Ezra <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/7NwkbGS/Shaping-Hearts-Artist-Henry-07.jpg">
                            <a href="/henry/">Henry <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/D7pQyBy/Shaping-Hearts-Artist-Moy-01.jpg">
                            <a href="/moy-saw-han/">Moy <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/z2xhm8f/Shaping-Hearts-Artist-Samuel.jpgg">
                            <a href="/samuel/">Samuel <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/B2SjLLT/Shaping-Hearts-Artist-Simeon-04.jpg">
                            <a href="/simeon/">Simeon <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/B4dqK81/Alex-Lim.jpg">
                            <a href="/alex-lim/">Alex Lim <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/w7GMVNX/Gary-Chong.jpg">
                            <a href="/gary-chong/">Gary Chong <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/n1HZZGc/Leong-Sijun.png">
                            <a href="/leong-sijun/">Leong Sijun <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/7gQFvV5/Ng-Jun-Yao.jpg">
                            <a href="/ng-jun-yao/">Ng Jun Yao <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/ZLg3w39/Vincent-Seet.jpg">
                            <a href="/vincent-seet/">Vincent Seet <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div class="team_card">
                            <img src="https://i.ibb.co/YRhbDcZ/randy-wah.jpg">
                            <a href="/randy-wah/">Randy Wah <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
                        </div>
                        <div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

			
			<section class="section canvas insta">
				<blockquote style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:300px; height: 550px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:300px;" data-instgrm-version="14" data-instgrm-permalink="https://www.instagram.com/reel/DAYE4lAys0b/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-captioned="" class="instagram-media"><div style="padding:16px;"> <a target="_blank" style="background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" href="https://www.instagram.com/reel/DAYE4lAys0b/?utm_source=ig_embed&amp;utm_campaign=loading"> <div style="display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg xmlns:xlink="https://www.w3.org/1999/xlink" xmlns="https://www.w3.org/2000/svg" version="1.1" viewBox="0 0 60 60" height="50px" width="50px"><g fill-rule="evenodd" fill="none" stroke-width="1" stroke="none"><g fill="#000000" transform="translate(-511.000000, -20.000000)"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style="color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;">View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style="width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style="width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style="background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style="width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a target="_blank" style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" href="https://www.instagram.com/reel/DAYE4lAys0b/?utm_source=ig_embed&amp;utm_campaign=loading">A post shared by Shaping Hearts (@shapingheartssg)</a></p></div></blockquote>
				
				<blockquote style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width: 300px; height: 550px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:300px;" data-instgrm-version="14" data-instgrm-permalink="https://www.instagram.com/reel/DA8IXeQSZ_S/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-captioned="" class="instagram-media"><div style="padding:16px;"> <a target="_blank" style="background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" href="https://www.instagram.com/reel/DA8IXeQSZ_S/?utm_source=ig_embed&amp;utm_campaign=loading"> <div style="display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg xmlns:xlink="https://www.w3.org/1999/xlink" xmlns="https://www.w3.org/2000/svg" version="1.1" viewBox="0 0 60 60" height="50px" width="50px"><g fill-rule="evenodd" fill="none" stroke-width="1" stroke="none"><g fill="#000000" transform="translate(-511.000000, -20.000000)"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style="color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;">View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style="width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style="width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style="background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style="width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a target="_blank" style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" href="https://www.instagram.com/reel/DA8IXeQSZ_S/?utm_source=ig_embed&amp;utm_campaign=loading">A post shared by Shaping Hearts (@shapingheartssg)</a></p></div></blockquote>
				
				<blockquote style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:300px; height: 550px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:300px;" data-instgrm-version="14" data-instgrm-permalink="https://www.instagram.com/reel/C_SjKlBy3Fy/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-captioned="" class="instagram-media"><div style="padding:16px;"> <a target="_blank" style="background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" href="https://www.instagram.com/reel/C_SjKlBy3Fy/?utm_source=ig_embed&amp;utm_campaign=loading"> <div style="display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg xmlns:xlink="https://www.w3.org/1999/xlink" xmlns="https://www.w3.org/2000/svg" version="1.1" viewBox="0 0 60 60" height="50px" width="50px"><g fill-rule="evenodd" fill="none" stroke-width="1" stroke="none"><g fill="#000000" transform="translate(-511.000000, -20.000000)"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style="color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;">View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style="width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style="width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style="background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style="width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a target="_blank" style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" href="https://www.instagram.com/reel/C_SjKlBy3Fy/?utm_source=ig_embed&amp;utm_campaign=loading">A post shared by Shaping Hearts (@shapingheartssg)</a></p></div></blockquote>
				
				<blockquote style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:300px; height: 550px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:300px;" data-instgrm-version="14" data-instgrm-permalink="https://www.instagram.com/reel/C-H4juGS_4G/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-captioned="" class="instagram-media"><div style="padding:16px;"> <a target="_blank" style="background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" href="https://www.instagram.com/reel/C-H4juGS_4G/?utm_source=ig_embed&amp;utm_campaign=loading"> <div style="display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg xmlns:xlink="https://www.w3.org/1999/xlink" xmlns="https://www.w3.org/2000/svg" version="1.1" viewBox="0 0 60 60" height="50px" width="50px"><g fill-rule="evenodd" fill="none" stroke-width="1" stroke="none"><g fill="#000000" transform="translate(-511.000000, -20.000000)"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style="color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;">View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style="width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style="width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style="background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style="width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a target="_blank" style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" href="https://www.instagram.com/reel/C-H4juGS_4G/?utm_source=ig_embed&amp;utm_campaign=loading">A post shared by Shaping Hearts (@shapingheartssg)</a></p></div></blockquote>

			</section>
				
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