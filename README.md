<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Play With Brain Zone</title>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

body{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    font-family:Arial,sans-serif;
    background:linear-gradient(135deg,#090d1f,#16245c,#07152f);
    color:white;
}

.menu{
    width:92%;
    max-width:450px;
    text-align:center;
    padding:30px 20px;
}

h1{
    font-size:32px;
    margin-bottom:10px;
}

.subtitle{
    color:#bfc9ff;
    margin-bottom:30px;
    font-size:16px;
}

.game-btn{
    display:block;
    width:100%;
    padding:20px;
    margin:16px 0;
    border:none;
    border-radius:18px;
    font-size:20px;
    font-weight:bold;
    color:white;
    background:linear-gradient(135deg,#263b91,#405de6);
    box-shadow:0 8px 20px rgba(0,0,0,0.35);
    cursor:pointer;
    text-decoration:none;
    transition:0.2s;
}

.game-btn:active{
    transform:scale(0.96);
}

.number{
    background:linear-gradient(135deg,#6a35d4,#3159e8);
}

.snake{
    background:linear-gradient(135deg,#087f55,#16b979);
}

.tic{
    background:linear-gradient(135deg,#b83280,#e94c9b);
}

.footer{
    margin-top:28px;
    color:#8f9bd0;
    font-size:13px;
}
</style>
</head>

<body>

<div class="menu">

<h1>🎮 Play With Brain Zone</h1>

<div class="subtitle">
Choose a game and start playing!
</div>

<a
class="game-btn number"
href="https://renuy5704-rgb.github.io/Number-reasoning-/">
🧠 Number Reasoning
</a>

<a
class="game-btn snake"
href="https://renuy5704-rgb.github.io/Snake-feed/">
🐍 Snake Feed
</a>

<a
class="game-btn tic"
href="https://renuy5704-rgb.github.io/Tuc-tac-toe/">
❌ Tic-Tac-Toe
</a>

<div class="footer">
One QR • Three Games 🎯
</div>

</div>

</body>
</html>
