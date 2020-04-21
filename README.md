# robertoHTML

<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='GRAFKOM.css'>
    
</head>
<body>
    <canvas id="canvas"></canvas>
    <script src='GRAFKOM.js'></script>
</body>
</html>

# robertoCss

#canvas {
    border: 1px solid;
    width: 100%;
    height: 800px;
}

# roberto kondisipintutertutup JS

var myCanvas = document.getElementById('canvas');
var ctx = myCanvas.getContext('2d');
myCanvas.width = myCanvas.scrollWidth;
myCanvas.height = myCanvas.scrollHeight;

ctx.beginPath();
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(2, 80, 502,650);
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(3, 150, 500,10);
ctx.fillStyle='brown';
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(20, 145, 10,18);
ctx.fillStyle='grey';
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(475, 145, 10,18);
ctx.fillStyle='grey';
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(275, 160, 200,500);
ctx.fillStyle='grey';
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(284, 200, 180,420);
ctx.fillStyle='white';
ctx.fill();
ctx.closePath();
//engselkanan
ctx.beginPath();
ctx.arc(417, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)

ctx.fillStyle='grey';
ctx.fill();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(412, 130, 10,40);
ctx.fillStyle='grey';
ctx.fill();
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(412, 130, 10,40);
ctx.closePath();

//engselkiri
ctx.beginPath();
ctx.arc(337, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)

ctx.fillStyle='grey';
ctx.fill();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(332, 130, 10,40);
ctx.fillStyle='grey';
ctx.fill();
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(332, 130, 10,40);
ctx.closePath();


ctx.font = '20pt calibri';
ctx.fillStyle = 'Black';
ctx.fillText(' Pintu Tertutup', 20, 400);

# ARVIANPINTU TRANSFORMASI PINTU TERBUKA

/*bagian ke-2*/
//border
ctx.beginPath();
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(550, 80, 640,650);
ctx.closePath();
//border


//tongkatsangga
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(580, 150, 580,10);
ctx.fillStyle='brown';
ctx.fill();
ctx.closePath();

//engselkanankiri
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(620, 145, 10,18);
ctx.fillStyle='grey';
ctx.fill();
ctx.closePath();
//engselkanan
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(1100, 145, 10,18);
ctx.fillStyle='grey';
ctx.fill();
ctx.closePath();

//pintu kanan
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(900, 160, 200,450);
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(910, 200, 180,370);
ctx.strokeStyle='black';
ctx.stroke();
ctx.closePath();

//engselkanan
ctx.beginPath();
ctx.arc(1050, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='black';
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(1045, 130, 10,40);
ctx.closePath();

//engselkiri
ctx.beginPath();
ctx.arc(950, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='black';
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(945, 130, 10,40);
ctx.closePath();


//pintu kiri

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(630, 160, 200,450);
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(640, 200, 180,370);
ctx.strokeStyle='black';
ctx.stroke();
ctx.closePath();

//engselkanan
ctx.beginPath();
ctx.arc(785, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='black';
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(780, 130, 10,40);
ctx.closePath();

//engselkiri
ctx.beginPath();
ctx.arc(675, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='black';
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(670, 130, 10,40);
ctx.closePath();


//pintu tngah

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(750, 160, 200,450);
ctx.fillStyle='grey';
ctx.fill();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(760, 200, 180,370);
ctx.fillStyle='white';
ctx.fill();
ctx.closePath();

//engselkiri
ctx.beginPath();
ctx.arc(790, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='black';
ctx.fillStyle='grey';
ctx.fill();
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(785, 130, 10,40);
ctx.fillStyle='grey';
ctx.fill();
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(785, 130, 10,40);
ctx.closePath();

//engselkanan
ctx.beginPath();
ctx.arc(900, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='black';
ctx.fillStyle='grey';
ctx.fill();
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(895, 130, 10,40);
ctx.fillStyle='grey';
ctx.fill();
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(895, 130, 10,40);
ctx.closePath();


ctx.font = '20pt calibri';
ctx.fillStyle = 'Black';
ctx.fillText('Gerakan Terbuka dan Tertutupnya Pintu', 650, 670);
//bagian ke dua selesai

# DIKI FIRMANSYAHPINTU TRANSFORMASITERBUKA

