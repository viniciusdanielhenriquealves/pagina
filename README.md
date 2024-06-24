<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            font-family: roboto, sans-serif;
        }

        #topbox {
            display: flex;
            flex-direction: column;
            text-align: center;
            width: 500px;
            height: 500px;
            margin: 0 auto;
        }

        .circle {
            background: url(https://files.passeidireto.com/c9f97d56-75d4-48e3-991c-521d60bb4aa3/c9f97d56-75d4-48e3-991c-521d60bb4aa3.jpeg);
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-left: 170px;
            margin-top: 40px;
            background-position: 30% 10%;
            background-size: cover;
            background-repeat: no-repeat;
        }

        .box-container {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }

        .container {
            text-align: center;
        }

        .styled-button {
            background-color: whitesmoke;
            border: none;
            color: black;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            font-size: 16px;
            border-radius: 8px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.15);
            display: inline-flex;
            align-items: center;
            gap: 10px; /*toma gap*/
            margin-top: 15px;
            width: 100px;
            height: 45px;
        }

        .styled-button img {
            width: 30px;
            height: 30px;
        }

        .box2 {
            text-align: center;
        }

        #bottombox {
            margin-left: 500px;
            width: 500px;
            height: 500px;
            margin-top: 80px;
        }

        .big-box {
            margin-left: 10px;
            margin-top: -50px;
            width: 300px;
            height: 320px;
            border-radius: 25px;
            background: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLhcxC5lGHR7Tf8ipXYnXbKwlD8Jjcfr1GSw&s);
            background-position: center;
            background-size: cover;
        }

        .big_box2 {
            margin-left: 510px;
            margin-top: -150px;
            width: 300px;
            height: 250px;
            background: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfd3E-zeiOziqEiKbZnsrbCfkUh6RkQZFZbQ&s);
            border-radius: 25px;
            background-position: center;
            background-size: cover;
        }

        .little-box1 {
            margin-left: 350px;
            width: 200px;
            height: 320px;
            background: url(https://static.poder360.com.br/2021/08/messi-contrato-barcelona.jpg);
            background-position: center;
            background-size: cover;
            border-radius: 20px;
            margin-top: 10px;
        }

        .little-box2 {
            margin-left: 350px;
            width: 200px;
            height: 250px;
            background: url(https://static.ndmais.com.br/2024/06/dieta-messi.jpg);
            background-position: center;
            background-size: cover;
            border-radius: 20px;
            margin-top: 30px;
        }

        .retangle-box {
            margin-left: 220px;
            width: 200px;
            height: 600px;
            background: url(https://imgproxy.ojc.com.br/insecure/fit/800/927/ce/0/plain/http%3A%2F%2Fwww.jornaldotocantins.com.br%2Fpolopoly_fs%2F1.1262949.1492984735%21%2Fimage%2Fimage.JPG_gen%2Fderivatives%2Flandscape_800%2Fimage.JPG);
            background-position: center;
            background-size: cover;
            border-radius: 20px;
            margin-top: 10px;
        }

        .box-space {
            width: 200px;
            height: 630px;
        }

        p {
            color: black;
        }
    </style>

</head>

<body>
    <div>
        <div id="topbox">
            <div class="circle"></div>

            <div class="text">
                <h1> Vinicius Daniel</h1>
                <h3> Student, part-time worker </h3>
                <div class="box-container">
                    <div class="container">
                        <a href="https://www.instagram.com/vinicius_daniel_henrique_alvek/#" class="styled-button" target="_blank">
                            <img src="img/icons8-instagram-30.png" alt="Instagram">
                            <p>Instagram</p>
                        </a>
                        <div>
                            <a href="https://www.leagueofgraphs.com/pt/summoner/br/hightoelo-fmelo" class="styled-button" target="_blank">
                                <img src="img/icons8-jogos-de-motim-30.png" alt="GitHub">
                                <p> Lolzinho </p>
                            </a>
                        </div>
                    </div>
                    <div class="box2">
                        <a href="https://github.com/viniciusdanielhenriquealves" class="styled-button" target="_blank">
                            <img src="img/icons8-github-30.png" alt="GitHub">
                            <p>GitHub</p>
                        </a>
                        <div>
                            <a href="https://www.twitch.tv/pelotinha_bola" class="styled-button" target="_blank">
                                <img src="img/twich_logo_icon_134450.png" alt="twitch">
                                <p>twitch</p>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div id="bottombox">
            <div class="big-box">
                <div class="little-box1">
                    <div class="retangle-box"></div>
                </div>
                <div class="little-box2"></div>
            </div>
        </div>
        <div class="big_box2">
            <div class="box-space"></div>
        </div>
    </div>
</body>

</html>
