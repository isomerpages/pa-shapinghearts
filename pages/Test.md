---
title: Test
permalink: /test/
variant: markdown
description: ""
---
```



    
    
    <title>Shaping Hearts</title>
    
     
                                                                                                                                                             
    
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Oswald:wght@200..700&display=swap');
            :root {
                --primary-clr: #DF366D;
                --secondary-clr: #28449C;
                --danger-clr: #E7004C;
                --white-clr: #fff;
                --title-clr: #333333;
                --body-clr: #4A4A4A;
                --body-font: "Open Sans", sans-serif;
                --title-font: "Oswald", sans-serif;
            }
            /*============================= bootstrap =============================*/
            .navbar>.container, .navbar>.container-fluid, .navbar>.container-lg, .navbar>.container-md, .navbar>.container-sm, .navbar>.container-xl,
            .navbar>.container-xxl {
                display: flex;
                flex-wrap: inherit;
                align-items: center;
                justify-content: space-between;
            }
            .container, .container-lg, .container-md, .container-sm, .container-xl, .container-xxl {
                max-width: 1400px;
            }
            .container, .container-fluid, .container-lg, .container-md, .container-sm, .container-xl, .container-xxl {
                --bs-gutter-x: 1.5rem;
                --bs-gutter-y: 0;
                width: 100%;
                padding-right: calc(var(--bs-gutter-x) * .5);
                padding-left: calc(var(--bs-gutter-x) * .5);
                margin-right: auto;
                margin-left: auto;
            }
            .row {
                --bs-gutter-x: 1.5rem;
                --bs-gutter-y: 0;
                display: flex;
                flex-wrap: wrap;
                margin-top: calc(-1 * var(--bs-gutter-y));
                margin-right: calc(-.5 * var(--bs-gutter-x));
                margin-left: calc(-.5 * var(--bs-gutter-x));
            }
            .row>* {
                flex-shrink: 0;
                width: 100%;
                max-width: 100%;
                padding-right: calc(var(--bs-gutter-x) * .5);
                padding-left: calc(var(--bs-gutter-x) * .5);
                margin-top: var(--bs-gutter-y);
            }
            .navbar-collapse {
                flex-basis: 100%;
                flex-grow: 1;
                align-items: center;
            }
            ul.navbar-nav {
                flex-direction: row;
                display: flex;
                margin-left: auto;
                justify-content: end;
            }
            .mx-auto {
                margin-right: auto!important;
                margin-left: auto!important;
            }
            @media (min-width: 1200px) {
                .navbar-expand-xl .navbar-collapse {
                    display: flex !important;
                    flex-basis: auto;
                }
            }
            @media (min-width: 768px) {
                .col-md-1 {
                    flex: 0 0 auto;
                    width: 8.33333333%;
                }
                .col-md-2 {
                    flex: 0 0 auto;
                    width: 16.66666667%;
                }
                .col-md-3 {
                    flex: 0 0 auto;
                    width: 25%;
                }
                .col-md-4 {
                    flex: 0 0 auto;
                    width: 33.33333333%;
                }
                .col-md-5 {
                    flex: 0 0 auto;
                    width: 41.66666667%;
                }
                .col-md-6 {
                    flex: 0 0 auto;
                    width: 50%;
                }
                .col-md-7 {
                    flex: 0 0 auto;
                    width: 58.33333333%;
                }
                .col-md-8 {
                    flex: 0 0 auto;
                    width: 66.66666667%;
                }
                .col-md-9 {
                    flex: 0 0 auto;
                    width: 75%;
                }
                .col-md-10 {
                    flex: 0 0 auto;
                    width: 83.33333333%;
                }
                .col-md-11 {
                    flex: 0 0 auto;
                    width: 91.66666667%;
                }
                .col-md-12 {
                    flex: 0 0 auto;
                    width: 100%;
                }
            }
            /*============================= bootstrap end =============================*/
            /*============================= common style =============================*/
            *, :after, :before {
                -webkit-box-sizing: border-box;
                box-sizing: border-box;
            }
            audio,canvas,iframe,img,svg,video {
                vertical-align: middle;
            }
            :link {
                text-decoration: none;
            }
            body {
                color: var(--body-clr);
                margin: 0;
                font-family: var(--body-font);
            }
            ul {
                padding: 0;
                margin: 0;
                list-style: none;
            }
            img {
                max-width: 100%;
            }
            p {
                margin: 0;
            }
            h1 {
                font-size: 80px;
            }
            h1, h2, h3, h4 {
                margin: 0;
                line-height: 1;
                font-weight: 600;
            }
            h1, h2 {
                text-transform: uppercase;
                font-family: var(--title-font);
            }
            h2 {
                color: #020101;
                font-size: 40px;
            }
            h3 {
                color: var(--title-clr);
                font-size: 25px;
            }
            h4 {
                font-size: 20px;
            }
            .section-title {
                text-align: center;
                margin-bottom: 30px;
                text-transform: uppercase;
                font-family: var(--title-font);
            }
            .common-banner {
                position: relative;
                min-height: 600px;
            }
            .common-bg-img {
                position: absolute;
                left: 0;
                top: 0;
                z-index: -2;
                height: 100%;
                width: 100%;
                object-fit: cover;
            }
            .common-banner .banner-content {
                position: absolute;
                left: 50%;
                top: 50%;
                color: var(--white-clr);
                transform: translate(-50%, -50%);
            }
            .common-title {
                font-size: 60px;
            }
            .btn {
                padding: 15px 30px;
                font-size: 20px;
                text-transform: uppercase;
            }
            .common-bg::before {
                content: '';
                position: absolute;
                width: 100%;
                height: 100%;
                left: 0;
                top: 0;
                z-index: -1;
            }
            /*================================== header ==================================*/
            header {
                padding: 20px 0;
                background-color: var(--white-clr);
                box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.03);
                transition: background 0.3s, border 0.3s, border-radius 0.3s, box-shadow 0.3s;
            }
            .cstm-navbar-toggler {
                display: none;
            }
            header .navbar .navbar-brand {
                max-width: 250px;
                height: 100px;
            }
            header .navbar-nav {
                gap: 30px;
            }
            header .nav-link {
                font-family: var(--title-font);
                color: var(--title-clr);
                font-size: 25px;
                font-weight: 300;
            }
            header .nav-link.active {
                font-weight: 800;
            }
            header .nav-link:hover, header .nav-link.active  {
                color: var(--primary-clr);
            }
            /* footer */
            .footer-links, .copyright {
                text-align: center;
            }
            .footer-links a {
                color: var(--title-clr);
                font-weight: 600;
            }
            .footer-links [class^="col-"]:not(:last-child) {
                border-right: 1px solid #333;
            }
            .footer-social-media {
                display: flex;
                justify-content: center;
                align-items: center;
                gap: 30px;
                font-size: 30px;
                margin-top: 25px;
            }
            .footer-links {
                padding: 25px 0 60px;
            }
            .footer-social-media .facebook {
                color: #31C5F4;
            }
            .footer-social-media .insta, .footer-social-media .youtube {
                color: #EE335F;
            }
            .footer-social-media .tiktok {
                color: #000;
            }
            .footer-title h2 {
                color: var(--white-clr);
                font-size: 62px;
                font-weight: 400;
            }
            .footer-title {
                background-color: #f26f85;
                text-align: center;
                padding: 10px 0;
            }
            /* copyright */
            .copyright {
                background-color: #383838;
                color: var(--white-clr);
                padding: 20px 0;
            }
            /* about us page */
            .about-banner::before {
                background-color: #F26F85;
                opacity: 0.71;
            }
            /*  */
            .our-heart-img {
                max-width: 500px;
                margin: auto auto 30px;
            }
            .about-our-hearts {
                text-align: center;
                padding: 60px 0;
                position: relative;
            }
            .about-our-hearts .our-headerts-header h4 {
                padding-top: 30px;
            }
            /* about artists */
            .about-artists-img {
                width: 80%;
                margin: auto;
                padding-top: 78%;
                position: relative;
            }
            .about-artists-img img {
                position: absolute;
                top: 0;
                height: 100%;
                object-fit: cover;
                left: 50%;
                transform: translateX(-50%);
            }
            .about-artists-content p {
                line-height: 1.9;
                margin-top: 15px;
            }
            .about-artists {
                padding: 50px 0 100px;
            }
            .about-artists .row {
                justify-content: center;
                row-gap: 160px;
            }
            .bottom-wave {
                position: absolute;
                bottom: -1px;
                width: calc(100% + 1.3px);
                height: 57px;
                left: 0;
                transform: rotate(180deg);
            }
            .bottom-wave svg{
                width: 100%;
                height: 100%;
            }
            .bottom-wave .elementor-shape-fill {
                fill: #fff;
                transform-origin: center;
                transform: rotateY(0deg);
            }
            .about-video-sec {
                position: relative;
                min-height: 650px;
                overflow: hidden;
                isolation: isolate;
                display: flex;
                align-items: center;
                justify-content: center;
              }
              section.about-video-sec:after {
                    background-color: #009BDE;
                    opacity: 0.6;
                    position: absolute;
                    content: "";
                    width: 100%;
                    height: 100%;
                    top: 0;
                    left: 0;
                }
              .video-container {
                position: absolute;
                width: 100%;
                height: 100%;
                left: 0;
                right: 0;
                top: 0;
                bottom: 0;
            }
            .video-container video{
                position: absolute;
                height: 100%;
                width: 100%;
                object-fit: cover;
                left: 50%;
                top: 50%;
                transform: translate(-50%, -50%);
            }
            .video-above-shape, .video-bottom-shape {
                overflow: hidden;
                position: absolute;
                left: 0;
                width: 100%;
                line-height: 0;
                direction: ltr;
                top: -1px;
                z-index: 1;
            }
            .video-above-shape svg, .video-bottom-shape svg{
                width: calc(100% + 1.3px);
                height: 100px;
            }
            .video-bottom-shape {
                top: auto;
                bottom: -1px;
                transform: rotate(180deg);
            }
            .video-above-shape .elementor-shape-fill {
                    fill: #62D1E1;
                }
            .video-bottom-shape .elementor-shape-fill {
                    fill: #fff;
                }
            .about-video-sec .content-box {
                position: relative;
                z-index: 1;
                text-align: center;
            }
            .about-video-sec .content-box h2{
                color: #fff;
                margin-bottom: 20px;
            }
            .btn-secondary {
                display: inline-flex;
                justify-content: center;
                align-items: center;
                gap: 5px;
                padding: 15px 30px 15px 30px;
                font-size: 20px;
                font-weight: 500;
                color: #000;
                text-transform: uppercase;
                background-color: #E3A0C9;
                font-family: var(--title-font);
                /* box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.5); */
            }
        </style>
        <header>
            <nav class="navbar navbar-expand-lg">
                <div class="container-fluid">
                <a href="#" class="navbar-brand">
                    <img alt="Shaping Hearts" src="images/logo.png">
                </a>
                
                <button class="cstm-navbar-toggler">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div id="navbarSupportedContent" class="collapse navbar-collapse">
                    <ul class="navbar-nav">
                    <li class="nav-item">
                        <a href="#" aria-current="page" class="nav-link active">Home</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Programmes</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Partners and Artists</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link">Contact Us</a>
                    </li>
                    </ul>
                </div>
                </div>
            </nav>
        </header>
        <section class="about-banner common-banner common-bg">
            <img alt="about banner" src="images/about-us-bg.jpg" class="common-bg-img">
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <div class="banner-content">
                          <h1 class="common-title">ABOUT SHAPING HEARTS</h1>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bottom-wave">
                <svg preserveAspectRatio="none" viewBox="0 0 1000 100" xmlns="http://www.w3.org/2000/svg">
                    <path d="M473,67.3c-203.9,88.3-263.1-34-320.3,0C66,119.1,0,59.7,0,59.7V0h1000v59.7 c0,0-62.1,26.1-94.9,29.3c-32.8,3.3-62.8-12.3-75.8-22.1C806,49.6,745.3,8.7,694.9,4.7S492.4,59,473,67.3z" opacity="0.33" class="elementor-shape-fill"></path>
                    <path d="M734,67.3c-45.5,0-77.2-23.2-129.1-39.1c-28.6-8.7-150.3-10.1-254,39.1 s-91.7-34.4-149.2,0C115.7,118.3,0,39.8,0,39.8V0h1000v36.5c0,0-28.2-18.5-92.1-18.5C810.2,18.1,775.7,67.3,734,67.3z" opacity="0.66" class="elementor-shape-fill"></path>
                    <path d="M766.1,28.9c-200-57.5-266,65.5-395.1,19.5C242,1.8,242,5.4,184.8,20.6C128,35.8,132.3,44.9,89.9,52.5C28.6,63.7,0,0,0,0 h1000c0,0-9.9,40.9-83.6,48.1S829.6,47,766.1,28.9z" class="elementor-shape-fill"></path>
                </svg>
            </div>
        </section>
        <section class="our-hearts about-our-hearts common-bg">
            
            <div class="container">
              <div class="row">
                <div class="col-md-11 mx-auto">
                  <div class="our-headerts-header">
                    <div class="our-heart-img">
                      <img alt="Follow our hearts" src="images/Follow-our-hearts.png">
                    </div>
                    <h4>Step into the world of talented artists with disabilities and be awed by their art creations at the largest inclusive arts 
                        event!</h4>
                    <h4>Experience the artists’ works through multiple lenses – an art exhibition, live performances, a charity art auction – and 
                        celebrate the diverse talents in our community.</h4>
                  </div>
                </div>
              </div>
            </div>
        </section>
        <section class="about-video-sec">
            <div class="video-above-shape">
                <svg preserveAspectRatio="none" viewBox="0 0 1000 100" xmlns="http://www.w3.org/2000/svg">
                    <path d="M738,99l262-93V0H0v5.6L738,99z" class="elementor-shape-fill"></path>
                </svg>
            </div>
            <div class="video-container">
                <video src="images/necdc_-_shaping_hearts_main_video_final_091023-Original-1.mp4" loop="" playsinline="" muted="" autoplay="" class="bg-video"></video>
            </div>
            <div class="container">
                <div class="content-box">
                    <h2>STORIES FROM THE HEART</h2>
                    <a class="btn btn-secondary">Click Here</a>
                </div>
            </div>
            <div class="video-bottom-shape">
                <svg preserveAspectRatio="none" viewBox="0 0 1000 100" xmlns="http://www.w3.org/2000/svg">
                    <path d="M738,99l262-93V0H0v5.6L738,99z" class="elementor-shape-fill"></path>
                </svg>
            </div>
        </section>
        
        <section class="about-artists">
            <div class="container">
                <div class="section-title">
                    <h2>MEET OUR HEARTISTS</h2>
                  </div>
                <div class="row">
                    <div class="col-md-4">
                        <div class="about-artists-box">
                            <div class="about-artists-img">
                                <img alt="about-artist1" src="images/about-artist1.png">
                            </div>
                            <div class="about-artists-content">
                                <p>Alex (@theunskilledboy), a visual artist with autism, creates abstract and pop-art inspired by nature and 
                                    everyday objects. He uses vibrant colours and shapes and excels in various mediums such as acrylics, ink, oil 
                                    pastels, and watercolours.</p>
                                <p>This year, Shaping Hearts 2023 will be launching a line of merchandise featuring the works of Alex. If his 
                                    paintings catches your attention, be sure to check out the merchandise available under the 'Shop' tab!</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="about-artists-box">
                            <div class="about-artists-img">
                                <img alt="about-artist" src="images/about-artist2.png">
                            </div>
                            <div class="about-artists-content">
                                <p>Reuel is a self-taught artist. He has a natural gift for the creative arts and enjoys celebrating festivals 
                                    and special occasions. Diagnosed with Autism, he attends programmes at Extraordinary People Limited, 
                                    connecting with others through art, music, drama and fashion. Dressing up like an archetypal French street 
                                    artist when he paints, he uses his knack of colours to imbue each painting with life and feeling.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="about-artists-box">
                            <div class="about-artists-img">
                                <img alt="about-artist" src="images/about-artist3.png">
                            </div>
                            <div class="about-artists-content">
                                <p>Gary has a unique set of abilities. He has a passion for painting and find solace in swimming and dance. His 
                                    cheerful demeanour is infectious, bringing joy to those around him. He expresses himself through his creative 
                                    pieces to show his perspective of the world. Despite facing challenges, he approaches life with a positive 
                                    attitude and an unwavering spirit, inspiring others as a remarkable individual.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="about-artists-box">
                            <div class="about-artists-img">
                                <img alt="about-artist" src="images/about-artist4.png">
                            </div>
                            <div class="about-artists-content">
                                <p>Sabrina is a new member to the Rainbow Centre’s Artability Programme. She is a sweet and joyful young lady who 
                                    loves K-POP music, food and everything cute. Sabrina is a fast learner and displays incredible art skills and 
                                    techniques in her paintings. She enjoys playing with colour contrast in her artworks, and loves defining the 
                                    subject matter with thick lines.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="about-artists-box">
                            <div class="about-artists-img">
                                <img alt="about-artist" src="images/about-artist5.png">
                            </div>
                            <div class="about-artists-content">
                                <p>After an accident that caused her to be paralysed chest down, Christina did not give up on herself, 
                                    discovering mouth painting through a group of friends. Although initially apprehensive, she has since 
                                    grown to enjoy painting and is proficient with both watercolour and acrylic. Her favourite subjects to paint 
                                    are flora and fauna. Besides painting, Christina also represented Singapore at the 11th ASEAN Para Games as a 
                                    table tennis player.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="video-sec">
            <div class="container">
               <img src="images/video-insta-img.png">                
            </div>
        </section>
        <footer>
            <div class="footer-title">
            <div class="container">
                <h2>Follow Our Hearts</h2>
            </div>
            </div>
            <div class="container">
            <div class="footer-social-media">
                <a class="facebook">
                <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a class="insta">
                <i class="fa-brands fa-instagram"></i>
                </a>
                <a class="tiktok">
                <i class="fa-brands fa-tiktok"></i>
                </a>
                <a class="youtube">
                <i class="fa-brands fa-youtube"></i>
                </a>
            </div>
            <div class="footer-links">
                <div class="row">
                <div class="col-md-2">
                    <a>Home</a>
                </div>
                <div class="col-md-2">
                    <a>About Us</a>
                </div>
                <div class="col-md-2">
                    <a>Programmes</a>
                </div>
                <div class="col-md-2">
                    <a>Partners &amp; Artists</a>
                </div>
                <div class="col-md-2">
                    <a>Shop</a>
                </div>
                <div class="col-md-2">
                    <a>Contact Us</a>
                </div>
                </div>
            </div>
            </div>
            <div class="copyright">
            <div class="container">
                <p>Copyright © 2023 Shaping Hearts 2023</p>
            </div>
            </div>
        </footer>
    

```