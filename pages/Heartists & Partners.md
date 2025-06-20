---
title: Heartists & Partners
permalink: /heartists-and-partners/
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
  .bp-section-pagetitle{
  display: none;
  }
  
    .hero {
      /* border-top: 1.99px solid rgba(0, 0, 0, 0.7);*/
  margin-top: -20px;
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
        font-size: 3rem;
  font-weight: bold;
  line-height: 1.4;
  color: black !important;
    }
  
    .hero_left p {
        margin-top: 10px;
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
  
      
    /* HEARTS */
    .hearts_grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
        gap: 40px;
    }
  
    .heart_card p:last-child {
        color: rgb(85, 85, 85);
    }
  
  .heart_card p{
  margin: 0% !important;
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
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 20px;
        border-radius: 15px;
        height: 200px;
    }
  
    .partner_card img {
        width: 100%;
    }
  
  
    /* General */
    .canvas {
        width: 100%;
        margin-left: auto;
        margin-right: auto;
    }
  
  .col.is-offset-2, .col.is-offset-2-tablet{
  width: 100%;
  margin-left: 0%;
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
        font-size: 3rem;
        line-height: 1.4;
  font-weight: bold;
    }
  
    .main_heading2 {
        font-size: 3rem;
  font-weight: bold;
  color: black !important;
    }
  
    .section {
        padding: 50px 0px;
    }
  
  .text-center{
  text-align: center;
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
  color: black !important;
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
  
  .navbar .bp-container{
  width: 1280px !important;
  max-width: 1280px !important;
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
  
  
    /* youtube_section */
    .youtube_section {
        border-top: 2px solid gainsboro;
        border-bottom: 1.99px solid black;
        min-height: 100vh;
    }
  
  @media (max-width: 1280px){
  .navbar .bp-container{
  width: 100% !important;
  max-width: 100% !important;
  }
  }
  
    @media (max-width: 800px) {
  .canvass {
  width: 90% !important;
  margin-left: auto;
  margin-right: auto;
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
  
  .bp-section{
  padding: 0px !important;
  }
  </style>
  
  <section>
  <section class="hero">
    <div class="canvas canvass relative">
        <div class="hero_left">
            <h1>Meet our Heartists and Partners.</h1>
            <p>Discover the talented Heartists behind the masterpieces and the dedicated partners who have collaborated and supported their journey. Each piece of art they create tells a profound story—a tale of hardship, resilience, triumph, and hope.</p>
        </div>
        <div class="hero_right">
            <img src="https://i.ibb.co/B20TdxHH/Header-Image-1.png">
        </div>
    </div>
  </section>
  
  <section class="section story bg_gray">
      <div class="canvass">
      <div class="text-center">
      <h1 class="main_heading2 bold">Our Heartists
      </h1>
      <br><br>
<div class="team_grid">
        <div class="team_card">
            <img src="https://i.ibb.co/8n8stPm2/Aubrey-Ang.jpg">
            <a href="/aubrey-ang/">Aubrey Ang <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/nswsmt76/Audrey-Ang-Pei-Yu.jpg">
            <a href="/audrey-ang-pei-yu/">Audrey Ang Pei Yu <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/R4Yd728q/Caden-Lee-Kai-En.jpg">
            <a href="/caden-lee-kai-en/">Caden Lee Kai En <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/398PyJMz/Choy-Eu-Jun-Julian.jpg">
            <a href="/choy-eu-jun-julian/">Choy Eu Jun, Julian <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/7t5cBn0C/Christopher-Daniel-Widjaja.jpg">
            <a href="/christopher-daniel-widjaja/">Christopher Daniel Widjaja <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/qMqtP0Lq/Christopher-Tey-Rui-Fang.jpg">
            <a href="/christopher-tey-rui-fang/">Christopher Tey Rui Fang <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/yBsnfyzt/Elijah-Goh.jpg">
            <a href="/elijah-goh/">Elijah Goh <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/ZzrcRr6X/Evan-Goh.jpg">
            <a href="/evan-goh/">Evan Goh <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/TDp8sgCy/Ezra-Chan-Yi.jpg">
            <a href="/ezra-chan-yi/">Ezra Chan Yi <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/My6VkYZy/Gabriel-Rhed-Osea-Longid.jpg">
            <a href="/gabriel-rhed-osea-longid/">Gabriel Rhed Osea Longid <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/fc19WHv/Isabella-Grace-Wilfred-Izzy.jpg">
            <a href="/isabella-grace-wilfred-izzy/">Isabella Grace Wilfred (Izzy) <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/C5v80sjm/Janetta-Tan.jpg">
            <a href="/janetta-tan/">Janetta Tan <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/v6kbqPpw/Jonas-Teo.jpg">
            <a href="/jonas-teo/">Jonas Teo <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/67MFHSFn/Joshua-Wang-Yu-Hui.jpg">
            <a href="/joshua-wang-yu-hui/">Joshua Wang Yu Hui <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/7xjHgwYF/Alex-Lim.jpg">
            <a href="/alex-lim/">Alex Lim <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/DFNSSz0/Koh-Xin-Abraham.jpg">
            <a href="/koh-xin-abraham/">Koh Xin Abraham <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/sYDstbz/Linda-Wong-Pui-See.jpg">
            <a href="/linda-wong-pui-see/">Linda Wong Pui See <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/WvJvp3qT/Ling-Teck-Mong.jpg">
            <a href="/ling-teck-mong/">Ling Teck Mong <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/WpcCvnZF/Lucas-Teo.jpg">
            <a href="/lucas-teo/">Lucas Teo <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/23p34PZP/Moy-Saw-Han.jpg">
            <a href="/moy-saw-han/">Moy Saw Han <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/Kcw22L29/Muhammad-Ridhwan-Masli.jpg">
            <a href="/muhammad-ridhwan-masli/">Muhammad Ridhwan Masli <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/DH3g8TNY/Muhammad-Syazwan-Bin-Rahmat.jpg">
            <a href="/muhammad-syazwan-bin-rahmat/">Muhammad Syazwan Bin Rahmat <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/dsz1pXX9/Ng-Jun-Yao.jpg">
            <a href="/ng-jun-yao/">Ng Jun Yao <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/Zv425CQ/Nur-Amalina-Binte-Rahmat.jpg">
            <a href="/nur-amalina-binte-rahmat/">Nur Amalina Binte Rahmat <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/6R5wmXxJ/Ong-Chee-Hwee.jpg">
            <a href="/ong-chee-hwee/">Ong Chee Hwee <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/LdnRJtjf/Serene-Keen.jpg">
            <a href="/serene-keen/">Serene Keen <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/Csb3R5XW/Simeon-Tan-Rui-En.jpg">
            <a href="/simeon-tan-rui-en/">Simeon Tan Rui En <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/bj7rFrrH/Titus-Teo.jpg">
            <a href="/titus-teo/">Titus Teo <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/YH4H1bp/Vincent-Seet-Seet-Kie-Hong.jpg">
            <a href="/vincent-seet/">Vincent Seet (Seet Kie Hong) <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/21vpFrys/Yap-Jia-Hui.jpg">
            <a href="/yap-jia-hui/">Yap Jia Hui <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/1t4zkSFy/Zayne-Pua.jpg">
            <a href="/zayne-pua/">Zayne Pua <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/kV3K6Vgq/Lim-Min-Chieh.jpg">
            <a href="/stanley-lim-min-chieh/">Stanley Lim Min-Chieh <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
      </div>
      </div>
      </div>
      
      </section>
  
  <section class="section partners">
    <div class="canvass canvas">
        <h1 class="main_heading2">Our Partners</h1>
        <br>
        <div class="partners_grid mt-5">
            <div class="partner_card">
                <a href="/apsn-katong-school/"><img alt="APSN Katong School" src="https://i.ibb.co/tMjTRhh4/APSN-Katong-School.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/artdis-singapore-ltd/"><img alt="ARTDIS Singapore Ltd." src="https://i.ibb.co/dwz4x87d/ARTDIS-Singapore-Ltd.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/artzillions/"><img alt="Artzillions" src="https://i.ibb.co/99kFS3zR/Artzillions.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/awwa-school/"><img alt="AWWA School" src="https://i.ibb.co/JjQsbGvH/AWWA-School.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/bethesda-care-centre/"><img alt="Bethesda CARE Centre" src="https://i.ibb.co/xtqk5Z32/Bethesda-CARE-Centre.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/bizlink-centre-singapore/"><img alt="Bizlink Centre Singapore Ltd" src="https://i.ibb.co/bRsgzVfn/Bizlink-Centre-Singapore-Ltd.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/cerebral-palsy-alliance-singapore-cpas-grow/"><img alt="Cerebral Palsy Alliance Singapore (CPAS GROW)" src="https://i.ibb.co/qMSPk60B/Cerabral-Palsy-Alliance-Singapore-CPAS-GROW.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/cerebral-palsy-alliance-singapore-cpas-school/"><img alt="Cerebral Palsy Alliance Singapore (CPAS School)" src="https://i.ibb.co/qMSPk60B/Cerabral-Palsy-Alliance-Singapore-CPAS-GROW.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/christian-outreach-to-the-handicapped/"><img alt="Christian Outreach to the Handicapped" src="https://i.ibb.co/j9wX69s7/Christian-Outreach-to-the-Handicapped.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/extraordinary-people-limited/"><img alt="Extraordinary People Limited" src="https://i.ibb.co/XZkWJkVT/Extraordinary-People-Limited.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/friends-of-the-disabled-society/"><img alt="Friends of the Disabled Society" src="https://i.ibb.co/Z6n36HfD/Friends-of-the-Disabled-Society.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/handicaps-welfare-association/"><img alt="Handicaps Welfare Association" src="https://i.ibb.co/PGRCRXK9/Handicaps-Welfare-Association.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/journey-by-touch/"><img alt="JOURNEY by TOUCH" src="https://i.ibb.co/bjBtqcHV/JOURNEY-by-TOUCH.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/metta-welfare-association/"><img alt="Metta Welfare Association (Arts @ Metta)" src="https://i.ibb.co/6R5grX0m/Metta-Welfare-Association-Arts-Metta.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/mouth-and-foot-painting-artists/"><img alt="Mouth and Foot Painting Artists" src="https://i.ibb.co/gL1Xd3X1/Mouth-and-Foot-Painting-Artists.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/minds-satellite-hub-bukit-batok/"><img alt="MINDS Satellite Hub (Bukit Batok)" src="https://i.ibb.co/dwjT1zKZ/MINDS-Satellite-Hub-Bukit-Batok.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/minds-regional-hub-hougang/"><img alt="MINDS Regional Hub (Hougang)" src="https://i.ibb.co/vCcqbcht/MINDS-Regional-Hub-Hougang.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/minds-regional-hub-woodlands/"><img alt="MINDS Regional Hub (Woodlands)" src="https://i.ibb.co/vCcqbcht/MINDS-Regional-Hub-Hougang.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/mindsg/"><img alt="MINDSG" src="https://i.ibb.co/mrXVYMzm/MINDSG.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/muscular-dystrophy-association-singapore/"><img alt="Muscular Dystrophy Association (Singapore)" src="https://i.ibb.co/v6SSDp88/Muscular-Dystrophy-Association-Singapore.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/rainbow-centre-singapore/"><img alt="Rainbow Centre Singapore" src="https://i.ibb.co/TD2tcWM6/Rainbow-Centre-Singapore.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/singapore-association-for-mental-health/"><img alt="Singapore Association for Mental Health" src="https://i.ibb.co/R43DVF6Q/Singapore-Association-for-Mental-Health.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/singapore-association-of-the-visually-handicapped/"><img alt="Singapore Association of The Visually Handicapped" src="https://i.ibb.co/Jw1Dpzhg/Singapore-Association-of-The-Visually-Handicapped.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/singapore-cheshire-home/"><img alt="Singapore Cheshire Home" src="https://i.ibb.co/pv4PJHz9/Singapore-Cheshire-Home.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/st-andrews-autism-school/"><img alt="St Andrew's Autism School" src="https://i.ibb.co/hqfnnRK/St-Andrews-Autism-School.jpg"></a>
            </div>
            <div class="partner_card">
                <a href="/the-art-faculty/"><img alt="The Art Faculty" src="https://i.ibb.co/LddB62p9/The-Art-Faculty.png"></a>
            </div>
            <div class="partner_card">
                <a href="/thye-hua-kwan-moral-charities/"><img alt="Thye Hua Kwan Moral Charities" src="https://i.ibb.co/v4tb8yrh/Thye-Hua-Kwan-Moral-Charities.jpg"></a>
            </div>
        </div>
    </div>
  </section>
  </section>
