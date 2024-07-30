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
	max-width: 1280px;
	width: 100%;
	}
	
		.has-float-btns{
	display:none;
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
	
	.hero .canvass{
	width: 90%;
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
	justify-content: space-between;
    width: 100%;
    }
  
	.hero_right .second{
	width: 80%;

	}
	
	.VideoPlayer{
	height: 90vh;
	display: flex;
	align-items: center;
	justify-content: center;
	background: url("https://i.ibb.co/LpHxkxT/Asset-14.png") no-repeat;
	background-position: center;
	background-size: cover;
	}
	
    .hero_center {
    width: 65%;
    margin-left: auto;
    margin-right: auto;
	position: relative;
	z-index: 3000;
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
	.story{
	display: flex;
	align-items: center;
	justify-content: center;
	background: url("https://i.ibb.co/JBFRmjG/Asset-16.png") no-repeat;
	background-position: center;
	background-size: cover;
	}
	
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
	position: absolute;
	bottom: 20px;
	right: 20px;
    }
    
    
    .story_card {
	position: relative;
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
    width: 100%;
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
	color: black !important;
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
    
	.relative{
	position: relative;
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
    
	.faqs_left,
	.faqs_right {
	max-width: 500px
	}
	
  .faq-container {
    max-width: 800px;
    margin: 0 auto;
  }

  .faq {
    border-bottom: 1px solid #ccc;
    margin-bottom: 10px;
  }

  .faq-input {
    display: none;
  }

  .faq-question {
    display: block;
    padding: 15px 0;
    font-weight: bold;
    cursor: pointer;
    background: #f1f1f1;
    margin: 0;
  }

  .faq-answer {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.3s ease-out;
    background: #fff;
    padding: 0 15px;
  }

  .faq-input:checked + .faq-question + .faq-answer {
    max-height: 200px; /* Adjust this value as needed */
    padding: 15px 15px;
  }

  .faq-input:checked + .faq-question {
    background: #e0e0e0;
  }

  .faq-question::after {
    content: '▼';
    float: right;
    transition: transform 0.3s ease-out;
  }

  .faq-input:checked + .faq-question::after {
    transform: rotate(180deg);
  }
    
    @media (max-width: 800px) {
	.hero_right img{
	display: none;
	}
	
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
    .hero_right .second,
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
    Step into the world of talent artists with disabilities
    </h1>
    </div>
    <div class="hero_right">
			<img src="https://i.ibb.co/yWvSB53/1.png">
    <div class="second">
			<h2>...and be awed by their art creations at the largest inclusive arts festival in Singapore!</h2>
    <p>
   Experience the artists' works through multiple lenses - an art exhibition, live performances, a charity art auction- and celebrate the diverse talents in our community.
    </p>
			</div>
    </div>
			</div>
	</div>
    
  	<div class="VideoPlayer relative">
		<div class="hero_center">
			<img style="width: 100%" src="https://www.intermedia-solutions.net/wp-content/uploads/2021/06/video-thumbnail-01.jpg">
		</div>
	</div>
	
    <section class="section story">
    <div class="canvass">
    <div class="text-center">
    <h1 class="main_heading2 bold">MEET OUR HEARTISTS
    </h1>
    <br><br>
    
    <div class="story_grid">
    <div class="story_card">
    <p>ALEX</p>
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
      <h1 class="bold mt-5">Lorem ipsum dolor sit amet adipiscing elit,</h1>
      <br>
      <img alt="Event" class="mt-5" src="https://i.ibb.co/0YcyxrZ/3.png">
    </div>
    <div class="faqs_right">
      <div class="faq-container">
        <div class="faq">
          <input class="faq-input" id="faq1" type="checkbox">
          <label class="faq-question" for="faq1">Add commonly asked questions here</label>
          <div class="faq-answer">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ut lorem qui Nullam ut lorem qui.
          </div>
        </div>
        <div class="faq">
          <input class="faq-input" id="faq2" type="checkbox">
          <label class="faq-question" for="faq2">Add commonly asked questions here</label>
          <div class="faq-answer">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ut lorem qui Nullam ut lorem qui.
          </div>
        </div>
        <div class="faq">
          <input class="faq-input" id="faq3" type="checkbox">
          <label class="faq-question" for="faq3">Add commonly asked questions here</label>
          <div class="faq-answer">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ut lorem qui Nullam ut lorem qui.
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

    </section>