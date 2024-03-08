# TcsClone
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./font-awesome-4.7.0/css/font-awesome.min.css">
    <style>
        * {
            padding: 0px;
            margin: 0px;
            box-sizing: border-box;

        }

        body {
            background-color: black;
            color: white;
            display: flex;
            flex-wrap: wrap;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }

        ul {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 50px;
        }

        nav ul li {
            list-style: none;
            color: white;
            font-size: 20px;

        }

        nav ul li a {
            text-decoration: none;
            color: gray;
        }

        .container {
            height: 500px;
            width: 1200px;
            border: 1px solid transparent;
            flex-wrap: wrap;
            background-image: url(./tcsdiv1.jfif);
            margin: 20px auto;
        }

        .container h1 {
            font-size: 70px;
        }

        .snapshots {
            height: 300px;
            width: 100%;
            border: 1px solid white transparent;
            display: flex;
        }

        .snap {
            height: 200px;
            width: 200px;
            border: 5px solid white;
            border-radius: 50%;
            margin: 50px auto;
            justify-content: space-between;
            align-items: center;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }

        #snap1 {
            background-image: url(./snap1.jfif);
        }

        #snap2 {
            background-image: url(./snap2.jfif);
        }

        #snap3 {
            background-image: url(./snap3.jfif);
        }

        #snap4 {
            background-image: url(./snap4.jfif);
        }

        #snap5 {
            background-image: url(./snap5.jfif);
        }

        #snap6 {
            background-image: url(./snap6.jfif);
        }

        #snap7 {
            background-image: url(./snap7.jfif);
        }

        #snap8 {
            background-image: url(./snap8.jfif);
        }

        #snap9 {
            background-image: url(./snap9.jfif);
        }

        .container3 {
            display: flex;
            flex-wrap: wrap;
            flex-direction: row;

        }

        .container3 .text {
            height: 500px;
            width: 600px;
            border: 1px solid transparent;
            margin: 60px;
            align-items: center;

        }

        .text h3 {
            color: grey;
        }

        .text h1 {
            font-size: 70px;
        }

        .container3 #text2 {
            background-color: rgb(50, 50, 50);
            border-radius: 30px;
            font-size: 50px;
            text-align: center;
        }

        .container3 #text2 li {
            list-style: none;
            align-items: end;
            display: inline-block;
            justify-content: space-between;
            margin: 50px;
            color: hotpink;

        }

        .container4 {
            height: 600px;
            width: 100%;
            border: 1px solid white transparent;

        }

        .container4 h1 {
            margin: 0px 70px;
            display: inline-block;
            justify-content: space-evenly;

        }

        .container4 h1 a {
            text-decoration: none;
            color: white;
            margin-left: 700px;
        }

        .container4 .box {
            height: 500px;
            width: 400px;
            border: 1px solid white transparent;
            display: inline-block;
            margin: 50px;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;

        }

        #box1 {
            background-image: url(./con4.1);
        }

        #box2 {
            background-image: url(./con4.2);
        }

        #box3 {
            background-image: url(./con4.3);
        }

        .container5 {
            height: 700px;
            width: 1400px;
            border: 1px solid transparent;
            flex-wrap: wrap;
            margin: 20px auto;
            background-image: url(./container5.jfif);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }


        .end {
            background-color: white;
        }

        h2 {
            color: black;
        }

        .container6 {
            height: 700px;
            width: 1600px;
            border: 1px solid transparent;
            flex-wrap: wrap;
            background-image: url(./container6.jfif);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }

        #textbox {
            height: 600px;
            width: 800px;
            border: 1px solid transparent;
            margin: 60px auto;
            margin-left: 800px;
            background-color: white;

        }

        #textbox h5 {
            color: gray;
            margin: 50px;
            font-size: 20px;
        }

        #textbox h1 {
            color: brown;
            margin: 52px;
            font-size: 50px;
        }

        #textbox h3 {
            color: rgb(193, 188, 188);
            margin: 53px;
            font-size: 30px;
        }

        #textbox h4 {
            color: black;
            margin: 53px;
            font-size: 20px;
        }

        .container7 {
            height: 100vh;
            width: 100%;
            border: 1px solid white transparent;

        }

        .con7 {
            height: 500px;
            width: 300px;
            border: 1px solid transparent;
            display: inline-block;
            margin: 40px 5px;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }

        #img1 {
            background-image: url(./img1.jfif);
        }

        #img2 {
            background-image: url(./img2.jfif);
        }

        #img3 {
            background-image: url(./img3.jfif);
        }

        #img4 {
            background-image: url(./img4.jfif);
        }

        #img5 {
            background-image: url(./img5.jfif);
        }

        #textbox1 {
            height: 600px;
            width: 800px;
            border: 1px solid transparent;
            margin: 60px auto;
            margin-left: 100px;
            background-color: white;
        }

        #textbox1 h5 {
            color: gray;
            margin: 50px;
            font-size: 20px;
        }

        #textbox1 h1 {
            color: brown;
            margin: 52px;
            font-size: 50px;
        }

        #textbox1 h3 {
            color: rgb(193, 188, 188);
            margin: 53px;
            font-size: 30px;
        }

        #textbox1 h4 {
            color: black;
            margin: 53px;
            font-size: 20px;
        }

        .container8 {
            height: 700px;
            width: 1600px;
            border: 1px solid transparent;
            flex-wrap: wrap;
            background-image: url(./container8.jfif);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }


        .footer {
            height: 100vh;
            width: 100%;
            background-color: rgb(35, 34, 34);
            border: 1px solid transparent;
            padding: 50px;
            display: flex;
            justify-content: space-evenly;

        }

        .col {
            flex-basis: 25%;
            flex-grow: 1;
            margin-bottom: 20px;
        }

        .col a {
            display: block;
            text-decoration: none;
            color: gray;
            font-size: 15px;
            margin-bottom: 15px;
        }
       
        .lfooter {
            height: 150px;
            width: 100%;
            background-color: black;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 0 50px;
        }
        
        .lfooter img {
            margin: 0 30px;
        }
        
        .lfooter i {
            margin: 0 15px;
        }
        
        .lfooter h6 {
            color: white;
        }
        
        .lfooter a {
            color: gray;
            text-decoration: none;
            margin-right: 10px;
        }
        
        
        
    </style>
</head>

<body>
    <div class="parent">
        <nav>
            <ul>
                <li><img src="./tcslogo1.svg" alt=""></li>
                <li>What we do</li>
                <li>Who we are</li>
                <li>Insights</li>
                <li>Careers</li>
                <li>Investor</li>
                <li><a href="">CONTACT US</a></li>
                <li><a href="">TCS WOLDWIDE</a></li>
                <li><i class="fa fa-search" aria-hidden="true"></i></li>
                <li><img src="./tata_logo.svg" alt=""></li>
            </ul>
        </nav>

        <div class="container">
            <h1>Collection for <br> Transformation</h1>
        </div>


        <div class="container2">
            <h1>Snapshorts</h1>
            <div class="snapshots">
                <div class="snap" id="snap1"></div>
                <div class="snap" id="snap2"></div>
                <div class="snap" id="snap3"></div>
                <div class="snap" id="snap4"></div>
                <div class="snap" id="snap5"></div>
                <div class="snap" id="snap6"></div>
                <div class="snap" id="snap7"></div>
                <div class="snap" id="snap8"></div>
            </div>
        </div>


        <div class="container3">
            <div class="text" id="text1">
                <h3>GLOBAL THOUGHT LEADERSHIP STUDY</h3>
                <h1>Answer a few questions to unlock insights into innovation with cloud</h1>
            </div>
            <div class="text" id="text2">
                <h1>Are you leveraging your competitive advantage with cloud?</h1>
                <li><i class="fa fa-arrow-left" aria-hidden="true"></i></li>
                <li><i class="fa fa-arrow-right" aria-hidden="true"></i></li>
            </div>

        </div>


        <div class="container4">
            <h1>Insights by interest</h1>
            <h1><a href="">view all</a></h1>
            <hr>
            <div class="box" id="box1"></div>
            <div class="box" id="box2"></div>
            <div class="box" id="box3"></div>
        </div>

        <h1>Discover the TCS difference</h1>
        <div class="container5">
            <img src="" alt="">
        </div>
        <div class="end">
            <div class="container6">
                <div id="textbox">
                    <h5>WHO WE ARE</h5>
                    <h1>We build greater futures through innovation and collective knowledge.</h1>
                    <h3>TCS is an IT services, consulting and business solutions organization that has been partnering
                        with
                        many of the world’s largest businesses in their transformation journeys for over 50 years.</h3>
                    <h4>Get to know us <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i></h4>
                </div>
            </div>

            <h2>Belief in action</h2>
            <div class="container7">
                <div class="con7" id="img1"></div>
                <div class="con7" id="img2"></div>
                <div class="con7" id="img3"></div>
                <div class="con7" id="img4"></div>
                <div class="con7" id="img5"></div>
            </div>

            <div class="container8">
                <div id="textbox1">
                    <h5>WHAT WE DO</h5>
                    <h1>TCS transforms businesses through technology.</h1>
                    <h3>We help businesses successfully navigate digital transformation and drive real growth, drawing
                        on the combined power of experience and contextual knowledge, across a vast ecosystem of
                        expertise.</h3>
                    <h4>Get to know us <i class="fa fa-arrow-circle-o-right" aria-hidden="true"></i></h4>
                </div>
            </div>
        </div>

        <div class="footer">
            <div class="col">
                <a href="#">Industries</a>
                <a href="#">Banking</a>
                <a href="#">Capital Markets</a>
                <a href="#">Consumer Goods and Distribution</a>
                <a href="#">Communication, Media, and Information Services</a>
                <a href="#">Education</a>
                <a href="#">Energy, Resource, and Utilities</a>
                <a href="#">Healthcare</a>
                <a href="#">High Tech</a>
                <a href="#">Insurance</a>
                <a href="#">Life Sciences</a>
                <a href="#">Manufacturing</a>
                <a href="#">Public Services</a>
                <a href="#">Retail</a>
                <a href="#">Travel and Logistics</a>
            </div>
            <div class="col">
                <a href="#">Services</a>
                <a href="#">Cloud</a>
                <a href="#">Cognitive Business Operations</a>
                <a href="#">Consulting</a>
                <a href="#">Cybersecurity</a>
                <a href="#">Data and Analytics</a>
                <a href="#">Enterprise Solutions</a>
                <a href="#">IoT and Digital Engineering</a>
                <a href="#">Sustainability Services</a>
                <a href="#">TCS Interactive</a>
                <a href="#">TCS and AWS Cloud</a>
                <a href="#">TCS Enterprise Cloud</a>
                <a href="#">TCS and Google Cloud</a>
                <a href="#">TCS and Microsoft Cloud</a>
            </div>
            <div class="col">
                <a href="">Products and Platforms</a>
                <a href="">TCS ADD™</a>
                <a href="">TCS BaNCS™</a>
                <a href="">TCS BFSI Platforms</a>
                <a href="">TCS CHROMA™</a>
                <a href="">TCS Customer Intelligence & Insights™</a>
                <a href="">TCS ERP on Cloud</a>
                <a href="">ignio™ Opens in new tab</a>
                <a href="">TCS HOBS™</a>
                <a href="">TCS Intelligent Urban Exchange™</a>
                <a href="">TCS OmniStore™</a>
                <a href="">TCS Optumera™</a>
                <a href="">TCS TAP™</a>
                <a href="">Quartz™ – The Smart Ledgers™</a>
                <a href="">TCS TwinX™</a>
                <a href="">TCS MasterCraft™</a>
                <a href="">Jile™ Opens in new tab</a>
                <a href="">TCS iON™</a>
            </div>
            <div class="col">
                <a href=""> Insights</a>
                <a href="">Customer Stories</a>
                <a href="">Cloud</a>
                <a href="">Blockchain</a>
                <a href="">IoT</a>
                <a href="">Metaverse</a>
                <a href="">Future of Work</a>
                <a href="">Health and Wellness</a>
                <a href="">Sustainability</a>
                <a href="">AI and ML</a>
                <a href="">Cybersecurity</a>
                <a href="">Perspectives</a>
                <a href="">More information</a>
                <a href="">Careers</a>
                <a href="">Corporate Social Responsibility</a>
                <a href="">Diversity, Equity, and Inclusion</a>
                <a href="">Investor Relations Opens in new tab</a>
                <a href="">Sports Sponsorships</a>
                <a href="">TCS Pace™</a>
                <a href="">TCS Research</a>
                <a href="">The TCS Way</a>
                <a href="">Who we are</a>
            </div>
        </div>

       <div class="lfooter"> 
        <img src="./tcslogo1.svg" alt="">
        <i class="fa fa-facebook" aria-hidden="true"></i>
        <i class="fa fa-youtube-play" aria-hidden="true"></i>
        <i class="fa fa-twitter" aria-hidden="true"></i>
        <i class="fa fa-instagram" aria-hidden="true"></i>
        <i class="fa fa-linkedin-square" aria-hidden="true"></i>
        <h6>©2023 TATA Consultancy Services Limited</h6>
        <a href="">Privacy Notice</a>
        <a href="">Security policy</a>
        <a href="">Cookie Policy</a>
        <a href="">California Notice</a>
        <a href=""> at Collection</a>
        <a href="">Disclaimer</a>
        <a href="">Customize</a>
        <a href="">cookies</a>
        
   

       </div>
    </div>

</body>

</html>
