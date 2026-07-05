<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Süleyman | İletişim</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{
height:100vh;
overflow:hidden;
background:#090909;
display:flex;
justify-content:center;
align-items:center;
color:white;
}

/* Hareketli Gradient */

body:before{
content:'';
position:fixed;
width:220%;
height:220%;
background:
radial-gradient(circle,#00ffd55a 0%,transparent 18%),
radial-gradient(circle,#ff00ff33 0%,transparent 20%),
radial-gradient(circle,#0066ff44 0%,transparent 22%);
animation:bgMove 25s linear infinite;
}

@keyframes bgMove{
0%{transform:translate(-20%,-20%) rotate(0deg);}
100%{transform:translate(-20%,-20%) rotate(360deg);}
}

.card{

position:relative;
z-index:2;

width:420px;
max-width:92%;

padding:45px;

background:rgba(255,255,255,.05);

border:1px solid rgba(255,255,255,.1);

backdrop-filter:blur(18px);

border-radius:24px;

text-align:center;

box-shadow:0 0 60px rgba(0,255,255,.15);

animation:fade 1s;
}

@keyframes fade{

from{
opacity:0;
transform:translateY(40px);
}

to{
opacity:1;
transform:none;
}

}

.avatar{

width:110px;
height:110px;

margin:auto;

border-radius:50%;

background:linear-gradient(135deg,#00ffe1,#0066ff);

display:flex;
align-items:center;
justify-content:center;

font-size:50px;

margin-bottom:25px;

box-shadow:0 0 30px cyan;

animation:pulse 3s infinite;

}

@keyframes pulse{

50%{
transform:scale(1.08);
box-shadow:0 0 45px cyan;
}

}

h1{

font-size:34px;

margin-bottom:10px;

}

p{

opacity:.75;

margin-bottom:35px;

}

.button{

display:block;

text-decoration:none;

padding:17px;

margin:15px 0;

border-radius:15px;

font-weight:600;

transition:.35s;

color:white;

font-size:18px;

}

.whatsapp{

background:#25D366;

}

.telegram{

background:#229ED9;

}

.site{

background:#8b5cf6;

}

.button:hover{

transform:translateY(-4px) scale(1.03);

box-shadow:0 10px 35px rgba(255,255,255,.18);

}

.footer{

margin-top:35px;

font-size:13px;

opacity:.45;

}

@media(max-width:500px){

.card{
padding:35px 25px;
}

h1{
font-size:28px;
}

.button{
font-size:17px;
}

}

</style>

</head>

<body>

<div class="card">

<div class="avatar">
🎰
</div>

<h1>Süleyman</h1>

<p>
Güncel iletişim kanalları aşağıdadır.
</p>

<a class="button whatsapp"
href="https://wa.me/995593589722"
target="_blank">

📱 WhatsApp

</a>

<a class="button telegram"
href="https://t.me/suleymanslot"
target="_blank">

✈️ Telegram

</a>

<a class="button site"
href="https://vegasslot345.com"
target="_blank">

🎲 Vegasslot Güncel Giriş

</a>

<div class="footer">

© 2026

</div>

</div>

</body>
</html>
