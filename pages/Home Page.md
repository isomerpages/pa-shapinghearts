---
title: Home Page
permalink: /home-page/
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
	
.canvasstext  {
	    width: 100% !important;
	}
	
.col.is-offset-2,
.col.is-offset-2-tablet {
    margin-left: 0% !important;
    width: 100% !important;
}

.content h1, .content h2, .content h3, .content h4, .content h5 {
    color: black !important;
}

.hero {
    margin-top: -20px !important;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    width: 100%;
    overflow: hidden;
    padding: 20px;
}

.bp-section-pagetitle {
    display: none;
}

.bp-section {
    padding: 0px
}

.hero .canvass {
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
    height: 100vh;
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
    color: white;
    font-weight: normal;
}

.center-box {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 30%;
    height: 20%;
    transform: translate(-50%, -50%);
    background-color: rgba(0, 0, 0, 0.1);
}

/* 2nd section Events */
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
}

.event_left p {
    font-size: 1.1rem;
    margin-top: 5px;
    color: gray;
}

.events .event_right {
    width: 48%;
}

.events .secondimg {
    margin-top: -10px;
}

/* Story */
.story .canvass {
    width: 80%;
}

.story_grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 16px;
}

.story_card h1 {
    font-size: 3rem;
    font-weight: bold;
    margin: 0px;
}

.story p {
    font-size: 1.1rem;
    margin: 0px;
}

/* Sponsors */
.sponsors .canvass {
    width: 70%;
}

.sponsors .sponsors_grid {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    grid-gap: 30px;
}

.sponsors_grid .button {
    width: 150px;
    font-weight: bold;
    border-radius: 2px;
}

/* FAQs */
.FAQS .canvass {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.faqs_left,
.faqs_right {
    width: 45%;
}

.faqs_left {
    padding-left: 20px;
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

/* General */
.canvass {
    width: 90%;
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
    padding: 100px 0px;
}

.button {
    background: white;
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

@media (max-width: 700px) {

    .faqs_left,
    .faqs_right {
        width: 100%;
        text-align: center;
    }

    .faqs_left img {
        width: 100%;
    }

    .button {
        padding: 12.5px 20px;
    }

    .canvass {
        width: 90% !important;
    }

    .events {
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

    .hero .canvass {
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
</style>

<section>
    <section class="hero">
        <img class="hero_img" src="https://i.imgur.com/2905Us8.png">
        <div class="canvass relative">
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

    <section style="z-index: 4000; position: relative;" class="relative events">
        <img class="event_bg" src="https://i.imgur.com/NG08rTq.png">
			<div class="canvass">
        <div class="event_left mt-5 section">
            <h1 class="main_heading">
                THE LARGEST<br>
                INCLUSIVE<br>
                ARTS EVENT
            </h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut.</p>
        </div>
        <div class="event_right mt-5 section">
            <img class="secondimg" src="https://i.imgur.com/hfmiZ2B.png">
				</div>
        </div>
    </section>

    <section class="story canvass section">
        <img class="story_bg" src="https://i.imgur.com/y4vGxG9.png">
        <div class="story_grid relative">
            <div class="story_card text-center">
                <h1 class="main_heading2">OUR STORY</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
            <div class="story_card text-center">
                <h1 class="main_heading2">OUR VISION</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
        </div>
    </section>

    <section class="sponsors canvass section">
        <img class="sponsors_bg" src="https://i.imgur.com/NwGbl1E.png">
        <div class="sponsors_grid">
            <div class="sponsor text-center">
                <button class="button">BECOME A SPONSOR</button>
            </div>
            <div class="sponsor text-center">
                <button class="button">OUR SPONSORS</button>
            </div>
        </div>
    </section>

    <section class="FAQS canvass section">
        <div class="faqs_left">
            <img alt="FAQ Image" src="https://i.imgur.com/y4vGxG9.png">
        </div>
        <div class="faqs_right">
            <div class="faq-container">
                <div class="faq">
                    <div class="faq-question">What is this event about?<span>▼</span></div>
                    <div class="faq-answer">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
                </div>
                <div class="faq">
                    <div class="faq-question">How can I participate?<span>▼</span></div>
                    <div class="faq-answer">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
                </div>
            </div>
        </div>
    </section>
</section>