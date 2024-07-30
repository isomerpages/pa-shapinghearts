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
	
	html {
	width: 100% !important;
	}

    .col.is-offset-2,
    .col.is-offset-2-tablet {
        margin-left: 0% !important;
        width: 100% !important;
    }
	
	.content h1, .content h2, .content h3, .content h4, .content h5 {
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
	background: url("https://i.ibb.co/BznXQFQ/Homepage-1.png") no-repeat;
	background-size: contain;
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

    .relative{
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

  .hero  .text {
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
	.events{
	height: 100%;
	width: 100%;
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
	
	.bp-container{
	width: 1280px !important;
	max-width: 1280px !important;
	}
	.has-float-btns{
	display:none;
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
    .story .canvas {
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
    .sponsors .canvas {
        width: 70%;
    }

    .sponsors .sponsors_grid {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        grid-gap: 30px;
    }

	.sponsors_grid h3{
	color: black;
	}
	
    .sponsors_grid img {
        width: 150px;
        font-weight: bold;
        border-radius: 2px;
    }


    /* FAQS */	
    .FAQS .canvas {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    }
    
  .faq-container {
    max-width: 800px;
    margin: 0 auto;
  }
	
		.faqs_left,
	.faqs_right {
	max-width: 500px;
	}

  .faq {
    border-bottom: 1px solid #ccc;
    margin-bottom: 10px;
  }

  .faq-input {
    display: none;
  }
  
  .FAQS h1{
    font-size: 1.5rem !important;
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
    max-height: 200px;
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

    /* General */
    body .canvas {
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


	@media (max-width: 1280px) {
	.bp-container{
	width: 100% !important;
}
	}
	
    @media (max-width: 700px) {
	.hero{
	background: none;
	}
	
	.section{
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

       body  .canvas {
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
            <p>Shop meaningful artworks by artists with disabilities, step into their world through sensorial experiences, and so much more!</p>
            <div class="flex justify-between mt-5">
							<button class="button bold"><a href="/our-story">Our Story</a></button>
                <button class="button bold">SHOP</button>
            </div>
        </div>
        <div style="z-index: 4000; position: relative;" class="event_right section">
            <img style="width: 100%;  display: block;" src="https://i.ibb.co/0BsF3nb/Homepage-2.png">
        </div>
			</div>
    </section>

    <section class="story relative">
        <div style="z-index: 4000; position: relative;" class="canvas section">
            <div class="text-center">
                <p class="text-center bold">FOLLOW OUR HEARTS</p>
                <h1 class="main_heading2 text-center mt-5">Step into the world of talented artists with disabilities and be awed by their art creations at the largest inclusive arts event!</h1>
                <button style="width: fit-content; background: white;" class="button bold mt-5">OUR STORY</button>
                <br>
                <br>

                <div class="story_grid mt-5">
                    <div class="story_card">
                        <p class="text-gray">Over</p>
                        <h1>150</h1>
                        <p class="text-gray">
                            Participating Artists
                            with Disabilities
                        </p>
                    </div>
                    <div class="story_card">
                        <p class="text-gray">More than</p>
                        <h1>350</h1>
                        <p class="text-gray">
                            Exhibited Paintings
                        </p>
                    </div>
                    <div class="story_card">
                        <p class="text-gray">Over</p>
                        <h1>30</h1>
                        <p class="text-gray">
                            Participating Social
                            Service Agencies
                            and Partners
                        </p>
                    </div>
                    <div class="story_card">
                        <p class="text-gray">More than</p>
                        <h1>2.8M</h1>
                        <p class="text-gray">
                            Public Engagements
                            on Social Media
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="sponsors relative">

        <div style="z-index: 4000; position: relative;" class="canvas section">
            <div class="text-center mt-5">
                <h3>PLATINUM SPONSORS</h3>
                <div class="sponsors_grid mt-5">
                    <img src="https://i.ibb.co/DfppnNY/PLATINUM-Neo-Group-Logo.png">
                    <img src="https://i.ibb.co/jwd4skW/Rigel-Logo-Horizontalnew-004.png">
                    <img src="https://i.ibb.co/vqPKFGQ/PLATINUM-SP-55th-Horizontal-Logo-2.png">
                </div>
                <br>

                <div class="text-center mt-5">
                    <h3>SILVER SPONSORS</h3>
                    <div class="sponsors_grid mt-5">
                        <img src="https://i.ibb.co/kSyrgzb/Myck.jpg">
                        <img src="https://i.ibb.co/kSyrgzb/Myck.jpg">
                    </div>
                </div>
                <br>

                <div class="text-center mt-5">
                    <h3>BRONZE SPONSORS</h3>
                    <div class="sponsors_grid mt-5">
                        <img src="https://i.ibb.co/Fgs9HfR/global-indian.png">
                        <img src="https://i.ibb.co/ByfhfkD/Logo-Jean-Yip-Group.png">
                        <img src="https://i.ibb.co/qkbc2gw/RICO-002-scaled.jpg">
                        <img src="https://i.ibb.co/SBrd86x/OUE.jpg">
                        <img style="width: 100px;" src="https://i.ibb.co/XttB1jx/BRONZE-P-G-Logo-RGB.png">
                        <img src="https://i.ibb.co/gg1Xk9j/LOGO-NEW-JULY-MULTIPLE-TRANSPARENT-new-extend-40.png">
                    </div>
                </div>
                <br>
                <div class="text-center mt-5">
                    <h3>TECH SPONSORS</h3>
                    <div class="sponsors_grid mt-5">
                        <img src="https://i.ibb.co/FJy3P94/HW-POS-RGB-Horizontal-300ppi-002.png">
                    </div>
                </div>
                <br>
                <div class="text-center mt-5">
                    <h3>ART PATRON</h3>
                    <div class="sponsors_grid mt-5">
                        <img src="https://i.ibb.co/FnZzsFC/Appliedlogo-blue-102021-002.png">
                        <img src="https://i.ibb.co/mXdQQPR/SSIA-Logo-CMYK-002.jpg">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="FAQS relative">
        <div style="z-index: 4000; position: relative;" class="canvas section">
            <div class="faqs_left">
                <p class="bold">FREQUENTLY ASKED QUESTIONS</p>
                <h1 class="bold mt-5">
                  Shaping Hearts is where you can experience the artists’ works through multiple lenses – an art exhibition, live performances, a charity art auction – and celebrate the diverse talents in our community.
                </h1>
                <img class="mt-5" style="width: 500px;" src="https://i.ibb.co/F6zc2zJ/Homepage-3.png">
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
    </div></section>
</section>