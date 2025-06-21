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
        padding: 0;
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
    
    /* Partner logos should be contained to show the full logo */
    .partners-grid .card img {
        object-fit: contain;
        object-position: center;
        background-color: var(--white);
    }
    
    @media (max-width: 576px) {
        .card[data-artist] .img-container {
            height: 280px;
        }
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
        width: 100%;
        margin: 0 auto;
        padding: 20px 0;
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
<p>Discover the talented Heartists behind the masterpieces and the dedicated partners who have collaborated and supported their journey. Each piece of art they create tells a profound story—a tale of hardship, resilience, triumph, and hope. Shaping Hearts 2025 features over 210 participating artists with disabilities.</p>
</div>
<div class="hero_right">
<img src="https://i.ibb.co/B20TdxHH/Header-Image-1.png" alt="Heartists and Partners">
</div>
</div>
</section>
<div class="content-container">
<h2 class="section-title">Our Heartists</h2>
<div class="grid">
<div class="card">
<img src="https://i.ibb.co/6JcCLTxw/Aubrey-Ang.jpg" alt="Aubrey Ang">
<a href="/aubrey-ang/">Aubrey Ang <span class="arrow">→</span></a>
</div>
<div data-artist="audrey-ang-pei-yu" class="card">
<div class="img-container">
<img src="https://i.ibb.co/4wKcdDvJ/Audrey-Ang-Pei-Yu.jpg" alt="Audrey Ang Pei Yu">
</div>
<a href="/audrey-ang-pei-yu/">Audrey Ang Pei Yu <span class="arrow">→</span></a>
</div>
<div data-artist="caden-lee-kai-en" class="card">
<img src="https://i.ibb.co/VpCZc5Zw/Caden-Lee-Kai-En.jpg" alt="Caden Lee Kai En">
<a href="/caden-lee-kai-en/">Caden Lee Kai En <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/1t99TnPX/Choy-Eu-Jun-Julian.jpg" alt="Choy Eu Jun, Julian">
<a href="/choy-eu-jun-julian/">Choy Eu Jun, Julian <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/0y8rZcs1/Christopher-Daniel-Widjaja.jpg" alt="Christopher Daniel Widjaja">
<a href="/christopher-daniel-widjaja/">Christopher Daniel Widjaja <span class="arrow">→</span></a>
</div>
<div data-artist="christopher-tey-rui-fang" class="card">
<img src="https://i.ibb.co/7xVP4gR8/Christopher-Tey-Rui-Fang.jpg" alt="Christopher Tey Rui Fang">
<a href="/christopher-tey-rui-fang/">Christopher Tey Rui Fang <span class="arrow">→</span></a>
</div>
<div data-artist="elijah-goh" class="card">
<img src="https://i.ibb.co/KxzTJGh5/Elijah-Goh.jpg" alt="Elijah Goh">
<a href="/elijah-goh/">Elijah Goh <span class="arrow">→</span></a>
</div>
<div data-artist="evan-goh" class="card">
<img src="https://i.ibb.co/rK75q4p2/Evan-Goh.jpg" alt="Evan Goh">
<a href="/evan-goh/">Evan Goh <span class="arrow">→</span></a>
</div>
<div data-artist="ezra-chan-yi" class="card">
<div class="img-container">
<img src="https://i.ibb.co/YFRDhNW8/Ezra-Chan-Yi.jpg" alt="Ezra Chan Yi">
</div>
<a href="/ezra-chan-yi/">Ezra Chan Yi <span class="arrow">→</span></a>
</div>
<div data-artist="gabriel-rhed-osea-longid" class="card">
<img src="https://i.ibb.co/BHjLxgp5/Gabriel-Rhed-Osea-Longid.jpg" alt="Gabriel Rhed Osea Longid">
<a href="/gabriel-rhed-osea-longid/">Gabriel Rhed Osea Longid <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/23mzB4FM/Isabella-Grace-Wilfred-Izzy.jpg" alt="Isabella Grace Wilfred (Izzy)">
<a href="/isabella-grace-wilfred-izzy/">Isabella Grace Wilfred (Izzy) <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/tpNGQrw3/Janetta-Tan.jpg" alt="Janetta Tan">
<a href="/janetta-tan/">Janetta Tan <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/jvZ6ntmk/Jonas-teo.jpg" alt="Jonas Teo">
<a href="/jonas-teo/">Jonas Teo <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/dJs4DrY0/Joshua-Wang-Yu-Hui.jpg" alt="Joshua Wang Yu Hui">
<a href="/joshua-wang-yu-hui/">Joshua Wang Yu Hui <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/xqtH8pTp/Alex-Lim.jpg" alt="Alex Lim">
<a href="/alex-lim/">Alex Lim <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/F4HKrF6W/Koh-Xin-Abraham.jpg" alt="Koh Xin Abraham">
<a href="/koh-xin-abraham/">Koh Xin Abraham <span class="arrow">→</span></a>
</div>
<div data-artist="linda-wong-pui-see" class="card">
<div class="img-container">
<img src="https://i.ibb.co/DDSrK4Xt/Linda-Wong-Pui-See.jpg" alt="Linda Wong Pui See">
</div>
<a href="/linda-wong-pui-see/">Linda Wong Pui See <span class="arrow">→</span></a>
</div>
<div data-artist="ling-teck-mong" class="card">
<img src="https://i.ibb.co/KzrpWjQ7/Ling-Teck-Mong.jpg" alt="Ling Teck Mong">
<a href="/ling-teck-mong/">Ling Teck Mong <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/wNjZWGH0/Lucas-Teo.jpg" alt="Lucas Teo">
<a href="/lucas-teo/">Lucas Teo <span class="arrow">→</span></a>
</div>
<div data-artist="moy-saw-han" class="card">
<div class="img-container">
<img src="https://i.ibb.co/XfsxkLSh/Moy-Saw-Han.jpg" alt="Moy Saw Han">
</div>
<a href="/moy-saw-han/">Moy Saw Han <span class="arrow">→</span></a>
</div>
<div data-artist="muhammad-ridhwan-masli" class="card">
<div class="img-container">
<img src="https://i.ibb.co/xtszv4fT/Muhammad-Ridhwan-Masli.jpg" alt="Muhammad Ridhwan Masli">
</div>
<a href="/muhammad-ridhwan-masli/">Muhammad Ridhwan Masli <span class="arrow">→</span></a>
</div>
<div data-artist="muhammad-syazwan-bin-rahmat" class="card">
<div class="img-container">
<img src="https://i.ibb.co/84RMjDxm/Muhammad-Syazwan-Bin-Rahmat.jpg" alt="Muhammad Syazwan Bin Rahmat">
</div>
<a href="/muhammad-syazwan-bin-rahmat/">Muhammad Syazwan Bin Rahmat <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/nsrbcfHK/Ng-Jun-Yao.jpg" alt="Ng Jun Yao">
<a href="/ng-jun-yao/">Ng Jun Yao <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/KzRNq9bP/Nur-Amalina-Binte-Rahmat.jpg" alt="Nur Amalina Binte Rahmat">
<a href="/nur-amalina-binte-rahmat/">Nur Amalina Binte Rahmat <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/DfKXY89t/Ong-Chee-Hwee.jpg" alt="Ong Chee Hwee">
<a href="/ong-chee-hwee/">Ong Chee Hwee <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/bMYjMNXJ/Serene-Keen.jpg" alt="Serene Keen">
<a href="/serene-keen/">Serene Keen <span class="arrow">→</span></a>
</div>
<div data-artist="simeon-tan-rui-en" class="card">
<div class="img-container">
<img src="https://i.ibb.co/S4GTwKFD/Simeon-Tan-Rui-En.jpg" alt="Simeon Tan Rui En">
</div>
<a href="/simeon-tan-rui-en/">Simeon Tan Rui En <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/Qj17G4cM/Titus-Teo.jpg" alt="Titus Teo">
<a href="/titus-teo/">Titus Teo <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/67JbJ0g7/Vincent-Seet-Kie-Hong.jpg" alt="Vincent Seet (Seet Kie Hong)">
<a href="/vincent-seet-kie-hong/">Vincent Seet (Seet Kie Hong) <span class="arrow">→</span></a>
</div>
<div data-artist="yap-jia-hui" class="card">
<div class="img-container">
<img src="https://i.ibb.co/whCbTqNH/Yap-Jia-Hui.jpg" alt="Yap Jia Hui">
</div>
<a href="/yap-jia-hui/">Yap Jia Hui <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/xT8h0tB/Zayne-Pua.jpg" alt="Zayne Pua">
<a href="/zayne-pua/">Zayne Pua <span class="arrow">→</span></a>
</div>
</div>
<h2 class="section-title">Our Partners</h2>
<div class="grid partners-grid">
<div class="card">
<img src="https://i.ibb.co/tMjTRhh4/APSN-Katong-School.jpg" alt="APSN Katong School">
<a href="/apsn-katong-school/">APSN Katong School <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/dwz4x87d/ARTDIS-Singapore-Ltd.jpg" alt="ARTDIS Singapore Ltd.">
<a href="/artdis-singapore-ltd/">ARTDIS Singapore Ltd. <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/99kFS3zR/Artzillions.jpg" alt="Artzillions">
<a href="/artzillions/">Artzillions <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/JjQsbGvH/AWWA-School.jpg" alt="AWWA School">
<a href="/awwa-school/">AWWA School <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/xtqk5Z32/Bethesda-CARE-Centre.jpg" alt="Bethesda CARE Centre">
<a href="/bethesda-care-centre/">Bethesda CARE Centre <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/bRsgzVfn/Bizlink-Centre-Singapore-Ltd.jpg" alt="Bizlink Centre Singapore Ltd">
<a href="/bizlink-centre-singapore/">Bizlink Centre Singapore Ltd <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/qMSPk60B/Cerabral-Palsy-Alliance-Singapore-CPAS-GROW.jpg" alt="Cerebral Palsy Alliance Singapore (CPAS GROW)">
<a href="/cerebral-palsy-alliance-singapore-cpas-grow/">Cerebral Palsy Alliance Singapore (CPAS GROW) <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/qMSPk60B/Cerabral-Palsy-Alliance-Singapore-CPAS-GROW.jpg" alt="Cerebral Palsy Alliance Singapore (CPAS School)">
<a href="/cerebral-palsy-alliance-singapore-cpas-school/">Cerebral Palsy Alliance Singapore (CPAS School) <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/0p6MXPTW/christian-outreach.jpg" alt="Christian Outreach to the Handicapped">
<a href="/christian-outreach-to-the-handicapped/">Christian Outreach to the Handicapped <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/XZkWJkVT/Extraordinary-People-Limited.jpg" alt="Extraordinary People Limited">
<a href="/extraordinary-people-limited/">Extraordinary People Limited <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/Z6n36HfD/Friends-of-the-Disabled-Society.jpg" alt="Friends of the Disabled Society">
<a href="/friends-of-the-disabled-society/">Friends of the Disabled Society <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/PGRCRXK9/Handicaps-Welfare-Association.jpg" alt="Handicaps Welfare Association">
<a href="/handicaps-welfare-association/">Handicaps Welfare Association <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/bjBtqcHV/JOURNEY-by-TOUCH.jpg" alt="JOURNEY by TOUCH">
<a href="/journey-by-touch/">JOURNEY by TOUCH <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/6R5grX0m/Metta-Welfare-Association-Arts-Metta.jpg" alt="Metta Welfare Association (Arts @ Metta)">
<a href="/metta-welfare-association/">Metta Welfare Association (Arts @ Metta) <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/gL1Xd3X1/Mouth-and-Foot-Painting-Artists.jpg" alt="Mouth and Foot Painting Artists">
<a href="/mouth-and-foot-painting-artists/">Mouth and Foot Painting Artists <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/dwjT1zKZ/MINDS-Satellite-Hub-Bukit-Batok.jpg" alt="MINDS Satellite Hub (Bukit Batok)">
<a href="/minds-satellite-hub-bukit-batok/">MINDS Satellite Hub (Bukit Batok) <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/vCcqbcht/MINDS-Regional-Hub-Hougang.jpg" alt="MINDS Regional Hub (Hougang)">
<a href="/minds-regional-hub-hougang/">MINDS Regional Hub (Hougang) <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/vCcqbcht/MINDS-Regional-Hub-Hougang.jpg" alt="MINDS Regional Hub (Woodlands)">
<a href="/minds-regional-hub-woodlands/">MINDS Regional Hub (Woodlands) <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/mrXVYMzm/MINDSG.jpg" alt="MINDSG">
<a href="/mindsg/">MINDSG <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/v6SSDp88/Muscular-Dystrophy-Association-Singapore.jpg" alt="Muscular Dystrophy Association (Singapore)">
<a href="/muscular-dystrophy-association-singapore/">Muscular Dystrophy Association (Singapore) <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/TD2tcWM6/Rainbow-Centre-Singapore.jpg" alt="Rainbow Centre Singapore">
<a href="/rainbow-centre-singapore/">Rainbow Centre Singapore <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/R43DVF6Q/Singapore-Association-for-Mental-Health.jpg" alt="Singapore Association for Mental Health">
<a href="/singapore-association-for-mental-health/">Singapore Association for Mental Health <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/Jw1Dpzhg/Singapore-Association-of-The-Visually-Handicapped.jpg" alt="Singapore Association of The Visually Handicapped">
<a href="/singapore-association-of-the-visually-handicapped/">Singapore Association of The Visually Handicapped <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/pv4PJHz9/Singapore-Cheshire-Home.jpg" alt="Singapore Cheshire Home">
<a href="/singapore-cheshire-home/">Singapore Cheshire Home <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/hqfnnRK/St-Andrews-Autism-School.jpg" alt="St Andrew's Autism School">
<a href="/st-andrews-autism-school/">St Andrew's Autism School <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/W4jQ8WWT/the-art-faculty.jpg" alt="The Art Faculty">
<a href="/the-art-faculty/">The Art Faculty <span class="arrow">→</span></a>
</div>
<div class="card">
<img src="https://i.ibb.co/v4tb8yrh/Thye-Hua-Kwan-Moral-Charities.jpg" alt="Thye Hua Kwan Moral Charities">
<a href="/thye-hua-kwan-moral-charities/">Thye Hua Kwan Moral Charities <span class="arrow">→</span></a>
</div>
</div>
</div>