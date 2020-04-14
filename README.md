# NVL-CSS-P6a
tablas de css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escala de Mosh</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <table>
        <th>
            <td><strong> Dureza </strong></td>
            <td><strong> Mineral </strong></td>
            <td class="se-raya"><strong> Se raya con/raya a </strong></td>
            <td><strong> Composición </strong></td>
            <td class="imagen"><strong> Imagen </strong></td>
        </th>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: white;">1</td>
            <td>Talco</td>
            <td>Se puede rayar fácilmente con la uña</td>
            <td>Mg3Si4O10(OH)2</td>
            <td class="imagen"> <img src="img/talco.jpg" alt="" width="30%" height="50"></td>
            
            
            caption {
    text-align: center;
}
table {
    margin-top: 60px;
    margin-left: 50px;
    
    
} 
td { 
    border: 1px solid black;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-right: 10px;
    padding-left: 10px;
}
.se-raya{
    text-align: center;
    padding-right: 100px;
    padding-left: 100px;
    padding-top: 5px;
    padding-bottom: 5px;

}
.numero{
    text-align: center;
}
.uno {
    border: white;

}
.imagen {
    text-align: center;
}
            
        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(230, 230, 230);">2</td>
            <td>Yeso</td>
            <td>Se puede rayar con la uña con más dificultad</td>
            <td>CaSO4·2H2O</td>
            <td class="imagen"><img src="img/yeso.jpg" alt="" width="30%" height="50vh"></td>
            
        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(209, 207, 207);">3</td>
            <td>Calcita</td>
            <td>Se puede rayar con una moneda de cobre</td>
            <td>CaCO3</td>
            <td class="imagen"> <img src="img/calcita.jpg" width="30%" height="50vh" alt=""></td>
            
        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(187, 186, 186);">4</td>
            <td>Fluorita</td>
            <td>Se puede rayar con un cuchillo de acero</td>
            <td>CaF2</td>
            <td class="imagen"><img src="img/fluorita.jpg" width="30%" height="50vh" alt=""></td>
            
        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(161, 160, 160);">5</td>
            <td>Apatito</td>
            <td>Se puede rayar difícilmente con un cuchillo</td>
            <td>Ca5(PO4)3(OH-,Cl-,F-)l</td>
            <td class="imagen"><img src="img/apatito.jpg" width="30%" height="50" alt=""></td>
            
        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(143, 143, 143);">6</td>
            <td>Ortosa</td>
            <td>Se puede rayar con una lija para el acero</td>
            <td>KAlSi3O8</td>
            <td class="imagen"><img src="img/ortosa.jpg" width="30%" height="50vh" alt=""></td>
            
        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(114, 114, 114); color: white;">7</td>
            <td>Cuarzo</td>
            <td>Raya el vidrio</td>
            <td>SiO2</td>
            <td class="imagen"><img src="img/cuarzo.jpg" width="30%" height="60" alt=""></td>
            

        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(90, 90, 90); color: white;">8</td>
            <td>Topacio</td>
            <td>Rayado por herramientas de carburo de wolframio</td>
            <td>Al2SiO4(OH-,F-)2</td>
            <td class="imagen"><img src="img/topacio.jpg" width="30%" height="50vh" alt=""></td>
            
        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(61, 61, 61); color: white;">9</td>
            <td>Corindón</td>
            <td>Rayado por herramientas de carburo de silicio</td>
            <td>Al2O3</td>
            <td class="imagen"><img src="img/corindon.jpg" width="30%" height="50vh" alt=""></td>
            
        </tr>
        <tr>
            <td class="uno"></td>
            <td class="numero" style="background-color: rgb(0, 0, 0); color: white;">10</td>
            <td>Diamante</td>
            <td>El material más duro en esta escala (rayado por otro diamante).</td>
            <td>C</td>
            <td class="imagen"> <img src="img/diamante.jpg" width="30%" height="50vh" alt=""></td>
            
        </tr>
    </table>
</body>
</html>
