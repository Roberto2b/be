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

#robertoslidingdoorpintutertutupjs

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
ctx.rect(3, 150, 500, 10);
ctx.fillStyle='black'
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(20, 145, 10,18);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(475, 145, 10,18);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(275, 160, 200,450);
ctx.fillStyle='#7B3638';
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(284, 200, 180,370);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();

//engselkanan
ctx.beginPath();
ctx.arc(417, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.fillStyle='brown';
ctx.fill();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(412, 130, 10,40);
ctx.fillStyle='grey';
ctx.fill();
ctx.strokeStyle='brown';
ctx.lineWidth=1;
ctx.strokeRect(412, 130, 10,40);
ctx.closePath();

//engselkiri
ctx.beginPath();
ctx.arc(337, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.fillStyle='brown';
ctx.fill();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(332, 130, 10,40);
ctx.fillStyle='grey';
ctx.fill();
ctx.strokeStyle='brown';
ctx.lineWidth=1;
ctx.strokeRect(332, 130, 10,40);
ctx.closePath();


ctx.font = '20pt calibri';
ctx.fillStyle = 'Black';
ctx.fillText(' Pintu Tertutup', 20, 400);

#arvianslidingdoortransformasiprosespintutertutupjs
/*bagian ke-2*/
//border
ctx.beginPath();
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(520, 80, 610,650);
ctx.closePath();
//border

//tongkatsangga
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(550, 150, 580,10);
ctx.fillStyle='black';
ctx.fill();
ctx.closePath();

//engselkanankiri
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(620, 145, 10,18);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();
//engselkanan
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(1100, 145, 10,18);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();

//pintu kanan
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(900, 160, 200,450);
ctx.strokeStyle='grey';
ctx.lineWidth=1;
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(910, 200, 180,370);
ctx.strokeStyle='grey';
ctx.stroke();
ctx.closePath();

//engselkanan
ctx.beginPath();
ctx.arc(1050, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='grey';
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='grey';
ctx.lineWidth=1;
ctx.strokeRect(1045, 130, 10,40);
ctx.closePath();

//engselkiri
ctx.beginPath();
ctx.arc(950, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='grey';
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='grey';
ctx.lineWidth=1;
ctx.strokeRect(945, 130, 10,40);
ctx.closePath();


//pintu kiri

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(630, 160, 200,450);
ctx.strokeStyle='grey';
ctx.lineWidth=1;
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(640, 200, 180,370);
ctx.strokeStyle='grey';
ctx.stroke();
ctx.closePath();

//engselkanan
ctx.beginPath();
ctx.arc(785, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='grey';
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='grey';
ctx.lineWidth=1;
ctx.strokeRect(780, 130, 10,40);
ctx.closePath();

//engselkiri
ctx.beginPath();
ctx.arc(675, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='grey';
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='grey';
ctx.lineWidth=1;
ctx.strokeRect(670, 130, 10,40);
ctx.closePath();


//pintu tengah

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(750, 160, 200,450);
ctx.fillStyle='#7B3638';
ctx.fill();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(760, 200, 180,370);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();

//engselkiri
ctx.beginPath();
ctx.arc(790, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='brown';
ctx.fillStyle='brown';
ctx.fill();
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(785, 130, 10,40);
ctx.fillStyle='grey';
ctx.fill();
ctx.strokeStyle='brown';
ctx.lineWidth=1;
ctx.strokeRect(785, 130, 10,40);
ctx.closePath();

//engselkanan
ctx.beginPath();
ctx.arc(900, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='brown';
ctx.fillStyle='brown';
ctx.fill();
ctx.stroke();
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(895, 130, 10,40);
ctx.fillStyle='grey';
ctx.fill();
ctx.strokeStyle='brown';
ctx.lineWidth=1;
ctx.strokeRect(895, 130, 10,40);
ctx.closePath();


ctx.font = '20pt calibri';
ctx.fillStyle = 'Black';
ctx.fillText('Gerakan Terbuka dan Tertutupnya Pintu', 650, 670);
//bagian ke dua selesai

#dikifirmansyahslidingdoortransformasiprosespintuterbukajs

// pintu ketiga
ctx.beginPath();
ctx.strokeStyle='black';
ctx.lineWidth=1;
ctx.strokeRect(1150, 80, 502,650);
ctx.closePath();
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(3, 150, 500,10);
ctx.fillStyle='brown';
ctx.fill();
ctx.closePath();

// tongkat sangga
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(1150, 150, 500,10);
ctx.fillStyle='black';
ctx.fill();
ctx.closePath();

// pembatas kiri
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(1180, 145, 10,18);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();
//pembatas kanan
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(1620, 145, 10,18);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();

// pintu
ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(1190, 160, 200,450);
ctx.fillStyle='#7B3638';
ctx.fill();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.rect(1200, 200, 180,370);
ctx.fillStyle='#2C2627';
ctx.fill();
ctx.closePath();

// engsel kiri 

ctx.beginPath();
ctx.arc(1215, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='brown';
ctx.fillStyle='brown';
ctx.fill();
ctx.stroke();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='brown';
ctx.lineWidth=1;
ctx.strokeRect(1210, 130, 10,40);
ctx.closePath();


//engsel kanan
ctx.beginPath();
ctx.arc(1350, 140, 9, 0, Math.PI*2); //x,y,radius, startAngle, endAngle, arahJarumJam(true / false:default)
ctx.strokeStyle='brown';
ctx.fillStyle='brown';
ctx.fill();
ctx.stroke();
ctx.closePath();

ctx.beginPath();
ctx.moveTo(170,80);
ctx.strokeStyle='brown';
ctx.lineWidth=1;
ctx.strokeRect(1345, 130, 10,40);
ctx.closePath();

ctx.font = '20pt calibri';
ctx.fillStyle = 'Black';
ctx.fillText('Pintu Terbuka', 1220, 670);
// end pintu ketiga
