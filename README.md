<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WinZone Africa</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#0c1d36;
color:white;
}

header{
background:#12284a;
padding:15px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-size:28px;
font-weight:bold;
color:#27d867;
}

.balance{
background:#27d867;
padding:8px 15px;
border-radius:20px;
color:#000;
font-weight:bold;
}

.banner{
padding:30px;
text-align:center;
background:linear-gradient(90deg,#12284a,#1e3d6b);
}

.banner h1{
font-size:32px;
margin-bottom:10px;
}

.buttons{
display:flex;
justify-content:center;
gap:10px;
margin-top:20px;
}

.btn{
padding:12px 20px;
border:none;
border-radius:8px;
font-weight:bold;
cursor:pointer;
}

.deposit{
background:#27d867;
}

.withdraw{
background:#ffc107;
}

.games{
padding:20px;
}

.games h2{
margin-bottom:15px;
}

.game-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:15px;
}

.game{
background:#12284a;
padding:20px;
border-radius:10px;
text-align:center;
}

.bottom-nav{
position:fixed;
bottom:0;
width:100%;
background:#12284a;
display:flex;
justify-content:space-around;
padding:15px;
}

.bottom-nav a{
color:white;
text-decoration:none;
font-size:14px;
}
</style>
</head>

<body>

<header>
<div class="logo">WINZONE</div>
<div class="balance">GHS 0.00</div>
</header>

<section class="banner">
<h1>Welcome to WinZone</h1>
<p>Sports Style Gaming Platform</p>

<div class="buttons">
<button class="btn deposit">Deposit</button>
<button class="btn withdraw">Withdraw</button>
</div>
</section>

<section class="games">
<h2>Popular Games</h2>

<div class="game-grid">

<div class="game">
<h3>Football</h3>
<p>Play Now</p>
</div>

<div class="game">
<h3>Basketball</h3>
<p>Play Now</p>
</div>

<div class="game">
<h3>Tennis</h3>
<p>Play Now</p>
</div>

<div class="game">
<h3>Virtual Sports</h3>
<p>Play Now</p>
</div>

</div>
</section>

<div class="bottom-nav">
<a href="#">Home</a>
<a href="#">Games</a>
<a href="#">Wallet</a>
<a href="#">Support</a>
<a href="#">Profile</a>
</div>

</body>
</html>
