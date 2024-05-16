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
            background-color: rgb(0, 0, 0);
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-left: 170px;
            margin-top: 40px;
        }

        .box {
            background-color: green;
            width: 120px;
            height: 40px;
            border-radius: 10px;
            margin-left: 100px;
        }

        .box2 {
            background-color: green;
            width: 120px;
            height: 40px;
            border-radius: 10px;
            margin-left: 250px;
            font-size: 30px;
            
        }

        #bottombox {
        margin-left: 400px;
            width: 500px;
            height: 500px;
            
        }

        .big-box {
            margin-left: 10px;
            margin-top: 20px;
            width: 600px;
            height: 700px;
            background-color: red;
            border-radius: 25px;
        }
        .little-box1{    margin: 0px auto;
           margin-left: 650px;
            width: 200px;
            height: 345px;
            background-color:red;
            border-radius: 20px;
         }
         .little-box2{margin-top: 10px;
           margin-left: 650px;
            width: 200px;
            height: 345px;
            background-color: red;
            border-radius: 20px;

         }
         .retangle-box{margin-top: 10px;
           margin-left: 220px;
            width: 200px;
            height: 700px;
            background-color: red;
            border-radius: 20px;
}

    </style>

</head>

<body>
    <div>
        <div id="topbox">
            <div class="circle"> </div>

            <div class="text">
                <h1> Vinicius Daniel</h1>
                <h3> Stundent, part-time worker </h3>
                <div class="box2">GitHub </div>
                <br>
                <div class="box"> </div>
                  
               
            </div>
        </div>



        <div id="bottombox">
            <div class="big-box">
                <div class="little-box1">
                    <div class="retangle-box">

                    </div>
                </div>
                <div class="little-box2">
                    
                </div>
                

        </div>
            
        </div>
    </div>
</body>

</html>
