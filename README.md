<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random number</title>

    <link rel = "stylesheet" href="randomcss.css">
    <script src="https://code.jquery.com/jquery-3.6.1.min.js"></script>
    <style>
    body{
    margin:0 auto;
    text-align: center;
    background-color: lightcyan;   
}
.verx{
    display: block;
    padding: 1rem;
    background-color: black;
    font-size: 2rem;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    user-select: none;
    
}
.zahol{
    text-align: center;
    color: aqua;
    user-select: none;
    opacity: 0,5;
}
.click{
    display: inline-block;
    color: rgb(255, 255, 255);
    background-color: black;
    font-size: 2rem;
    align-items: center;
    border-radius: 5px;
    margin: 10px;
    line-height: 1;  
    user-select: none;
}

.butt1 {
    font-size: 2rem;
    text-align: center;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    user-select: none;
}
.rozdil{
    background-color: black;
    width: max-width;
    height: 10px;
    padding: 0;
    user-select: none;
}
.click:hover{
    background-color: rgb(8, 57, 43);
    font-size: 3rem;
}

#tenm{
    text-shadow: 60px 20px 5px rgb(112, 199, 225); /*create a shadow*/
}
    </style>
</head>
<body>
    <div class ="verx">
        <h1 class = "zahol" id = "tenm">Random number</h1>
    </div>

    <div>        
        <h2 class = butt1 >Random number 1-10</h2>
        <button class = "click" id = "clicks" onclick = 'document.getElementById("p").innerHTML = $("#clicks").text(Math.floor(Math.random()* 11))'>Click</button>
        <div id = "rozdil">ᅠ</div>
    </div>
    <hr> <!--create a line -->
    <div>
        <h2 class="butt1">Random Number 1-100</h2>
        <button class="click" id="clicks2" onclick="document.getElementById('p').innerHTML = $('#clicks2').text(Math.floor(Math.random()*101))">Click</button>

    </div>
    <hr>
    <div>
        <h2 class="butt1">Random number 1-1000</h2>
        <button class="click" id = "clicks3" onclick="document.getElementById('p').innerHTML = $('#clicks3').text(Math.floor(Math.random()*1001))">Click</button>
    </div>
    <!--img src=":\Users\Lenovo\OneDrive\Pictures\Saved Pictures\inve.png" alt = "web"--> <!--Create a photo-->
    <!--<img src = "blublu" alt width = 100--> <!--width is 100px-->
    <picture>
    <source media="(max-width:500px)" imgset = "bick.png"> <!--Міняє картинку при ширині 500px-->
    </picture>

    <a href="https://t.me/OleksandrKuz" target="_blank">My inst</a><!--Перекидує на тг в новій вкладці-->
    
</body>
</html>


