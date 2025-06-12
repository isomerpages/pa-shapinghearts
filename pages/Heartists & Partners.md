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
            <img src="https://i.ibb.co/jTgGjSr/Shaping-Hearts-Artist-Ashley-01.jpg">
            <a href="/ashley/">Ashley <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"> </a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/hZrXVkH/Shaping-Hearts-Artist-EZRA-01.jpg">
            <a href="/ezra/">Ezra <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
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
        <div class="team_card">
            <img src="https://i.ibb.co/jG8vzVP/Christopher-Daniel-Widjaja.jpg">
            <a href="/christopher-daniel-widjaja/">Christopher Daniel Widjaja <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/ChhYSQB/Christopher-Tey-Rui-Fang.jpg">
            <a href="/christopher-tey-rui-fang/">Christopher Tey Rui Fang <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/g9LG697/Elijah-Goh.jpg">
            <a href="/elijah-goh/">Elijah Goh <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/MPxbNvj/Evan-Goh.jpg">
            <a href="/evan-goh/">Evan Goh <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/Wt4hcT8/Isabella-Grace-Wilfred.jpg">
            <a href="/isabella-grace-wilfred-izzy/">Isabella Grace Wilfred (Izzy) <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/yyMX5w5/Joshua-Wang.jpg">
            <a href="/joshua-wang-yu-hui/">Joshua Wang Yu Hui <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/FDGzwp8/Linda-Wong.jpg">
            <a href="/linda-wong-pui-see/">Linda Wong Pui See <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
        </div>
        <div class="team_card">
            <img src="https://i.ibb.co/D89KsF6/Rayden-Yeow.jpg">
            <a href="/rayden-yeow/">Rayden Yeow <img src="https://i.ibb.co/K99VVxJ/Arrow.png" style="width: 30px !important"></a>
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
                <a href="/apsn/"><img alt="APSN" src="https://i.ibb.co/5xC1Wdb/Frame-217-1.png"></a>
            </div>
            <div class="partner_card">
                <a href="/awwa-school/"><img src="https://i.ibb.co/YDJPN5d/AWWA.png"></a>
            </div>
            <div class="partner_card">
                <a href="/artdis-singapore-ltd/"><img alt="artdis" src="https://i.ibb.co/ssmZ13q/Frame-217.png"></a>
            </div>
            <div class="partner_card">
                <a href="/bizlink-centre-singapore/"><img src="https://i.ibb.co/5Wwy12d/Bizlink-Centre-Singapore.png"></a>
            </div>
            <div class="partner_card">
                <a href="/bethesda-care-centre/"><img alt="bethesda" src="https://i.ibb.co/Qr6gBxt/Group-7270-1.png"></a>
            </div>
            <div class="partner_card">
                <a href="/cerebral-palsy-alliance-singapore-cpas-school/"><img src="https://i.ibb.co/t3qhTZ9/Cerebral-Palsy-Alliance-Singapore-CPAS-School.png"></a>
            </div>
            <div class="partner_card">
                <a href="/christian-outreach-to-the-handicapped/"><img src="https://i.ibb.co/25GsqMX/Christian-outreach.png"></a>
            </div>
            <div class="partner_card">
                <a href="/down-syndrome-association-singapore/"><img src="https://i.ibb.co/bJ7vD0Q/Down-Syndrome-Association-Singapore.png"></a>
            </div>
            <div class="partner_card">
                <a href="/extraordinary-people-limited/"><img src="https://i.ibb.co/MZWSKDp/Extra-Ordinary-People.png"></a>
            </div>
            <div class="partner_card">
                <a href="/friends-of-the-disabled-society-fds/"><img src="https://i.ibb.co/nbddZ6y/Friends-of-the-Disabled-Society-FDS.png"></a>
            </div>
            <div class="partner_card">
                <a href="/handicaps-welfare-association/"><img src="https://i.ibb.co/YbdG585/Handicapped-Welfare-Association.png"></a>
            </div>
            <div class="partner_card">
                <a href="/love-nils/"><img src="https://i.ibb.co/92YfPh7/love-nils-trp.png"></a>
            </div>
            <div class="partner_card">
                <a href="/metta-welfare-association/"><img src="https://i.ibb.co/FHt66wn/Partners-metta.png"></a>
            </div>
            <div class="partner_card">
                <a href="/muscular-dystrophy-association-singapore/"><img src="https://i.ibb.co/QnNXmv3/Muscular-Dystrophy-Association-Singapore.png"></a>
            </div>
            <div class="partner_card">
                <a href="/muscular-dystrophy-association-singapore/"><img src="https://i.ibb.co/Nx0KgW4/Mouth-Foot-Painting-Artists-Pte-Ltd-1.png"></a>
            </div>
            <div class="partner_card">
                <a href="/minds/"><img src="https://i.ibb.co/qN9gnTs/MINDS.png"></a>
            </div>
            <div class="partner_card">
                <a href="/pathlight-school/"><img src="https://i.ibb.co/dGp4NyQ/pathlight-trp.png"></a>
            </div>
            <div class="partner_card">
                <a href="/singapore-association-for-mental-health-samh/"><img src="https://i.ibb.co/89Wx44M/Singapore-Association-for-Mental-Health-SAMH.png"></a>
            </div>
            <div class="partner_card">
                <a href="/singapore-association-of-the-visually-handicapped/"><img alt="savh" src="https://i.ibb.co/Fhhkgrk/Group-4171.png"></a>
            </div>
            <div class="partner_card">
                <a href="/thk-homes-for-disabled/"><img src="https://i.ibb.co/mb1MSWS/thye-hua-trp.png"></a>
            </div>
            <div class="partner_card">
                <a href="/touch-community-services/"><img alt="Journey by Touch" src="https://i.ibb.co/6WJ1KjY/Frame-206.png"></a>
            </div>
        </div>
    </div>
  </section>
  </section>