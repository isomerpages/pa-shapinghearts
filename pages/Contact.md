---
title: Contact
permalink: /contact/
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
        .ms_cont {
            background: #D1D1D1;
            min-height: 70vh;
	width: 100%;
	margin-top: -20px;
   display: flex;
	padding-left: 20px;
	padding-right: 20px;
        }

        .ms_flex {
            display: flex;
            flex-direction: column;
            justify-content: center;
            width: 50%;
            min-height: 100%;
        }

        .ms_small {
            font-size: 18px;
            font-weight: 500;
            text-transform: uppercase;
            padding-bottom: 30px;
        }

        .ms_medium {
            font-size: 48px;
            font-weight: 700;
	          line-height: 1.5;
            text-transform: capitalize;
            padding-bottom: 30px;
        }
	
		.col.is-offset-2, .col.is-offset-2-tablet{
	margin-left: 0% !important;
 width: 100% !important;
	}
	
        .ms_form {
            position: relative;
            width: 50%;
            display: flex;
            justify-content: flex-end;
        }

        .ms_form_cont {
            background-color: white;
            padding-top: 30px;
            padding-bottom: 30px;
            padding-right: 60px;
            padding-left: 60px;
            display: flex;
            flex-direction: column;
            border: 1px solid black;

            position: absolute;
            width: 440px;
            top: 55px;
        }

        .ms_form_fields {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .ms_form_p {
            font-size: 24px;
            font-weight: 600;
            text-transform: capitalize;
            text-align: center;
            padding-bottom: 20px;
        }

        .ms_full {
            width: 100%;
            display: flex;
            flex-direction: column;
        }

        .arrow{
            font-size: 2rem;
            color: rgb(70, 70, 70);
        }

        input[type=text],
        input[type=tel],
        input[type=email] {
            width: 100%;
            margin: 8px 0;
            box-sizing: border-box;
            border: none;
            border-bottom: 1px solid black;
            font-size: 16px;
            padding-bottom: 5px;
        }

        input[type=text]:focus,
        input[type=tel]:focus,
        input[type=email]:focus {
            outline: none;
        }

        label{
            color: #b3b3b3;
        }

        input[type=submit] {
            background-color: black;
            color: white;
            padding-top: 12px;
            padding-bottom: 12px;
            font-size: 18px;
            margin-top: 20px;
            border: none;
            outline: none;
            cursor: pointer;
        }
        
        input::placeholder{
            color: black;
        }

        .ms_footer {
            height: 20vh;
            display: flex;
            align-items: center;
        }

        .ms_footer p {
            padding-left: 80px;
            padding-right: 80px;
        }

        .ms_bold {
            font-weight: bold;
            text-decoration: underline;
        }

        @media (min-width: 320px) and (max-width: 1023px) {

            .ms_footer{
                width: 100%;
            }

            .ms_cont{
                flex-direction: column;
                padding-right: 10px;
                padding-left: 10px;
                height: auto;
                padding-top: 30px;
                padding-bottom: 30px;
                gap: 20px;
            }

            .ms_flex{
                width: 100%;    
                align-items: center;
            }

            .ms_form_cont{
                width: 90%;
            }

            .ms_form{
                width: 100%;   
                justify-content: center;
	
            }

            .ms_medium{
                font-size: 33px;
            }

            .ms_form_cont{
                position: static;
            }
	.ms_form_cont{
	padding-left: 20px;
	padding-right: 20px;
	}
        }
    </style>

<section>
    <div class="ms_cont">
        <div class="ms_flex">
            <p class="ms_small">LOREM IPSUM dolor</p>
            <p class="ms_medium">Lorem ipsum dolor sit amet adipiscing elit, sed do eiusmod tempor
                incididunt ut la</p>
                <i class="fa-solid fa-arrow-right-long arrow"></i>
        </div>
        <div class="ms_form">
            <div class="ms_form_cont">
                <p class="ms_form_p">Lorem ipsum dolor sit</p>
                <form class="ms_form_fields">
                    <div class="ms_full">
                        <label>Name</label>
                        <input id="" name="" placeholder="Jacob Jones" type="text">
                    </div>

                    <div class="ms_full">
                        <label>E-Mail</label>
                        <input id="" name="" placeholder="example@gmail.com" type="email">
                    </div>

                    <div class="ms_full">
                        <label>Telephone</label>
                        <input id="" name="" placeholder="+91 1234567890" type="tel">
                    </div>

                    <div class="ms_full">
                        <label>Message</label>
                        <input id="" name="" placeholder="Lorem ipsum dolor sit amet, consectetur" type="text">
                    </div>

                    <input value="SEND" type="submit">
                </form>
            </div>
        </div>
    </div>
    <div class="ms_footer">
        <p>Lorem ipsum dolor sit amet, consectetur <span class="ms_bold">adipiscing elit.</span></p>
    </div>
	</section>