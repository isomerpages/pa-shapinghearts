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
            box-shadow: 0px 0px 10px 1px gainsboro;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            border-radius: 15px;
            height: 200px;
        }

        .partner_card img {
            width: 30%;
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

        .faqs_left,
        .faqs_right {
            width: 45%;
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



        /* youtube_section */
        .youtube_section {
            border-top: 2px solid gainsboro;
            border-bottom: 1.99px solid black;
            min-height: 100vh;
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
                <h1>Meet the Heartists behind the masterpieces.</h1>
                <p>Every art piece has a story behind it. Stories of triumph, tragedy, strength, failure, hardship, and beauty. See what speaks to you. </p>
            </div>
            <div class="hero_right">
                <img src="https://i.ibb.co/gzGc84Z/Partners-1.png">
            </div>
        </div>
    </section>

    <section class="section">
        <div class="canvas canvass">
            <h1 class="main_heading2">Our Heartists</h1>
            <br>
            <div class="hearts_grid">
                <div class="heart_card">
                    <img src="https://i.ibb.co/cQY3zg7/Alex-Lim.jpg">
                    <p class="bold">Alex Lim</p>
                    <br>
                    <p class="desc">Alex (@theunskilledboy), a visual artist with autism, creates abstract and pop-art inspired by nature and everyday objects. He uses vibrant colours and shapes and excels in various mediums such as acrylics, ink, oil pastels, and watercolours.</p>
                </div>

                <div class="heart_card">
                    <img src="https://i.ibb.co/TgtK1Xp/Gary-Chong.jpg">
                    <p class="bold">Gary Chong</p>
                    <br>
                    <p class="desc">Gary is a talented artist with a remarkable spirit. His friendly and chatty nature shines through as he expresses himself through art. His vibrant energy is evident in his captivating drawings, showcasing his innate talent and passion. Beyond art, Gary finds joy in dancing, a testament to his zest for life and determination to embrace the world with boundless enthusiasm. Gary is diagnosed with intellectual disability.</p>
                </div>
                <div class="heart_card">
                    <img src="https://i.ibb.co/QjM0F9X/Leong-Sijun.png">
                    <p class="bold">Leong Sijun</p>
                    <br>
                    <p class="desc">Sijun was born with Down Syndrome and had been challenging the deterioration of his eyesight and muscles in the past decade. He would paint very slowly stroke by stroke to fill up the whole canvas. He loves cars and paintings; if given a choice, he would want to become a car designer or an Interior Designer. He is a cheerful boy, like his paintings, colourful and bright; he feels happy with colours and sunshine.”</p>
                </div>
                <div class="heart_card">
                    <img src="https://i.ibb.co/QJ5tKyw/Ng-Jun-Yao.jpg">
                    <p class="bold">Ng Jun Yao</p>
                    <br>
                    <p class="desc">Jun Yao has been fond of observing the expression and movement of animals since young. His fondness for animals translates into paintings of uniquely charming animal cartoon characters. His parents enrolled him in art classes when he was 8 years old to nurture his interest and talent. Over the years, his artworks were exhibited in various art exhibitions and printed on merchandise e.g. bags &amp; and pouches. In 2015, his artwork was selected by Uniqlo to be one of the prints on t-shirts. He was diagnosed with autism at the age of 4 and graduated from AWWA Special School in 2018.</p>
                </div>
                <div class="heart_card">
                    <img src="https://i.ibb.co/yWwVvgs/Vincent-Seet.jpg">
                    <p class="bold">Vincent Seet</p>
                    <br>
                    <p class="desc">Vincent is a two-time stroke survivor and educator turned artist. He believes that every painting is “a dream come true” and every artwork can be a “hope for peace and harmony in the world”. Over the years, Vincent has supported various charity institutions locally as well as across the region. He also conducts art workshops for residents of a mental health nursing home on a voluntary basis.</p>
                </div>
                <div class="heart_card">
                    <img src="https://i.ibb.co/qp8cF5H/Yap-Jia-Hui.jpg">
                    <p class="bold">Yap Jia Hui</p>
                    <br>
                    <p class="desc">Jia Hui is a young artist who likeseverything cute, lovely, and pink! With her distinctive crayon techniques and bold colour choices, her style is one of the most iconic and refreshing out of all of our apprentices! </p>
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
                    <img src="https://i.ibb.co/5xC1Wdb/Frame-217-1.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/YDJPN5d/AWWA.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/5Wwy12d/Bizlink-Centre-Singapore.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/t3qhTZ9/Cerebral-Palsy-Alliance-Singapore-CPAS-School.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/25GsqMX/Christian-outreach.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/bJ7vD0Q/Down-Syndrome-Association-Singapore.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/MZWSKDp/Extra-Ordinary-People.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/6WJ1KjY/Frame-206.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/ssmZ13q/Frame-217.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/nbddZ6y/Friends-of-the-Disabled-Society-FDS.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/Fhhkgrk/Group-4171.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/Qr6gBxt/Group-7270-1.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/XXfLxp8/Group-7270-2.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/YbdG585/Handicapped-Welfare-Association.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/qN9gnTs/MINDS.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/Nx0KgW4/Mouth-Foot-Painting-Artists-Pte-Ltd-1.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/QnNXmv3/Muscular-Dystrophy-Association-Singapore.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/FHt66wn/Partners-metta.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/D7Zzxrz/Rainbow-Centre.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/89Wx44M/Singapore-Association-for-Mental-Health-SAMH.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/C9TC495/Singapore-cheshire-home.png">
                </div>
                <div class="partner_card">
                    <img src="https://i.ibb.co/fS7jGNx/SPD.png">
                </div>
            </div>
        </div>
    </section>

    
    <section class="section bg_gray mt-5 FAQS">
        <div class="canvass canvas">
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
                            What is the Shaping Hearts festival?
                        </div>
                        <div class="faq-answer">
                           Shaping Hearts is Singapore's largest inclusive arts festival organized by the North East Community Development Council (NE CDC). It celebrates the talents of artists with disabilities through art exhibitions, live performances, and an art marketplace, promoting inclusivity and raising awareness about the special needs community.
                        </div>
                    </div>
                    <div class="faq">
                        <div class="faq-question">
                            What impact does the Shaping Hearts festival have on the community?
                        </div>
                        <div class="faq-answer">
                            The Shaping Hearts festival promotes inclusivity and awareness for the special needs community, supports differently-abled artists financially and socially, and encourages community engagement and compassion through art, creating a more cohesive and supportive society.
                        </div>
                    </div>
                    <div class="faq">
                        <div class="faq-question">
                            How does the Shaping Hearts festival support artists with disabilities?
                        </div>
                        <div class="faq-answer">
                           The Shaping Hearts festival supports artists with disabilities by providing a platform for them to showcase their talents through art exhibitions and performances. It raises awareness and funds through the sale of artwork, with proceeds going directly to the artists and their supporting social service agencies, helping them gain financial stability and recognition for their work
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</section>