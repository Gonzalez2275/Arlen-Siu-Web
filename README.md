<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Arlen.css">
</head>
<body>
   <div id="conteitemscarrusel">
        <div class="itemCarrusel" id="icarrusel1">
             <div class="tarjetaCarrusel" id="carrusel1">
                  <img src="Primera imgen.jpeg" alt="Presentación">
            </div>
            <div class="flechasCarrusel">
                <a href="#icarrusel6">
                     <i><</i>
                </a>
                <a href="#icarrusel2">
                     <i>></i>
                </a>
            </div>
       </div>
       <div class="itemCarrusel" id="icarrusel2">
             <div class="tarjetaCarrusel" id="carrusel2">
                  <img src="imagen 2.jpeg" alt="Quien fue">
            </div>
            <div class="flechasCarrusel">
                <a href="#icarrusel1">
                     <i><</i>
                </a>
                <a href="#icarrusel3">
                     <i>></i>
                </a>
            </div>
        </div>
        <div class="itemCarrusel" id="icarrusel3">
             <div class="tarjetaCarrusel" id="carrusel3">
                  <img src="imagen 3.jpeg" alt="Datos personales">
            </div>
            <div class="flechasCarrusel">
                <a href="#icarrusel2">
                     <i><</i>
                </a>
                <a href="#icarrusel4">
                     <i>></i>
                </a>
            </div>
        </div>
        <div class="itemCarrusel" id="icarrusel4">
             <div class="tarjetaCarrusel" id="carrusel4">
                  <img src="imagen 4.jpeg" alt="Que hizo">
            </div>
            <div class="flechasCarrusel">
                <a href="#icarrusel3">
                     <i><</i>
                </a>
                <a href="#icarrusel5">
                     <i>></i>
                </a>
            </div>
        </div>
        <div class="itemCarrusel" id="icarrusel5">
             <div class="tarjetaCarrusel" id="carrusel5">
                  <img src="imagen 5.jpeg" alt="Maria Rural">
            </div>
            <div class="flechasCarrusel">
                <a href="#icarrusel4">
                     <i><</i>
                </a>
                <a href="#icarrusel6">
                     <i>></i>
                </a>
            </div>
       </div>
       <div class="itemCarrusel" id="icarrusel6">
             <div class="tarjetaCarrusel" id="carrusel6">
                  <img src="imagen final.jpeg" alt="Legado">
            </div>
            <div class="flechasCarrusel">
                <a href="#icarrusel5">
                     <i><</i>
                </a>
                <a href="#icarrusel1">
                     <i>></i>
                </a>
            </div>
        </div>
    </div>
</body>
</html>

{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

body{
    background-color: rgba(245, 255, 102, 0.486);
}
#conteitemscarrusel{
    height: 600px;
    overflow: hidden;
}

.itemCarrusel{
    height: 100%;
    position: relative;
}

.tarjetaCarrusel{
    height: 100%;
}

.flechasCarrusel{
    position: absolute;
    top: 0;
    height: 100%;
    width: 95%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 30px;
}

#carrusel1{
    background-color: rgb(160, 75, 75);
}

#carrusel2{
    background-color: rgb(99, 99, 190);
}

#carrusel3{
    background-color: rgb(85, 182, 85);
}

#carrusel4{
    background-color: rgb(168, 168, 79);
}

#carrusel5{
    background-color: rgb(146, 112, 49);
}

#carrusel6{
    background-color: rgb(163, 72, 163);
}

a{
    text-decoration: none;
    color: black;
    font-size: 30px;
    font-style: arial;
    font-weight: bold;
}

img{
    width: 100%;
    height: 100%;
}
