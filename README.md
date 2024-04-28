<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Group 6</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #fff;
            color: #333; 
            line-height: 1.6;
            padding: 20px;
        }

        header {
            background-color: #fff;
            color: #446B6F;
            padding: 20px 10; 
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            font-size: 28px;
            margin-bottom: 10px;
            color: #5AA2E0;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #5AA2E0;
            text-decoration: none;
            transition: color 0.6s;
        }

        nav ul li a:hover {
            color: #4182BE; 
        }

        nav ul li a.active {
            font-weight: bold;
        }

        main {
            padding: 40px 0;
        }

        #main {
            text-align: center;
            margin-bottom: 40px;
            display: flex;
            align-items: center;
        }

        #main p {
            font-size: 20px;
            margin-bottom: 20px;
			text-align: left;
        }

        #main img {
            max-width: 550px; 
            height: auto;
            margin-right: 25px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1); 
        }

        #stats {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-bottom: 40px;
        }
        

        .stat-container {
            flex: 0 0 calc(33.33% - 20px);
            margin: 10px;
            text-align: center; 
        }

        .stat-container h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #5AA2E0;
        }

        .stat-container p {
            font-size: 18px;
            margin-top: 10px;
        }

        .img-container {
            position: relative;
            text-align: center;
            color: white;
            margin-bottom: 20px;
            margin-top: 20px;
        }

        .img-container img {
            width: 100%;
            display: block;
        }

        .img-container .centered {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 1;
            max-width: 100%;
        }

        .img-container::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)); 
            z-index: 0; 
        }

        @media screen and (max-width: 768px) {
            header {
                padding: 15px 0;
            }

            nav {
                text-align: center;
            }

            nav ul {
                display: block;
                text-align: center;
            }

            nav ul li {
                display: block;
                margin-bottom: 10px;
            }

            #main {
                flex-direction: column;
                align-items: flex-start;
            }

            #main img {
                margin-right: 0;
                margin-bottom: 20px;
            }

            .stat-container {
                flex: 0 0 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <div class="container">
        <h1>Group 6</h1>
        <nav>
            <ul>
                <li><a href="index.html" class="active">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </div>
</header>

<main>
    <div class="container">
        <section id="main">
            <img src="https://cdn.discordapp.com/attachments/1174619043781677056/1233687973698994186/illustration_1.jpg?ex=662e00f5&is=662caf75&hm=2344d55c74df6cf4c3a1dd2581d00c0e2fb23229cde555f9609e854fc0f68018" alt="Illustration" />
            <div>
                <p>Super Typhoon Odette, known internationally as Rai, was a deadly typhoon that occurred on December 16, 2021. The typhoon's highest wind speed was 280 km/h, dumping 272.1 millimeters of rain in the central and southern Philippines.</p>
                <p>Typhoon Odette was extremely disastrous because it brought heavy rains, intense winds, mudslides, floods, and storm surges, which affected millions of people. Typhoon Odette most severely affected provinces in five regions: Palawan, Negros Occidental, Bohol, Cebu, Negros Oriental, Southern Leyte, Leyte, Dinagat Islands, and Surigao Del Norte.</p>
                <p>Typhoons can affect everyone in the area, especially if you are unprepared. The typhoon can cause unpredictable landslides, heavy rains that can result in high floods, and strong winds that can destroy houses. However, you should always keep an eye on the news in case there are any updates about an upcoming typhoon so that we can prepare ahead of time. </p>
                <p>Secondary disasters such as floods, mudslides, landslides, power outages, destroyed properties, and diseases followed Typhoon Odette.</p>
            </div>
        </section>
    </div>
    
    <div class="container">
        <section id="stats">
            <div class="stat-container">
                <h2>31,607 Families</h2>
                <p>Reported to be displaced in evacuation centers</p>
            </div>
            <div class="stat-container">
                <h2>20,918 Families</h2>
                <p>Sought temporary shelter in 810 evacuation areas</p>
            </div>
            <div class="stat-container">
                <h2>10,689 Families</h2>
                <p>Remained outside the evacuation zones or temporarily</p>
            </div>
            <div class="stat-container">
                <h2>405</h2>
                <p>Deaths</p>
            </div>
            <div class="stat-container">
                <h2>52</h2>
                <p>Reported missing</p>
            </div>
            <div class="stat-container">
                <h2>1,371</h2>
                <p>Injured</p>
            </div>
            <div class="stat-container">
                <h2>404,653</h2>
                <p>Destroyed houses</p>
            </div>
            <div class="stat-container">
                <h2>1,704,205</h2>
                <p>Partially destroyed houses</p>
            </div>
        </section>
    </div>
    
    <div class="container">
        <div class="img-container">
            <img src="https://i.postimg.cc/XJrMZbxf/odette-destruction.jpg" alt="Destroyed">
            <div class="centered">Humanitarian groups sent over PHP 4 million via digital cash transfers to 2,650 families in Eastern Samar towns, providing financial support to low-income individuals three days before Typhoon Odette's arrival, using Global Parametrics' early warning system technology.</div>
        </div>
    </div>
</main>

</body>
</html>
