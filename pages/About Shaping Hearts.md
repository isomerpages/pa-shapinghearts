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
    
    body{
    overflow-x:  hidden;
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
    
    .bp-container{
    width: 100% !important;
    max-width: 100% !important;
    padding: 0px !important;
    }
    
    .has-float-btns{
    display:none;
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

    .events h1{
    color: white !important;
    }
    
    .events .button{
    border: none !important;
    }
    
    /* Story */
    .story{
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
VideoPlayer{
    padding: 30px 0px;
    align-items: center;
    justify-content: center;
    }
    
    .VideoPlayer  iframe{
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
        
        .col.is-offset-2, .col.is-offset-2-tablet{
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

    .button a{
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

    .sponsors h3{
    color: #c5242f !important;
    font-weight: bold
    }

    .sponsors h2{
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

    .navbar .bp-container{
        width: 1280px !important;
    max-width: 1280px !important;
    }

     /* STORY */
    .story{
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
    
    .team_card{
    position: relative;
    }
    
    .team_card img {
    width: 100% !important;
    border-radius: 15px;
    margin: 0 !important;
    }
    
    .team_card a{
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
    
    .button:hover a{
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
    .bp-container{
    width: 100% !important;
}
    }
    
    
    @media (max-width: 1280px){
    .navbar .bp-container{
    width: 100% !important;
    max-width: 100% !important;
    }
    }
    
    @media (max-width: 700px) {
    .sponsors .sponsors_grid {
    grid-row-gap: 30px;
    }
    .VideoPlayer iframe{
    min-height: auto !important;
    }
    
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
    
	
	    /* TIMELINE */

    .isomer-timeline-section {
        font-family: Arial, sans-serif;
        background-color: #c5242f;
        color: white;
        padding: 20px;
    }

    body .content .isomer-timeline-section .timeline-title {
        text-align: center;
        margin-bottom: 50px;
        font-size: 36px;
        color: white !important;
    }

    body .content .isomer-timeline-section .isomer-timeline .timeline-title {
        text-align: start;
        margin-bottom: 0px;
        font-size: 22px;
        color: white !important;
    }

    .timeline-desc {
        width: 80%;
        margin: auto;
    }

    .isomer-timeline {
        position: relative;
        max-width: 1200px;
        margin: auto;
    }

    .isomer-timeline::after {
        content: '';
        position: absolute;
        width: 6px;
        background-color: #ff6f61;
        top: 0;
        bottom: 0;
        left: 50%;
        margin-left: -3px;
    }

    .timeline-container {
        padding: 10px;
        position: relative;
        background-color: inherit;
        width: 50%;
    }
	
	.timeline-content img{
	width: 250px;
	margin: 0;
	}


    @media (max-width: 768px) {
        .timeline-content {
            flex-direction: column;
	align-items: start;
        }

        .timeline-container {
            width: 100% !important;
            left: 0 !important;
            padding-left: 20px;
        }
	
	.timeline-desc{
	width: 100%;
	}

        .isomer-timeline::after {
            left: 0;
        }

        .timeline-container.right-container::after {
            left: 20px;
            right: auto;
        }

        .timeline-container.right-container .timeline-content {
            margin-left: 0px !important;
        }

        .timeline-content {
            padding: 5px 20px !important;
        }

        body .content .isomer-timeline-section .isomer-timeline .timeline-title {
            text-align: start;
            margin-bottom: 10px;
        }

        .timeline-container::after {
            right: 0%;
            left: -13px;
        }

        .timeline-desc {
            width: 100%;
        }
	.timeline-content{
	align-items: start !important;
	}
    }

    .timeline-container.left-container {
        left: 0;
    }

    .timeline-container.right-container {
        left: 50%;
    }

    .timeline-container::after {
        content: '';
        position: absolute;
        width: 25px;
        height: 25px;
        right: -13px;
        background-color: #ff6f61;
        border: 4px solid #ff6f61;
        top: 15px;
        border-radius: 50%;
        z-index: 1;
    }

    .timeline-container.right-container::after {
        left: -13px;
    }

    .timeline-content {
        padding: 20px 5px;
        position: relative;
        border-radius: 6px;
        display: flex;
        align-items: center;
        column-gap: 10px;
    }

    .timeline-container.left-container .timeline-content {
        margin-left: 0;
    }

    .timeline-container.right-container .timeline-content {
        margin-left: 30px;
    }

    .timeline-date {
        font-size: 14px;
        color: #ffffff80;
        margin-bottom: 5px;
    }

    .timeline-title {
        font-weight: bold;
        margin-bottom: 10px;
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
            <p>What gives art meaning? Is it the artist behind the art? Is it the way it’s created? Or is it meaningful because it speaks to you? Sometimes, we don’t need to find meaning in art - it’s already there.</p>
            <div class="flex justify-between mt-5">
                <button class="button bold"><a target="_blank" href="https://shop.shapinghearts.sg/">Shop</a></button>
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
                <h1 class="main_heading2 text-center mt-5">Step into the world of talented artists with disabilities and be awed by their art creations at the largest inclusive arts event!</h1>
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
                 <a href="https://staging.d2d4qnv3td402n.amplifyapp.com/alex-lim/">Alex Lim <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
           </div>
           <div class="team_card">
              <img src="https://i.ibb.co/w7GMVNX/Gary-Chong.jpg">
                     <a href="https://staging.d2d4qnv3td402n.amplifyapp.com/gary-chong/">Gary Chong <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
           </div>
           <div class="team_card">
                      <img src="https://i.ibb.co/n1HZZGc/Leong-Sijun.png">
                 <a href="https://staging.d2d4qnv3td402n.amplifyapp.com/leong-sijun/">Leong Sijun <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
           </div>
           <div class="team_card">
                  <img src="https://i.ibb.co/7gQFvV5/Ng-Jun-Yao.jpg">
                 <a href="https://staging.d2d4qnv3td402n.amplifyapp.com/ng-jun-yao/">Ng Jun Yao <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
           </div>
           <div class="team_card">
                          <img src="https://i.ibb.co/ZLg3w39/Vincent-Seet.jpg">
                     <a href="https://staging.d2d4qnv3td402n.amplifyapp.com/vincent-seet/">Vincent Seet <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
           </div>  
           <div class="team_card">
                          <img src="https://i.ibb.co/YRhbDcZ/randy-wah.jpg">
                     <a href="https://staging.d2d4qnv3td402n.amplifyapp.com/randy-wah/">Randy Wah <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
           </div>  
    <div>
  </div>
  </div>
  </div>
  </div></section>

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
                <br>
        </div>
    </div></div></section>
</section>
	
		 <section class="isomer-timeline-section">
        <h1 class="timeline-title">GROWTH OF SHAPING HEARTS</h1>
        <p class="timeline-desc" style="text-align: center;">
            Initiated by North East CDC in 2019, Shaping Hearts was envisioned as a annual platform where persons with
            disabilites could build their future through art. Each artwork represents a step towards independence and
            recognition, showcasing talents that might otherwise go unnoticed. As Shaping Hearts has grown, so has our
            community's understanding of inclusion We're creating a space in Singapore where art opens doors, improves
            lives, and enables everyone to contribute. Today Shaping Hearts is Singapore's largest inclusive arts
            festival
        </p>

        <br>
        <div class="isomer-timeline">
            <div class="timeline-container left-container">
                <div class="timeline-content">
                    <img style="border-radius: 20px;" width="250" src="https://i.ibb.co/mN4ttcM/5IMG195.jpg">
                    <div class="">
                        <p class="timeline-title">2019 “Art Market @ North East”</p>
                        
                        <p style="margin: 0px !important">46 paintings<br> 25 artists <br> 12 SSAs
                        </p>
                        <p style="margin-top: 5px; width: fit-content; background: #ffca50; color: white; color: #97002b; font-weight: bold; padding: 10px; border-radius: 10px; font-size: 17px">
                            Raised $31,260
                        </p>

                    </div>
                </div>
            </div>
            <div class="timeline-container right-container">
                <div class="timeline-content">
                    <img style="border-radius: 20px;" width="200" src="https://i.ibb.co/d0NKQSS/ART-Auction1.jpg">
                    <div class="">
                        <p class="timeline-title">2020 “Articulate @ North East”</p>
                        
                        <p style="margin: 0px !important">120 paintings<br> 100 artists <br> 12 SSAs</p>
                        <p style="margin-top: 5px; width: fit-content; background: #ffca50; color: white; color: #97002b; font-weight: bold; padding: 10px; border-radius: 10px; font-size: 17px">
                            Raised $36,640
                        </p>
                    </div>
                </div>
            </div>
            <div class="timeline-container left-container">
                <div class="timeline-content">
                    <img style="border-radius: 20px;" width="250" src="https://i.ibb.co/PgMM71N/26-NOV-SHAPING-HEARTS-25-min.jpg">
                    <div class="">

                        <p class="timeline-title">2021 “Shaping Hearts”</p>
                        
                        <p style="margin: 0px !important">110 paintings<br> 150 artists <br> 21 SSAs</p>
                        <p style="margin-top: 5px; width: fit-content; background: #ffca50; color: white; color: #97002b; font-weight: bold; padding: 10px; border-radius: 10px; font-size: 17px">
                            Raised $284,010
                        </p>
                    </div>
                </div>
            </div>
            <div class="timeline-container right-container">
                <div class="timeline-content">
                    <img style="border-radius: 20px;" width="250" src="https://i.ibb.co/88tBHvt/DSC-8633.jpg">
                    <div class="">

                        <p class="timeline-title">2022 “Shaping Hearts”</p>
                        
                        <p style="margin: 0px !important">270 paintings<br> 150 artists <br> 22 SSAs</p>
                        <p style="margin-top: 5px; width: fit-content; background: #ffca50; color: white; color: #97002b; font-weight: bold; padding: 10px; border-radius: 10px; font-size: 17px">
                            Raised $570,000
                        </p>
                    </div>
                </div>
            </div>
            <div class="timeline-container left-container">
                <div class="timeline-content">
                    <img style="border-radius: 20px;" width="250" src="https://i.ibb.co/cCvB0VT/OTH8832-min.jpg">
                    <div class="">

                        <p class="timeline-title">2023 “Shaping Hearts”</p>
                        
                        <p style="margin: 0px !important">350 paintings<br> 150 artists <br> 28 Comunity Partners</p>
                        <p style="margin-top: 5px; width: fit-content; background: #ffca50; color: white; color: #97002b; font-weight: bold; padding: 10px; border-radius: 10px; font-size: 17px">
                            Raised $490,586
                        </p>
                    </div>
                </div>
            </div>

            <div class="timeline-container right-container">
                <div class="timeline-content">
                    <img style="border-radius: 20px;" width="250" src="https://i.ibb.co/h2JKLFc/OTH8857-min.jpg">
                    <div class="">

                        <p class="timeline-title">2024 “Shaping Hearts”</p>
                        
                        <p style="margin: 0px !important">500 paintings<br> 200 artists <br> 27 Sponsors &amp; Partners <br> 22 SSAs</p>
                    </div>
                    
                </div>
            </div>

        </div>
    </section>
	
</section>