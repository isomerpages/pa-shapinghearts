---
title: Partners
permalink: /partners/
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

        .hero {
            margin-top: 10vh;
            border-top: 1.99px solid rgba(0, 0, 0, 0.7);
            min-height: 60vh;
        }

        .hero .canvas {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 40px 0px;
        }

        .hero_left,
        .hero_right {
            width: 45%;
        }

        .hero_right{
            text-align: end;
        }

        .hero_right img{
            width: 90%;
        }

        .hero_left h1 {
            font-size: 2rem;
        }

        .hero_left p {
            margin-top: 10px;
        }

        /* HEARTS */
        .hearts_grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 40px;
        }

        .heart_card p:last-child {
            color: rgb(85, 85, 85);
        }

        .heart_card img {
            width: 100%;
            border-top-left-radius: 25px;
            border-bottom-right-radius: 25px;

        }

        /* Partners */
        .partners_grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
        }

        .partner_card {
            box-shadow: 0px 0px 10px 1px gainsboro;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            border-radius: 15px;
            height: 200px;
        }

        .partner_card img {
            width: 30%;
        }


        /* General */
        .canvas {
            width: 88%;
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
        }

        .main_heading2 {
            font-size: 3rem;
        }

        .section {
            padding: 100px 0px;
        }

        .button {
            background: transparent;
            border: 1.99px solid rgba(0, 0, 0, 1);
            border-radius: 20px;
            padding: 12.5px 30px;
            width: 45%;
            transition: 0.2s all ease;
            cursor: pointer;
        }

        .button:hover {
            background: black;
            color: white;
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


        .flex-wrap{
            flex-wrap: wrap;
        }

        /* FAQS */
        .FAQS .canvas {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .faqs_left,
        .faqs_right {
            width: 45%;
        }

        .faq-container {
            width: 100%;
            margin: auto;
            padding: 20px;
        }

        .faq {
            border-bottom: 1px solid #ccc;
            padding: 15px 0;
            margin-top: 20px;
        }

        .faq-question {
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0px;
            font-weight: 600;
            font-size: 1.1rem;
        }

        .faq-answer {
            display: none;
            margin-top: 10px;
            color: #555;
        }

        .faq-question::after {
            content: '▼';
            font-size: 12px;
            transform: rotate(0deg);
            transition: transform 0.3s ease;
        }

        .faq-question.active::after {
            transform: rotate(180deg);
        }



        /* youtube_section */
        .youtube_section {
            border-top: 2px solid gainsboro;
            border-bottom: 1.99px solid black;
            min-height: 100vh;
        }

        @media (max-width: 800px) {

            .faqs_left,
            .faqs_right {
                width: 100%;
                text-align: center;
            }

            .faqs_left img {
                width: 100%;
            }

            .hero .canvas {
                flex-direction: column-reverse;
            }

            .hero_left {
                margin-top: 30px;
                width: 100%;
            }

            .hero_right {
                width: 100%;
            }

            .hero_right img {
                width: 100%;
            }

            .youtubeVid{
                width: 100% !important;
            }
        }
    </style>
	
<section>
    <section class="hero">
        <div class="canvas relative">
            <div class="hero_left">
                <h1>Lorem ipsum dolor sit amet, consectetur adipiscing eli</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem
                    ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut</p>
            </div>
            <div class="hero_right">
                <img src="./assets/event.png">
            </div>
        </div>
    </section>

    <section class="section">
        <div class="canvas">
            <h1 class="main_heading2">Our Heartists</h1>
            <br>
            <div class="hearts_grid">
                <div class="heart_card">
                    <img src="./assets/user1.png">
                    <p class="bold mt-5">Mawell Rebarber</p>
                    <br>
                    <p class="desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor</p>
                </div>

                <div class="heart_card">
                    <img src="./assets/user2.jpg">
                    <p class="bold mt-5">Mawell Rebarber</p>
                    <br>
                    <p class="desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor</p>
                </div>
                <div class="heart_card">
                    <img src="./assets/user3.png">
                    <p class="bold mt-5">Mawell Rebarber</p>
                    <br>
                    <p class="desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor</p>
                </div>
                <div class="heart_card">
                    <img src="./assets/user4.png">
                    <p class="bold mt-5">Mawell Rebarber</p>
                    <br>
                    <p class="desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor</p>
                </div>
                <div class="heart_card">
                    <img src="./assets/user5.png">
                    <p class="bold mt-5">Mawell Rebarber</p>
                    <br>
                    <p class="desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor</p>
                </div>
                <div class="heart_card">
                    <img src="./assets/user6.png">
                    <p class="bold mt-5">Mawell Rebarber</p>
                    <br>
                    <p class="desc">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor</p>
                </div>

                
            </div>

        </div>
    </section>


    
    <section class="section bg_gray youtube_section">
        <div class="canvas">
            <h1 class="main_heading2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
            </h1>
            <br>

            <div class="flex mt-5 justify-between  flex-wrap">
                <iframe class="youtubeVid" allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/v1v_jBPOJWQ?si=tFRSp9q9D90agi2C" height="315" width="280"></iframe>
                <iframe class="youtubeVid" allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/QTB1YiWxxKU?si=oBYIdMSIW7YnQ6LW" height="315" width="280"></iframe>
                <iframe class="youtubeVid" allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/v1v_jBPOJWQ?si=tFRSp9q9D90agi2C" height="315" width="280"></iframe>
                <iframe class="youtubeVid" allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/QTB1YiWxxKU?si=oBYIdMSIW7YnQ6LW" height="315" width="280"></iframe>
            </div>
        </div>
    </section>

    
    <section class="section partners">
        <div class="canvas">
            <h1 class="main_heading2">Our Partners</h1>
            <br>
            <div class="partners_grid mt-5">
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
                <div class="partner_card">
                    <img src="https://freepnglogo.com/images/all_img/1697562980facebook-logo-transparent.png">
                </div>
            </div>
        </div>
    </section>

    
    <section class="section bg_gray mt-5 FAQS">
        <div class="canvas">
            <div class="faqs_left">
                <p class="bold">LOREM IPSUM dolor</p>
                <h1 class="bold mt-5">
                    Lorem ipsum dolor sit amet adipiscing elit,
                </h1>
                <br>
                <img class="mt-5" src="./assets/event.png">
            </div>
            <div class="faqs_right">
                <div class="faq-container">
                    <div class="faq">
                        <div class="faq-question">
                            Add commonly asked questions here
                        </div>
                        <div class="faq-answer">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ut lorem qui Nullam ut lorem
                            qui.
                        </div>
                    </div>
                    <div class="faq">
                        <div class="faq-question">
                            Add commonly asked questions here
                        </div>
                        <div class="faq-answer">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ut lorem qui Nullam ut lorem
                            qui.
                        </div>
                    </div>
                    <div class="faq">
                        <div class="faq-question">
                            Add commonly asked questions here
                        </div>
                        <div class="faq-answer">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ut lorem qui Nullam ut lorem
                            qui.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</section>