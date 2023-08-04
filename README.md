<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Success.com</title>

    <style>
        body {
            /* height: max-content; */
            /* height: 1800px; */
        /* zoom: 75%; */
            width: fit-content;

        }

        /* css reset  */
        * {
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
        }

        /* navbar editing */

        #navbar {
            display: flex;
            align-items: center;
            position: relative;
            flex-wrap: wrap;
            top: 25px;
            height: fit-content;

        }

        #navbar::before {
            content: "";
            position: absolute;
            height: 100%;
            width: 100%;
            background-color: rgb(255, 255, 255);
            z-index: -5;
            opacity: 0.5;
        }
        

        #logo p3 {
            font-size: 60px;
            padding: 3px 52px;
            margin: 0px 0px;
            font-family: math
        }

        #logo p4 {
            margin: 0px 57px;
            padding: 0px 0px;

        }

        ul {
            display: flex;
            flex-wrap: wrap;
            margin: 15px;
        }

        .item {
            display: flex;
            list-style: none;
            margin: 27px;
            /* border: 2px solid red; */

        }

        .item a {
            /* border: 2px solid red; */
            margin: -2px;
            padding: 16px;
            font-size: 20px;
            text-decoration: none;
            /* background-color: #d1d1d1b3; */
            border-radius: 9px;
        }

        .item a:hover {
            color: rgb(0, 0, 0);
            /* background-color: #5391b4b3; */
            background: linear-gradient(rgba(73, 73, 189, 0.505), rgba(184, 91, 91, 0.528));
            transform: scale(1.2);
            transition: all 0.5s ease-in-out 0s;
        }

        /* below heading */
        .heading-2 {
            display: flex;
            flex-wrap: wrap;
            flex-direction: column;
            align-items: center;
        }

        .heading-2 p1 {

            font-size: 30px;
            margin-top: 200px;

        }

        .heading-2 h2 {

            font-size: 200px;
            background-image: url(https://images.unsplash.com/photo-1563089145-599997674d42?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80) ;
            background-size: cover;
            background-position: cover;
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent
        }

        .heading-2 p2 {
            font-size: 30px;
        }

        .heading-2 button {
            margin: 82px;

        }

        .main-image::before {
            content: "";
            position: absolute;
            background: url(bg/pexels-nina-uhlikova-725255.jpg) no-repeat center center/cover;
            position: fixed;

            /* height: -webkit-fill-available; */
            height: 1800px;
            width: 100%;
            z-index: -1;
            opacity: 0.6;
        }

        /* about me text */
        #aboutme2{
            background-color: rgb(167, 167, 167);
            margin-top: 340px;
            box-shadow: 5px 4px 70px 80px rgb(167, 167, 167);
        }
        #aboutme {
            height: fit-content;
            width: fit-content;
            display: flex;
            flex-direction: row;
            align-items: center;
            /* justify-content: center; */
            /* border: 3px solid black; */
            
         
            /* color: white; */

        }
        @media (max-width: 900px) and (min-width: 10px){
            #aboutme {
                display: flex;
            flex-direction: column;
            align-items: center;
            }
        }

        #aboutme h2 {
            display: block;
            font-size: 60px;
            margin: 0px;
            padding: 0px;


        }

        .selfpara {
            display: flex;
            flex-direction: column;
            font-size: 40px;
            margin: 80px;

        }

        .selfpara a {
            font-size: 60px;
            margin: 60px;
            background-image: url(https://images.unsplash.com/photo-1563089145-599997674d42?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80) ;
            background-size: cover;
            background-position: cover;
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }

        button {
            display: block;
            padding: 13px;
            margin: auto;
            background-color: #cfcfcf;
            font-size: 33px;
            border-radius: 12px;
            cursor: pointer;
            margin-top: 80px;

        }

        button:hover {
            color: white;
            background-color: rgba(0, 0, 0, 0.484);
        }

        .selfimage img {

            height: 700px;
            filter: drop-shadow(10px 10px 20px rgb(21, 22, 22));


        }

        /* How I Can Help You */

        .container {

            height: fit-content;
            width: fit-content;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-evenly;


        }

        .item-cont {
            background-color: rgba(89, 184, 225, 0.445);
            border: 2px solid rgb(7, 1, 1);
            border-radius: 10px;
            margin: 68px;
            padding: 56px;
            text-align: center;
            

        }
        .item-cont:hover{
            
            color: rgb(0, 0, 0);
            background-color: rgba(89, 184, 225, 0.445);
            transform: scale(1.1);
            transition: all 0.5s ease-in-out 0s;
            box-shadow:  4px 5px 30px 40px rgba(89, 184, 225, 0.445);
           
        }
        a12 {
            text-align: center;
            display: block;
            margin: 50px;
            margin-top: 300px;
            font-size: 60px;
            padding: 30px;
            background-image: url(https://images.unsplash.com/photo-1563089145-599997674d42?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80) ;
            background-size: cover;
            background-position: cover;
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }

        #item1 {

            font-size: 40px;
        }

        #item2 {

            font-size: 40px;
        }

        #item3 {

            font-size: 35px;
        }

        p9 {
            display: inline-block;
            font-size: 20px;
            margin-top: 10px;
            padding: 5px;

        }

        .button4 {
            font-size: 15px;
            margin-top: 5px;
            padding: 8px;
        }

        input[type='text'] {
            color: rgb(0, 0, 0);
            margin: 22px;
            padding: 10px;
            border: 2px solid black;
            background-color: #dfe6ebbd;
            font-size: 14px;
            border-radius: 9px;
        }

        input[type='text']:hover {
            background-color: rgb(178, 178, 177);
        }

        .feedback-box {
            margin-top: 40px;
            border: 3px solid black;
            background: url(bg/Laptop\ background\ black.jpg);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            
        }

        .feedback-box a12 {
            margin-top: 120px;
            background-image: url(https://images.unsplash.com/photo-1563089145-599997674d42?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80) ;
            background-size: cover;
            background-position: cover;
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }

        .form {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            display: flex;
            justify-content: end;
            flex-direction: column;
            margin: 70px;
            padding: 10px;

        }

        .box {

            border: 3px solid black;
            margin: 10px;
            padding: 7px 18px;
            border-radius: 7px;
            background-color: #f1eae2;
            width: 900px;
            font-size: 17px;
        }

        .box:hover {
            background-color: rgb(187, 204, 204);


        }

        label {
            font-size: 20px;
        }

        .form button {
            margin: 10px;
            padding: 10px;
            font-size: 21px;
            /* background: linear-gradient(red, blue); */
        }

        /* contact */
        #contact {
            background-color: #cfcfcf81;
            
        }

        #contact a12{
            margin-top: 120px;
            padding-top: 30px;
            background-image: url(https://images.unsplash.com/photo-1563089145-599997674d42?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80) ;
            background-size: cover;
            background-position: cover;
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }

        .contactimg {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-wrap: wrap;
            margin: 28px;
            /* filter: drop-shadow(10px 10px 20px rgb(94, 182, 217)); */
        }

        .contactimg img {
            width: 60px;
            height: 60px;
            margin: 30px;

        }

        .address {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 17px;
        }

        .address p {
            font-size: 30px;
            margin: 8px;
        }

        /* footer */
        #footer {
            text-align: center;
            font-size: 20px;
            

        }

        @media (max-width: 800px) and (min-width: 0px) {
            .main-image::before {
                content: "";
                position: absolute;
                background: url(bg/pexels-nina-uhlikova-725255.jpg) no-repeat center center/cover;
                position: fixed;
                height: -webkit-fill-available;
                width: 100%;
                z-index: -1;
                opacity: 0.4;

            }
            #Success{
                font-size: 140px;
            }

            .selfimage img {
                height: 300px;
            }

            .box {

                border: 3px solid black;
                margin: 10px;
                padding: 7px 18px;
                border-radius: 7px;
                background-color: #f1eae2;
                width: 400px;
                font-size: 17px;
            }

        }

        @media (max-width: 1300px) and (min-width: 800px) {
            .selfimage img {
                height: 400px;
            }

            .box {

                border: 3px solid black;
                margin: 10px;
                padding: 7px 18px;
                border-radius: 7px;
                background-color: #f1eae2;
                width: 600px;
                font-size: 17px;
            }
            #Success{
                font-size: 170px;
            }

        }

        @media (min-width: 1400px) {
            #Success {
                animation-name: lucifer;
                animation-duration: 3s;
                animation-timing-function: ease-in-out;
                animation-iteration-count: infinite;
                animation-fill-mode: forwards;
                animation-delay: 0s;
                animation-direction: alternate-reverse;
                
            }

            @keyframes lucifer {
                0% {
                    font-size: 190px;
                }

                50% {
                    font-size: 220px;
                }

                75% {
                    font-size: 190px;
                }
            }
        }
        @media (min-width: 50px)
        {
            #Success {
                margin-left: 25px;
                margin-right: 25px
            }
        }


        #time {
            font-size: 18px;
            text-align: end;
            padding: 10px;
        }

        ::placeholder{
            color: rgb(26, 25, 25);
        }
    </style>

</head>

<body>
    <div id="home">
        <div class="main-image">
        
            <div id="time"></div>
            <nav id="navbar">
                <div id="logo">
                    <!-- <img src="bg/pngwing.com - Copy.png" alt="error"> -->
                    <P3>LUCIFER</P3>
                    <br>
                    <p4>Personal life coach</p4>
                </div>
    
                <ul>
                    <li class="item"><a href="#home">HOME</a></li>
                    <li class="item"><a href="#aboutme">ABOUT</a></li>
                    <li class="item"><a href="#services">SERVICES</a></li>
                    <li class="item"><a href="#feedback">FEEDBACK</a></li>
                    <li class="item"><a href="#contact">CONTACT</a></li>
                </ul>
    
            </nav>
            <div class="heading-2">
                <p1>AMBITION IS THE FIRST STEP TOWARDS</p1>
                <h2 id="Success">SUCCESS</h2>
                <P2>Now Available for Online Coaching</P2>
                <button class="button" type="button">Book now</button>
            </div>
    
        </div>
    </div>
    <div id="aboutme2">
        <div id="aboutme">
            <!-- <div class="selfimage">
                <img src="bg/WhatsApp Image 2023-06-20 at 7.35.17 AM.jpg" alt="error">
            </div> -->
    
            <p6 class="selfpara"><a>ABOUT-ME</a>
    
                <a6>"I'm a life coach specializing in helping people overcome their challenges and create the life  they want. My passion is to help others realize their full potential, build self-confidence, and find purpose."</a6>
                <a6 id="para8">
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quae corporis est non autem quisquam corrupti
                    quos! Maiores delectus nisi dolore, fuga nulla quos sit qui quaerat at hic in deserunt.
                </a6>
                
            </p6>
            <div class="selfimage">
                <img src="bg/Selfimage background removed.png" alt="error">
            </div>
    
            
        </div>
        <button class="button" onclick="togglehide()" type="button">Read more/less</button>
        

    </div>
    <div id="services">
        <a12 >How I Can Help You</a12>
    <div class="container">

        <div class="item-cont" id="item1">ONLINE COACHING <p8>
                <form action="Noaction.php" class="from">
                    <p9>Use this area to describe one of your services.</p9>
                    <input type="text" placeholder="Start writing from here">
                    <button class="button4" type="button">BOOK NOW</button>
                </form>
            </p8>
        </div>
        <div class="item-cont" id="item2">COUPLE GUIDENCE <p8>
                <form action="Noaction.php" class="from">
                    <p9>Use this area to describe one of your services.</p9>
                    <input type="text" placeholder="Start writing from here">
                    <button class="button4" type="button">BOOK NOW</button>
                </form>
        </div>
        <div class="item-cont" id="item3">ENTREPRENEURSHIP <p8>
                <form action="Noaction.php" class="from">
                    <p9>Use this area to describe one of your services.</p9>
                    <input type="text" placeholder="Start writing from here">
                    <button class="button4" type="button">BOOK NOW</button>
                </form>
        </div>

    </div>
    </div>
    
    <div id="feedback">
        <div class="feedback-box">
            <a12>feedback-form</a12>
            <form action="" class="form">
                <div>
                    <label for="name">Name </label>
                    <input type="text1" placeholder="Enter your name" id="name" class="box">
                </div>
    
                <div>
                    <label for="email">Email </label>
                    <input type="email" placeholder="Enter your Email" id="email" class="box">
                </div>
    
                <div>
                    <label for="number">Phone </label>
                    <input type="number" placeholder="Enter your Phone Number" id="number" class="box">
                </div>
    
                <div>
                    <label for="message">Message</label>
                    <textarea id="message" cols="30" rows="10" placeholder="Message for us" class="box"></textarea>
                </div>
                <div>
                    <button>Submit Now</button>
                </div>
            </form>
        </div>
    </div>
    <div id="contact">
        <a12 >Contact Us</a12>
        <div class="address">
            <p>117 Mega boys hostel - A </p>
            <p>Dr BR Ambedkar National Institue of Technology</p>
            <p>G.T Road, Amritsar Bypass, Jalandhar, Punjab, India-144008</p>

            <p>+916387259583</p>
        </div>
        <div class="contactimg">
            <a href="https://www.threads.net/@1182_anoop_11989" target="_blank">
                <img src="bg/Threads_(app)_logo.svg.png" alt="">
            </a>
            <a href="https://www.youtube.com/" target="_blank">
                <img src="bg/yt black.png" alt="">
            </a>
            <a href="https://facebook.com" target="_blank">
                <img src="bg/fac.png" alt="">
            </a>
            <a href="https://instagram.com/1182_anoop_11989?igshid=MzNlNGNkZWQ4Mg==" target="_blank">
                <img src="bg/insta black.png" alt="">
            </a>
        </div>

    </div>
    <footer>
        <div id="footer">
            Copyright &copy; LifeCoach.com. All rights reserved!
        </div>
    </footer>
</body>
<script>
    function togglehide() {
        let para = document.getElementById('para8');
        if (para.style.display == 'none') {
            para.style.display = 'block';
        }
        else {
            para.style.display = 'none';
        }
    }

    function time() {
        let time = new Date();
        document.getElementById('time').innerHTML = time;
    }
    setInterval(time, 1000);
</script>

</html>
