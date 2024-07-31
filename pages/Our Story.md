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
    padding: 30px 0px;
    margin-top: -20px;
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
	color: black !important;
    }
    
    .hero h2 {
    font-size: 2rem;
    font-weight: bold;
	color: white !important;
    }
    
    .hero p {
    color: black;
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
	margin-top: 30px !important;
    }
	
	.hero_right h2{
	color: black !important;
	}
  
	.hero_right .second{
	width: 50%;
	}
	
	.VideoPlayer{
	display: none;
	padding: 30px 0px;
	align-items: center;
	justify-content: center;
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
        
    .hero_right img {
    width: 45%;
    }

    
    
    /* STORY */
	.story{
	display: flex;
	align-items: center;
	justify-content: center;
	}
	
    .story .canvass {
    width: 80%;
    }
    
    .story_grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
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
    
	.story_card{
	position: relative;
	}
    
    .story_card img {
	width: 100% !important;
	border-radius: 10px;
    }
	
	.story_card a{
	position: absolute;
	bottom:0%;
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
    padding: 70px 0px;
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
		.FAQS{
	height: 100%;
	width: 100%;
	}
	
	.FAQS h1{
color: black !important;
	}
	
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
    border-top-right-radius: 10px;
    display: block;
    padding: 15px 10px;
    border-top-left-radius: 10px;
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
		.story_card a{
	        padding: 10px;
	}
	
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
	
	.story h1{
	color: black !important;
	font-weight: bold;
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
			<img src="https://i.ibb.co/mGydBr3/Story-1.png">
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
    <section class="section story bg_gray">
    <div class="canvass">
    <div class="text-center">
    <h1 class="main_heading2 bold">MEET OUR HEARTISTS
    </h1>
    <br><br>
    
    <div class="story_grid">
			<div class="story_card">
  <img src="https://i.ibb.co/B4dqK81/Alex-Lim.jpg">
				<a href="https://staging.d2d4qnv3td402n.amplifyapp.com/alex-lim/">Alex Lim</a>
			</div>
			<div class="story_card">
			 <img src="https://i.ibb.co/w7GMVNX/Gary-Chong.jpg">
					<a href="https://staging.d2d4qnv3td402n.amplifyapp.com/alex-lim/">Gary Chong</a>
			</div>
			<div class="story_card">
					 <img src="https://i.ibb.co/n1HZZGc/Leong-Sijun.png">
				<a href="https://staging.d2d4qnv3td402n.amplifyapp.com/alex-lim/2">Leong Sijun</a>
			</div>
			<div class="story_card">
				 <img src="https://i.ibb.co/7gQFvV5/Ng-Jun-Yao.jpg">
				<a href="https://staging.d2d4qnv3td402n.amplifyapp.com/alex-lim/">Ng Jun Yao</a>
			</div>
			<div class="story_card">
						 <img src="https://i.ibb.co/ZLg3w39/Vincent-Seet.jpg">
					<a href="https://staging.d2d4qnv3td402n.amplifyapp.com/alex-lim/">Vincent Seet</a>
			</div>
			<div class="story_card">
							 <img src="https://i.ibb.co/GVNQWyY/Yap-Jia-Hui.jpg">
				<a href="https://staging.d2d4qnv3td402n.amplifyapp.com/alex-lim/">Yap Jia Hui</a>
			</div>
			<div>
    </div>
    </div>
    </div>
    </div></section>
	    
   <section class="section FAQS">
  <div class="canvass">
    <div class="faqs_left">
      <p class="bold">LOREM IPSUM dolor</p>
      <h1 class="bold mt-5">Lorem ipsum dolor sit amet adipiscing elit,</h1>
      <br>
      <img alt="Event" class="mt-5" style="width: 500px" src="https://i.ibb.co/F6zc2zJ/Homepage-3.png">
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