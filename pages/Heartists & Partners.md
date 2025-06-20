---
title: Heartists & Partners
permalink: /heartists-and-partners/
variant: markdown
description: ""
---
<style>
    /* Import Fonts */
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
    
    /* CSS Variables for consistent theming */
    :root {
        --primary-color: #e94e77;
        --secondary-color: #3a5a78;
        --accent-color: #f4b942;
        --text-color: #333333;
        --light-gray: #f5f5f5;
        --medium-gray: #e0e0e0;
        --dark-gray: #666666;
        --white: #ffffff;
        --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        --transition: all 0.3s ease;
    }
    
    /* Base Styles */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: "Inter", sans-serif;
    }
    
    body {
        color: var(--text-color);
        line-height: 1.6;
        background-color: var(--white);
    }
    
    /* Typography */
    h1 {
        font-size: 2.5rem;
        font-weight: 700;
        margin-bottom: 1.5rem;
        color: var(--secondary-color);
    }
    
    h2 {
        font-size: 2rem;
        font-weight: 600;
        margin: 2rem 0 1.5rem;
        color: var(--secondary-color);
    }
    
    p {
        margin-bottom: 1.5rem;
        font-size: 1.1rem;
        color: var(--dark-gray);
    }
    
    /* Layout Components */
    .canvas {
        margin: 0 auto;
        padding: 0 20px;
    }
    
    .relative {
        position: relative;
    }
    
    /* Hero Section */
    .hero {
        padding: 60px 0;
        margin-bottom: 40px;
        border-bottom: 1px solid var(--medium-gray);
    }
    
    .hero .canvas {
        display: flex;
        align-items: center;
        gap: 40px;
    }
    
    .hero_left {
        flex: 1;
    }
    
    .hero_right {
        flex: 1;
    }
    
    .hero_right img {
        width: 100%;
        transition: var(--transition);
    }
    
    .hero_right img:hover {
        transform: scale(1.02);
    }
    
    /* Grid Layout */
    .grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 25px;
        margin-bottom: 60px;
    }
    
    /* Card Component */
    .card {
        border-radius: 12px;
        overflow: hidden;
        box-shadow: var(--shadow);
        transition: var(--transition);
        background-color: var(--white);
        border: 1px solid var(--medium-gray);
    }
    
    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
    }
    
    /* Default image styling for Heartists */
    .card img {
        width: 100%;
        height: 300px;
        object-fit: cover;
        object-position: top;
        display: block;
        transition: var(--transition);
    }
    
    /* Specific positioning for certain images */
    .card[data-artist="elijah-goh"] img {
        object-position: center 40%;
    }
    
    .card[data-artist="evan-goh"] img {
        object-position: center 50%;
    }
    
    .card[data-artist="caden-lee-kai-en"] img {
        object-position: center 20%;
    }
    
    .card[data-artist="christopher-tey-rui-fang"] img {
        object-position: center 20%;
    }
    
    .card[data-artist="gabriel-rhed-osea-longid"] img {
        object-position: center 20%;
    }
    
    .card[data-artist="ling-teck-mong"] img {
        object-position: center 20%;
    }
    
    /* Partner logos should be contained to show the full logo */
    .partners-grid .card img {
        object-fit: contain;
        object-position: center;
        background-color: var(--white);
    }
    
    /* Image container for rotated images */
    .card[data-artist] .img-container {
        position: relative;
        height: 300px;
        overflow: hidden;
    }
    
    @media (max-width: 576px) {
        .card[data-artist] .img-container {
            height: 280px;
        }
    }
    
    /* Image rotations for specific artists */
    .card[data-artist="audrey-ang-pei-yu"] .img-container img,
    .card[data-artist="muhammad-syazwan-bin-rahmat"] .img-container img,
    .card[data-artist="yap-jia-hui"] .img-container img {
        transform: rotate(90deg) scale(1.5);
        object-fit: cover;
        position: absolute;
        height: 100%;
        width: 100%;
        object-position: center;
        top: 0;
        left: 0;
    }
    
    /* General rotation for -90deg images */
    .card[data-artist="linda-wong-pui-see"] .img-container img,
    .card[data-artist="simeon-tan-rui-en"] .img-container img {
        transform: rotate(-90deg) scale(1.5);
        object-fit: cover;
        position: absolute;
        height: 100%;
        width: 100%;
        object-position: center 80%;
        top: 0;
        left: 0;
    }
    
    /* Special positioning for Linda Wong Pui See - eyes covered by top edge */
    .card[data-artist="linda-wong-pui-see"] .img-container img {
        transform: rotate(-90deg) scale(1.1);
        object-fit: cover;
        position: absolute;
        height: 100%;
        width: 100%;
        object-position: top center;
        top: 0;
        left: 0;
    }
    
    /* Special positioning for Moy Saw Han - eyes covered by top edge */
    .card[data-artist="moy-saw-han"] .img-container img {
        transform: rotate(-90deg) scale(1.1);
        object-fit: cover;
        position: absolute;
        height: 100%;
        width: 100%;
        object-position: top center;
        top: 0;
        left: 0;
    }
    
    /* Special positioning for Muhammad Ridhwan Masli - face covered by top edge */
    .card[data-artist="muhammad-ridhwan-masli"] .img-container img {
        transform: rotate(-90deg) scale(1.0);
        object-fit: cover;
        position: absolute;
        height: 100%;
        width: 100%;
        object-position: top center;
        top: 0;
        left: 0;
    }
    
    /* Special positioning for Simeon Tan Rui En - forehead covered by top edge */
    .card[data-artist="simeon-tan-rui-en"] .img-container img {
        object-position: center 40%;
    }
    
    /* Special positioning for Ezra Chan Yi */
    .card[data-artist="ezra-chan-yi"] .img-container img {
        transform: rotate(-90deg) scale(1.7);
        object-fit: cover;
        position: absolute;
        height: 100%;
        width: 100%;
        object-position: 120% top;
        top: 0;
        left: 0;
    }
    
    .card:hover img {
        filter: brightness(1.05);
    }
    
    .card a {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 15px;
        text-decoration: none;
        color: var(--secondary-color);
        font-weight: 600;
        font-size: 1.1rem;
        transition: var(--transition);
    }
    
    .card a:hover {
        background-color: var(--light-gray);
        color: var(--primary-color);
    }
    
    .arrow {
        font-size: 20px;
        transition: var(--transition);
    }
    
    .card:hover .arrow {
        transform: translateX(5px);
        color: var(--primary-color);
    }
    
    /* Section Styling */
    .section-title {
        text-align: center;
        margin: 3rem 0 2rem;
        position: relative;
    }
    
    .section-title:after {
        content: '';
        display: block;
        width: 80px;
        height: 4px;
        background-color: var(--accent-color);
        margin: 15px auto 0;
        border-radius: 2px;
    }
    
    /* Content Container */
    .content-container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
    }
    
    /* Responsive Design */
    @media (max-width: 992px) {
        h1 {
            font-size: 2.2rem;
        }
        
        h2 {
            font-size: 1.8rem;
        }
        
        .grid {
            grid-template-columns: repeat(3, 1fr);
        }
    }
    
    @media (max-width: 768px) {
        .hero .canvas {
            flex-direction: column;
        }
        
        .hero_left, .hero_right {
            width: 100%;
        }
        
        h1 {
            font-size: 2rem;
        }
        
        h2 {
            font-size: 1.6rem;
        }
        
        .grid {
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
    }
    
    @media (max-width: 576px) {
        .grid {
            grid-template-columns: 1fr;
        }
        
        .card img {
            height: 280px;
        }
    }
</style>

<section class="hero">
    <div class="canvas relative">
        <div class="hero_left">
            <h1>Meet our Heartists and Partners</h1>
            <p>Discover the talented Heartists behind the masterpieces and the dedicated partners who have collaborated and supported their journey. Each piece of art they create tells a profound story—a tale of hardship, resilience, triumph, and hope.</p>
        </div>
        <div class="hero_right">
            <img alt="Heartists and Partners" src="https://i.ibb.co/B20TdxHH/Header-Image-1.png">
        </div>
    </div>
</section>

<div class="content-container">
    <h2 class="section-title">Our Heartists</h2>
    <div class="grid">
        <div class="card">
            <img alt="Aubrey Ang" src="https://i.ibb.co/8n8stPm2/Aubrey-Ang.jpg">
            <a href="/aubrey-ang/">Aubrey Ang <span class="arrow">→</span></a>
        </div>
        <div data-artist="audrey-ang-pei-yu" class="card">
            <div class="img-container">
                <img alt="Audrey Ang Pei Yu" src="https://i.ibb.co/nswsmt76/Audrey-Ang-Pei-Yu.jpg">
            </div>
            <a href="/audrey-ang-pei-yu/">Audrey Ang Pei Yu <span class="arrow">→</span></a>
        </div>
        <div data-artist="caden-lee-kai-en" class="card">
            <img alt="Caden Lee Kai En" src="https://i.ibb.co/R4Yd728q/Caden-Lee-Kai-En.jpg">
            <a href="/caden-lee-kai-en/">Caden Lee Kai En <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Choy Eu Jun, Julian" src="https://i.ibb.co/398PyJMz/Choy-Eu-Jun-Julian.jpg">
            <a href="/choy-eu-jun-julian/">Choy Eu Jun, Julian <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Christopher Daniel Widjaja" src="https://i.ibb.co/7t5cBn0C/Christopher-Daniel-Widjaja.jpg">
            <a href="/christopher-daniel-widjaja/">Christopher Daniel Widjaja <span class="arrow">→</span></a>
        </div>
        <div data-artist="christopher-tey-rui-fang" class="card">
            <img alt="Christopher Tey Rui Fang" src="https://i.ibb.co/qMqtP0Lq/Christopher-Tey-Rui-Fang.jpg">
            <a href="/christopher-tey-rui-fang/">Christopher Tey Rui Fang <span class="arrow">→</span></a>
        </div>
        <div data-artist="elijah-goh" class="card">
            <img alt="Elijah Goh" src="https://i.ibb.co/yBsnfyzt/Elijah-Goh.jpg">
            <a href="/elijah-goh/">Elijah Goh <span class="arrow">→</span></a>
        </div>
        <div data-artist="evan-goh" class="card">
            <img alt="Evan Goh" src="https://i.ibb.co/ZzrcRr6X/Evan-Goh.jpg">
            <a href="/evan-goh/">Evan Goh <span class="arrow">→</span></a>
        </div>
        <div data-artist="ezra-chan-yi" class="card">
            <div class="img-container">
                <img alt="Ezra Chan Yi" src="https://i.ibb.co/TDp8sgCy/Ezra-Chan-Yi.jpg">
            </div>
            <a href="/ezra-chan-yi/">Ezra Chan Yi <span class="arrow">→</span></a>
        </div>
        <div data-artist="gabriel-rhed-osea-longid" class="card">
            <img alt="Gabriel Rhed Osea Longid" src="https://i.ibb.co/My6VkYZy/Gabriel-Rhed-Osea-Longid.jpg">
            <a href="/gabriel-rhed-osea-longid/">Gabriel Rhed Osea Longid <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Isabella Grace Wilfred (Izzy)" src="https://i.ibb.co/fc19WHv/Isabella-Grace-Wilfred-Izzy.jpg">
            <a href="/isabella-grace-wilfred-izzy/">Isabella Grace Wilfred (Izzy) <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Janetta Tan" src="https://i.ibb.co/C5v80sjm/Janetta-Tan.jpg">
            <a href="/janetta-tan/">Janetta Tan <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Jonas Teo" src="https://i.ibb.co/v6kbqPpw/Jonas-Teo.jpg">
            <a href="/jonas-teo/">Jonas Teo <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Joshua Wang Yu Hui" src="https://i.ibb.co/67MFHSFn/Joshua-Wang-Yu-Hui.jpg">
            <a href="/joshua-wang-yu-hui/">Joshua Wang Yu Hui <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Alex Lim" src="https://i.ibb.co/7xjHgwYF/Alex-Lim.jpg">
            <a href="/alex-lim/">Alex Lim <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Koh Xin Abraham" src="https://i.ibb.co/DFNSSz0/Koh-Xin-Abraham.jpg">
            <a href="/koh-xin-abraham/">Koh Xin Abraham <span class="arrow">→</span></a>
        </div>
        <div data-artist="linda-wong-pui-see" class="card">
            <div class="img-container">
                <img alt="Linda Wong Pui See" src="https://i.ibb.co/sYDstbz/Linda-Wong-Pui-See.jpg">
            </div>
            <a href="/linda-wong-pui-see/">Linda Wong Pui See <span class="arrow">→</span></a>
        </div>
        <div data-artist="ling-teck-mong" class="card">
            <img alt="Ling Teck Mong" src="https://i.ibb.co/WvJvp3qT/Ling-Teck-Mong.jpg">
            <a href="/ling-teck-mong/">Ling Teck Mong <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Lucas Teo" src="https://i.ibb.co/WpcCvnZF/Lucas-Teo.jpg">
            <a href="/lucas-teo/">Lucas Teo <span class="arrow">→</span></a>
        </div>
        <div data-artist="moy-saw-han" class="card">
            <div class="img-container">
                <img alt="Moy Saw Han" src="https://i.ibb.co/23p34PZP/Moy-Saw-Han.jpg">
            </div>
            <a href="/moy-saw-han/">Moy Saw Han <span class="arrow">→</span></a>
        </div>
        <div data-artist="muhammad-ridhwan-masli" class="card">
            <div class="img-container">
                <img alt="Muhammad Ridhwan Masli" src="https://i.ibb.co/Kcw22L29/Muhammad-Ridhwan-Masli.jpg">
            </div>
            <a href="/muhammad-ridhwan-masli/">Muhammad Ridhwan Masli <span class="arrow">→</span></a>
        </div>
        <div data-artist="muhammad-syazwan-bin-rahmat" class="card">
            <div class="img-container">
                <img alt="Muhammad Syazwan Bin Rahmat" src="https://i.ibb.co/DH3g8TNY/Muhammad-Syazwan-Bin-Rahmat.jpg">
            </div>
            <a href="/muhammad-syazwan-bin-rahmat/">Muhammad Syazwan Bin Rahmat <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Ng Jun Yao" src="https://i.ibb.co/dsz1pXX9/Ng-Jun-Yao.jpg">
            <a href="/ng-jun-yao/">Ng Jun Yao <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Nur Amalina Binte Rahmat" src="https://i.ibb.co/Zv425CQ/Nur-Amalina-Binte-Rahmat.jpg">
            <a href="/nur-amalina-binte-rahmat/">Nur Amalina Binte Rahmat <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Ong Chee Hwee" src="https://i.ibb.co/6R5wmXxJ/Ong-Chee-Hwee.jpg">
            <a href="/ong-chee-hwee/">Ong Chee Hwee <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Serene Keen" src="https://i.ibb.co/LdnRJtjf/Serene-Keen.jpg">
            <a href="/serene-keen/">Serene Keen <span class="arrow">→</span></a>
        </div>
        <div data-artist="simeon-tan-rui-en" class="card">
            <div class="img-container">
                <img alt="Simeon Tan Rui En" src="https://i.ibb.co/Csb3R5XW/Simeon-Tan-Rui-En.jpg">
            </div>
            <a href="/simeon-tan-rui-en/">Simeon Tan Rui En <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Titus Teo" src="https://i.ibb.co/bj7rFrrH/Titus-Teo.jpg">
            <a href="/titus-teo/">Titus Teo <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Vincent Seet (Seet Kie Hong)" src="https://i.ibb.co/YH4H1bp/Vincent-Seet-Seet-Kie-Hong.jpg">
            <a href="/vincent-seet-kie-hong/">Vincent Seet (Seet Kie Hong) <span class="arrow">→</span></a>
        </div>
        <div data-artist="yap-jia-hui" class="card">
            <div class="img-container">
                <img alt="Yap Jia Hui" src="https://i.ibb.co/21vpFrys/Yap-Jia-Hui.jpg">
            </div>
            <a href="/yap-jia-hui/">Yap Jia Hui <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Zayne Pua" src="https://i.ibb.co/1t4zkSFy/Zayne-Pua.jpg">
            <a href="/zayne-pua/">Zayne Pua <span class="arrow">→</span></a>
        </div>
    </div>
    <h2 class="section-title">Our Partners</h2>
    <div class="grid partners-grid">
        <div class="card">
            <img alt="APSN Katong School" src="https://i.ibb.co/tMjTRhh4/APSN-Katong-School.jpg">
            <a href="/apsn-katong-school/">APSN Katong School <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="ARTDIS Singapore Ltd." src="https://i.ibb.co/dwz4x87d/ARTDIS-Singapore-Ltd.jpg">
            <a href="/artdis-singapore-ltd/">ARTDIS Singapore Ltd. <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Artzillions" src="https://i.ibb.co/99kFS3zR/Artzillions.jpg">
            <a href="/artzillions/">Artzillions <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="AWWA School" src="https://i.ibb.co/JjQsbGvH/AWWA-School.jpg">
            <a href="/awwa-school/">AWWA School <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Bethesda CARE Centre" src="https://i.ibb.co/xtqk5Z32/Bethesda-CARE-Centre.jpg">
            <a href="/bethesda-care-centre/">Bethesda CARE Centre <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Bizlink Centre Singapore Ltd" src="https://i.ibb.co/bRsgzVfn/Bizlink-Centre-Singapore-Ltd.jpg">
            <a href="/bizlink-centre-singapore/">Bizlink Centre Singapore Ltd <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Cerebral Palsy Alliance Singapore (CPAS GROW)" src="https://i.ibb.co/qMSPk60B/Cerabral-Palsy-Alliance-Singapore-CPAS-GROW.jpg">
            <a href="/cerebral-palsy-alliance-singapore-cpas-grow/">Cerebral Palsy Alliance Singapore (CPAS GROW) <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Cerebral Palsy Alliance Singapore (CPAS School)" src="https://i.ibb.co/qMSPk60B/Cerabral-Palsy-Alliance-Singapore-CPAS-GROW.jpg">
            <a href="/cerebral-palsy-alliance-singapore-cpas-school/">Cerebral Palsy Alliance Singapore (CPAS School) <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Christian Outreach to the Handicapped" src="https://i.ibb.co/j9wX69s7/Christian-Outreach-to-the-Handicapped.jpg">
            <a href="/christian-outreach-to-the-handicapped/">Christian Outreach to the Handicapped <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Extraordinary People Limited" src="https://i.ibb.co/XZkWJkVT/Extraordinary-People-Limited.jpg">
            <a href="/extraordinary-people-limited/">Extraordinary People Limited <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Friends of the Disabled Society" src="https://i.ibb.co/Z6n36HfD/Friends-of-the-Disabled-Society.jpg">
            <a href="/friends-of-the-disabled-society/">Friends of the Disabled Society <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Handicaps Welfare Association" src="https://i.ibb.co/PGRCRXK9/Handicaps-Welfare-Association.jpg">
            <a href="/handicaps-welfare-association/">Handicaps Welfare Association <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="JOURNEY by TOUCH" src="https://i.ibb.co/bjBtqcHV/JOURNEY-by-TOUCH.jpg">
            <a href="/journey-by-touch/">JOURNEY by TOUCH <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Metta Welfare Association (Arts @ Metta)" src="https://i.ibb.co/6R5grX0m/Metta-Welfare-Association-Arts-Metta.jpg">
            <a href="/metta-welfare-association/">Metta Welfare Association (Arts @ Metta) <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Mouth and Foot Painting Artists" src="https://i.ibb.co/gL1Xd3X1/Mouth-and-Foot-Painting-Artists.jpg">
            <a href="/mouth-and-foot-painting-artists/">Mouth and Foot Painting Artists <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="MINDS Satellite Hub (Bukit Batok)" src="https://i.ibb.co/dwjT1zKZ/MINDS-Satellite-Hub-Bukit-Batok.jpg">
            <a href="/minds-satellite-hub-bukit-batok/">MINDS Satellite Hub (Bukit Batok) <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="MINDS Regional Hub (Hougang)" src="https://i.ibb.co/vCcqbcht/MINDS-Regional-Hub-Hougang.jpg">
            <a href="/minds-regional-hub-hougang/">MINDS Regional Hub (Hougang) <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="MINDS Regional Hub (Woodlands)" src="https://i.ibb.co/vCcqbcht/MINDS-Regional-Hub-Hougang.jpg">
            <a href="/minds-regional-hub-woodlands/">MINDS Regional Hub (Woodlands) <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="MINDSG" src="https://i.ibb.co/mrXVYMzm/MINDSG.jpg">
            <a href="/mindsg/">MINDSG <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Muscular Dystrophy Association (Singapore)" src="https://i.ibb.co/v6SSDp88/Muscular-Dystrophy-Association-Singapore.jpg">
            <a href="/muscular-dystrophy-association-singapore/">Muscular Dystrophy Association (Singapore) <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Rainbow Centre Singapore" src="https://i.ibb.co/TD2tcWM6/Rainbow-Centre-Singapore.jpg">
            <a href="/rainbow-centre-singapore/">Rainbow Centre Singapore <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Singapore Association for Mental Health" src="https://i.ibb.co/R43DVF6Q/Singapore-Association-for-Mental-Health.jpg">
            <a href="/singapore-association-for-mental-health/">Singapore Association for Mental Health <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Singapore Association of The Visually Handicapped" src="https://i.ibb.co/Jw1Dpzhg/Singapore-Association-of-The-Visually-Handicapped.jpg">
            <a href="/singapore-association-of-the-visually-handicapped/">Singapore Association of The Visually Handicapped <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Singapore Cheshire Home" src="https://i.ibb.co/pv4PJHz9/Singapore-Cheshire-Home.jpg">
            <a href="/singapore-cheshire-home/">Singapore Cheshire Home <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="St Andrew's Autism School" src="https://i.ibb.co/hqfnnRK/St-Andrews-Autism-School.jpg">
            <a href="/st-andrews-autism-school/">St Andrew's Autism School <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="The Art Faculty" src="https://i.ibb.co/LddB62p9/The-Art-Faculty.png">
            <a href="/the-art-faculty/">The Art Faculty <span class="arrow">→</span></a>
        </div>
        <div class="card">
            <img alt="Thye Hua Kwan Moral Charities" src="https://i.ibb.co/v4tb8yrh/Thye-Hua-Kwan-Moral-Charities.jpg">
            <a href="/thye-hua-kwan-moral-charities/">Thye Hua Kwan Moral Charities <span class="arrow">→</span></a>
        </div>
    </div>
</div>
