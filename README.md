# Sensies
Premium Sensi Web App
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ARGUS VAULT SENSI</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#0f0f0f;
    color:white;
    text-align:center;
}

header{
    padding:20px;
    font-size:28px;
    font-weight:bold;
    color:#00ffd5;
}

.card{
    width:90%;
    max-width:400px;
    margin:20px auto;
    padding:20px;
    border-radius:15px;
    background:#1a1a1a;
}

button{
    width:100%;
    padding:12px;
    margin:8px 0;
    border:none;
    border-radius:10px;
    font-weight:bold;
    cursor:pointer;
}

.btn3{background:#ff4d4d;color:white;}
.btn4{background:#ffaa00;color:black;}
.btn5{background:#bb66ff;color:white;}
.btn6{background:#00ff99;color:black;}

#output{
    margin-top:15px;
    padding:10px;
    background:#111;
    border-radius:10px;
    white-space:pre-line;
}
</style>
</head>

<body>

<header>🔥 ARGUS VAULT SENSI</header>

<div class="card">

<button class="btn3" onclick="showSensi('3GB')">3GB RAM</button>
<button class="btn4" onclick="showSensi('4GB')">4GB RAM</button>
<button class="btn5" onclick="showSensi('5GB')">5GB RAM</button>
<button class="btn6" onclick="showSensi('6GB')">6GB RAM</button>

<div id="output">
Select a RAM option 👆
</div>

</div>

<script>
function showSensi(ram){

let text="";

if(ram==="3GB"){
text=`🎯 3GB SENSI

General : 85
Red Dot : 80
2x Scope : 75
4x Scope : 70
AWM : 60`;
}

if(ram==="4GB"){
text=`🎯 4GB SENSI

General : 92
Red Dot : 88
2x Scope : 84
4x Scope : 78
AWM : 65`;
}

if(ram==="5GB"){
text=`🔥 5GB PRO SENSI

General : 97
Red Dot : 94
2x Scope : 91
4x Scope : 87
AWM : 75`;
}

if(ram==="6GB"){
text=`🚀 6GB ULTRA SENSI

General : 100
Red Dot : 97
2x Scope : 94
4x Scope : 90
AWM : 80`;
}

document.getElementById("output").innerText=text;
}
</script>

</body>
</html>
