# valentine26
BTECH(CSE-AIML)--- Project - valentine.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Sweet Heart Saanira ❤️</title>

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: radial-gradient(circle at top, #0d0d0d, #1a0000, #330000);
    color: white;
    text-align: center;
    overflow: hidden;
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.card {
    background: rgba(255,255,255,0.05);
    padding: 40px;
    border-radius: 20px;
    box-shadow: 0 0 40px rgba(255,77,109,0.3);
    max-width: 520px;
}

/* Glow titles */
.title {
    font-size: 26px;
    text-shadow: 0 0 10px white, 0 0 30px #ff4d6d;
}

/* Melt line */
.melt {
    margin-top: 15px;
    font-size: 18px;
    color: #ffd6e0;
    text-shadow: 0 0 10px #fff, 0 0 30px #ff4d6d;
}

/* Buttons */
button {
    padding: 10px 22px;
    border-radius: 25px;
    border: none;
    margin: 10px;
    cursor: pointer;
    font-size: 16px;
}
.yes { background:#ff4d6d; color:white; }
.no { background:#555; color:white; }

/* Floating romantic items */
.float {
    position: absolute;
    font-size: 22px;
    animation: rise 6s linear infinite;
}

@keyframes rise {
    0% { transform: translateY(0); opacity:1; }
    100% { transform: translateY(-900px); opacity:0; }
}
</style>
</head>

<body>

<div class="container">
<div class="card" id="main">

<h2 class="title">Hello beautiful, welcome here 💖</h2>
<p>I wanna ask you something… can I?</p>
<button class="yes" onclick="step2()">YES</button>
<button class="no" onclick="alert('Please listen to me 😌 Click YES')">NO</button>

</div>
</div>

<script>

/* Floating roses, kisses, hearts */
for(let i=0;i<35;i++){
let f=document.createElement("span");
f.className="float";
f.innerHTML=["🌹","💋","❤️"][Math.floor(Math.random()*3)];
f.style.left=Math.random()*100+"%";
f.style.bottom="0";
f.style.animationDuration=(Math.random()*3+4)+"s";
document.body.appendChild(f);
}

function step2(){
document.getElementById("main").innerHTML = `
<h2 class="title">Will you be my forever Valentine, Saanira? 💘</h2>
<p class="melt">“My heart found its home the day it found you.” ❤️✨</p>
<button class="yes" onclick="step3()">YES</button>
<button class="no" onclick="alert('Nope 😌 No is not acceptable. Go for YES ❤️')">NO</button>
`;
}

function step3(){
document.getElementById("main").innerHTML = `
<h2>Yayyy I knew it!! ❤️🌹✨</h2>
<h3>Happy Valentine’s Day My Love Saanira 💖</h3>
<p class="melt">“Loving you isn’t a moment in my life — it is my life.”</p>
<p>Do you like this?</p>
<button class="yes" onclick="likeYes()">YES</button>
<button class="no" onclick="likeNo()">NO</button>
`;
}

function likeYes(){
alert("Awww 😘 That means a lot! I love you sooo much sweetheart 💖 Ummmahh!");
}

function likeNo(){
alert("Ooh okay 😌 Love noted. Accept this for today 💕");
}
</script>

</body>
</html>

function step4(){
document.getElementById("main").innerHTML = `
<h2 class="title">Yayyy I knew it!! ❤️🌹</h2>
<p class="melt">“Loving you isn’t a moment in my life — it is my life.” ❤️💋🌹</p>
<p>Do you like this?</p>
<button class="yes" onclick="likeYes()">YES</button>
<button class="no" onclick="likeNo()">NO</button>
`;
}

function likeYes(){
alert("Awww 😘 That means a lot! I love you sooo much sweetheart 💖 Ummmahh!");
}

function likeNo(){
alert("Ooh okay 😌 Love noted. Accept this for today 💕");
}

</script>

</body>
</html>
