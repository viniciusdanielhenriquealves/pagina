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
            background:url(https://files.passeidireto.com/c9f97d56-75d4-48e3-991c-521d60bb4aa3/c9f97d56-75d4-48e3-991c-521d60bb4aa3.jpeg);
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-left: 170px;
            margin-top: 40px;
            background-position: 30% 10%;
            background-size: cover;
            background-repeat: no-repeat ;
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
    background-color: #4CAF50; /* Verde */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.3s;
    border-radius: 8px;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.15);
    display: inline-block;
    margin: 10px;
}

.styled-button:hover {
    background-color: #45a049;
    transform: scale(1.05);
}

.styled-button:active {
    background-color: #3e8e41;
    transform: scale(0.95);
}


        .box2 {
            background-color: green;
            width: 120px;
            height: 40px;
            border-radius: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 20px;
        }

    
        #bottombox {
            margin-left: 500px;
            width: 500px;
            height: 500px;
        }

        .big-box{
            margin-left: 10px;
            margin-top: -50px;
            width: 300px;
            height: 320px;
            background-color: red;
            border-radius: 25px;
        }

        .big_box2{
            margin-left: 510px;
            margin-top: -120px;
            width: 300px;
            height: 320px;
            background-color: red;
            border-radius: 25px;

        }
        
        .little-box1,
        .little-box2,
        .retangle-box {
            margin-left: 350px;
            width: 200px;
            height: 345px;
            background-color: red;
            border-radius: 20px;
            margin-top: 10px;
        }

        .retangle-box {
            margin-left: 220px;
            width: 200px;
            height: 700px;
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
                        <a href="https://www.instagram.com/vinicius_daniel_henrique_alvek/#" class="styled-button" target="_blank">Instagram</a>
                    </div>
                    <div class="box2">
                        <p style="margin: 0;"> github   </p>
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

        </div>
    </div>
</body>

</html>
