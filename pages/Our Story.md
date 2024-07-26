---
title: Our Story
permalink: /our-story/
variant: markdown
description: ""
---
### **Our Story**

1. Interdum et malesuada fames ac ante ipsum primis in faucibus. In sagittis ut nisl eget suscipit. Morbi lorem ligula, tincidunt et viverra et, gravida sit amet velit. Duis posuere mi lectus, molestie viverra metus consectetur quis. Fusce dignissim arcu enim, id faucibus felis dignissim ut. Suspendisse potenti. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Phasellus blandit sem sit amet neque fringilla cursus. Ut semper imperdiet dolor ac vulputate. Phasellus in accumsan urna. Suspendisse potenti. Curabitur porttitor risus a dolor pellentesque, sed dignissim ligula laoreet. Nullam lacus ligula, malesuada ac vestibulum vitae, condimentum nec sem.

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');

        * {
            margin: 0%;
            padding: 0;
            box-sizing: border-box;
            font-family: "Inter", sans-serif;
        }



        .hero {
            min-height: 100vh;
            padding: 50px 0px;
            margin-top: 10vh;
            border-top: 1px solid rgba(0, 0, 0, 0.7);
            border-bottom: 1px solid rgba(0, 0, 0, 0.7);
        }

        .hero h1 {
            font-size: 4rem;
        }

        .hero h2 {
            font-size: 2rem;
        }

        .hero p {
            color: rgb(105, 105, 105);
        }

        .hero_left {
            position: relative;
            width: 50%;
        }

        .hero_right {
            width: 50%;
            margin-left: auto;
        }

        .hero_center {
            width: 65%;
            margin-left: auto;
            margin-right: auto;
        }

        .hero_left img {
            width: 70%;
        }

        .hero_left img:last-child {
            margin-left: 80%;
            margin-top: -25%;
        }


        /* Banner */
        .banner {
            background: rgba(209, 209, 209, 1);
        }

        .banner .canvas {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .banner_left {
            width: 50%;
            padding: 20px 0px;
        }

        .banner_img {
            position: relative;
            width: 30%;
            padding-bottom: 20px;
        }

        .banner img {
            width: 100%;
            height: 100%;
        }


        /* STORY */
        .story .canvas {
            width: 80%;
        }

        .story_grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .story_grid .arrow {
            font-size: 1.1rem;
            margin-left: auto;
            margin-top: 20px;
            display: block;
        }


        .story_card {
            background-color: rgba(44, 44, 44, 1);
            padding: 20px;
            border-radius: 20px;
            text-align: start;
            color: white;
            height: 200px;
            display: flex;
            justify-content: space-between;
            -ms-flex-direction: column;
            flex-direction: column;
        }

        .story_card p {
            width: 90%;
        }

        .story_card button {
            outline: none;
            border: none;
            height: 40px;
            width: 40px;
            background: white;
            border-radius: 50%;
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



        @media (max-width: 800px) {
            .faqs_left,
            .faqs_right {
                width: 100%;
                text-align: center;
            }

            .faqs_left img {
                width: 100%;
            }

            .hero h1 {
                font-size: 2.5rem;
                margin-bottom: 20px;
            }

            .hero_left,
            .hero_right,
            .hero_center {
                width: 100%;
            }

            .hero_left img {
                width: 70%;
                margin-top: 50px;
                margin-left: auto !important;
                margin-right: auto !important;
                display: block;
            }

            .hero_left img:last-child {
                margin-top: 50px;
                margin-left: 0px;
            }

            .banner .canvas {
                flex-direction: column-reverse;
            }

            .banner_left {
                width: 100%;
            }

            .banner_img {
                width: 50%;
                margin-left: auto;
                margin-right: auto;
            }

            .main_heading2 {
                font-size: 2rem;
            }
        }
    </style>

    <div class="hero">
        <div class="canvas">
            <div class="hero_left">
                <h1>
                    LOREM IPSUM DOLOR SIT AMET, CONSECER ELIT TEMPOR
                </h1>
            </div>
            <div class="hero_right">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem
                    ipsum
                    dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem ipsum dolor
                    sit
                    amet,
                    consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem ipsum dolor sit amet,
                    consectetur
                    adipiscing elit, sed do eiusmod tempor incididunt ut
                </p>
                <br>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem
                    ipsum
                    dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem ipsum dolor
                    sit
                    amet,
                    consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem ipsum dolor sit amet,
                    consectetur
                    adipiscing elit, sed do eiusmod tempor incididunt ut
                </p>
            </div>
            <div class="hero_left">
                <img src="./assets/event.png">
                <img src="./assets/event.png">
            </div>
            <br>
            <div class="hero_left">
                <h2>Lorem ipsum dolor sit amet, consectetur adipiscing eli</h2>
                <br>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem
                    ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem ipsum
                    dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut Lorem ipsum dolor
                    sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut</p>
            </div>
            <br>
            <br>
            <div class="hero_center">
                <img style="width: 100%;" src="./assets/Frame 9.png">
            </div>
        </div>
    </div>

    <div class="banner">
        <div class="canvas">
            <div class="banner_left">
                <h1>
                    “Lorem ipsum dolor sit amet, consectetur adipiscing eli”
                </h1>
                <p class="mt-5">- John Smith, 15</p>
            </div>
            <div class="banner_img">
                <img src="./assets/Frame 6.png">
            </div>
        </div>
    </div>

    <section class="section mt-5 story">
        <div class="canvas">
            <div class="text-center">
                <p class="bold">LOREM IPSUM DOLOR</p>
                <br>
                <h1 class="main_heading2 bold">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                    tempor
                </h1>
                <br><br>

                <div class="story_grid">
                    <div class="story_card">
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                    <div class="story_card">
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                    <div class="story_card">
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                    <div class="story_card">
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                    <div class="story_card">
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                    <div class="story_card">
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                    <div class="story_card">
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                    <div class="story_card">
                        <p>Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="arrow">
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>


                    
                </div>
            </div>
        </div>
    </section>

    
    <section class="section bg_gray FAQS">
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





