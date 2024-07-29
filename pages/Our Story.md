---
title: Our Story
permalink: /our-story/
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
	
	.bp-container{
	max-width: 100%;
	width: 100%;
	}
	
	    html {
    width: 100% !important;
    }

    .col.is-offset-2,
    .col.is-offset-2-tablet {
        margin-left: 0% !important;
        width: 100% !important;
    }

 body .content h1, body .content h2,body .content h3, body .content h4, body .content h5 {
    color: black !important;
}
	
    .hero {
    min-height: 100vh;
    padding: 30px 0px;
    margin-top: -20px;
	background: url("https://i.ibb.co/3rH1qph/Background.png") no-repeat;
	background-size: cover;
	background-position: center;
    }
    
            .bp-section-pagetitle{
        display: none;
        }
        
        .bp-section{
        padding: 0px !important;
        }
        
    .hero h1 {
    font-size: 3rem;
    font-weight: bold;
	color: white !important;
    }
    
    .hero h2 {
    font-size: 2rem;
    font-weight: bold;
	color: white !important;
    }
    
    .hero p {
    color: white;
    }
    
    .hero_left {
    position: relative;
    width: 50%;
    margin-right: auto;
    }
    
    .hero_right {
	display: flex;
	align-items: start;
    width: 100%;
    }
    
    .hero_center {
    width: 65%;
    margin-left: auto;
    margin-right: auto;
    }
        
        .col.is-offset-2, .col.is-offset-2-tablet{
        margin-left: 0% !important;
     width: 100% !important;
        }
        
    
    
    .hero_left img {
    width: 50%;
    }
    
    .hero_left img:last-child {
    margin-left: 50%;
    margin-top: -25%;
    }
    
    
    /* STORY */
    .story .canvass {
    width: 80%;
    }
    
    .story_grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
    width: 95%;
    margin: auto;
    }
    
    .story_grid .arrow {
    font-size: 1.2rem;
    margin-left: auto;
        height: 35px;
        width: 35px;
        border-radius: 50%;
    }
    
    
    .story_card {
    background-color: rgba(44, 44, 44, 1);
    padding: 30px 20px;
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
    body .canvass {
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
    }
    
    .main_heading2 {
    font-size: 3rem;
        margin-top: 0 !important;
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
    .FAQS .canvass {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    }
    
    
    .faqs_left{
    padding-left: 20px;
    }
    
    .faqs_left h1{
    font-size: 2rem;
    line-height: 1.2;
    font-weight: bold;
    }
    
    .faqs_left,
    .faqs_right {
    width: 48%;
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
       body .canvass{
        width: 90% !important;
        margin-left: auto;
        margin-right: auto;
        }
        
    .story_grid{
    width: 100%;
    }
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
    
  
    .main_heading2 {
    font-size: 2rem;
    }
    }
    </style>
<section>
    <div class="hero">
    <div class="canvass">
    <div class="hero_left">
    <h1>
    LOREM IPSUM DOLOR SIT AMET, CONSECER ELIT TEMPOR
    </h1>
    </div>
    <div class="hero_right">
			<img src="https://i.ibb.co/yWvSB53/1.png">
    <div>
			<h2>Lorem ipsum dolor sit amet, consectetur adipiscing elit</h2>
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
    </div>
			</div>
	</div>
    
  
    <section class="section mt-5 story">
    <div class="canvass">
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
    <i class="sgds-icon sgds-icon-arrow-right"></i>
    </button>
    </div>
    <div class="story_card">
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <button class="arrow">
    <i class="sgds-icon sgds-icon-arrow-right"></i>
    </button>
    </div>
    <div class="story_card">
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <button class="arrow">
    <i class="sgds-icon sgds-icon-arrow-right"></i>
    </button>
    </div>
    <div class="story_card">
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <button class="arrow">
    <i class="sgds-icon sgds-icon-arrow-right"></i>
    </button>
    </div>
    <div class="story_card">
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <button class="arrow">
    <i class="sgds-icon sgds-icon-arrow-right"></i>
    </button>
    </div>
    <div class="story_card">
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <button class="arrow">
    <i class="sgds-icon sgds-icon-arrow-right"></i>
    </button>
    </div>
    <div class="story_card">
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <button class="arrow">
    <i class="sgds-icon sgds-icon-arrow-right"></i>
    </button>
    </div>
    <div class="story_card">
    <p>Lorem ipsum dolor sit amet consectetur.</p>
    <button class="arrow">
    <i class="sgds-icon sgds-icon-arrow-right"></i>
    </button>
    </div>
    </div>
    </div>
    </div>
    </section>
    
   
    <section class="section bg_gray FAQS">
    <div class="canvass">
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