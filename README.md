<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Chocolate Day 💖</title>

<link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #ffd6e8, #ffc2d1);
  text-align: center;
  color: #5a2a41;
  overflow-x: hidden;
}

.card {
  margin: 80px auto;
  padding: 40px;
  max-width: 600px;
  background: #fff0f6;
  border-radius: 25px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

h1 {
  font-family: 'Pacifico', cursive;
  font-size: 42px;
  color: #d63384;
}

p {
  font-size: 18px;
  line-height: 1.6;
}

.btn {
  display: inline-block;
  margin-top: 25px;
  padding: 12px 25px;
  font-size: 18px;
  color: white;
  background: #ff4d88;
  border-radius: 30px;
  text-decoration: none;
  transition: 0.3s ease;
  cursor: pointer;
}

.btn:hover {
  background: #e6005c;
  transform: scale(1.05);
}

.click-text {
  margin-top: 30px;
  font-weight: bold;
  font-size: 20px;
  color: #c9184a;
}

/* SECOND PAGE STYLE */
#surprisePage {
  display: none;
  padding: 40px 20px 80px;
}

#surprisePage h2 {
  font-family: 'Pacifico', cursive;
  font-size: 38px;
  color: #b30059;
}

#surprisePage img {
  width: 250px;
  margin: 20px 0;
  border-radius: 20px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

.footer {
  font-size: 22px;
  font-weight: bold;
  margin-top: 40px;
  color: #880e4f;
}

/* Chocolate Rain */
.choco {
  position: fixed;
  top: -50px;
  font-size: 24px;
  animation: fall linear infinite;
}

@keyframes fall {
  to {
    transform: translateY(110vh);
  }
}
</style>
</head>

<body>

<!-- FIRST PAGE -->
<div class="card" id="homePage">
  <h1>Happy Chocolate Day My Bacha 🍫💗</h1>

  <p>
    You are sweeter than every chocolate in the world.  
    Every smile of yours melts my heart like warm cocoa.  
    Being with you makes my life soft, sweet, and full of love.
  </p>

  <p>
    I wish I could hand you chocolates right now…  
    but for now, I’m sending all my love wrapped in sweetness 💕
  </p>

  <div class="click-text">Click there for your chocolate 🍫👇</div>
  <div class="btn" onclick="showSurprise()">Click Here 💝</div>
</div>

<!-- SECOND PAGE -->
<div id="surprisePage">
  <h2>Yayyy Apka Chocolate Idhar Hai 🍫💖</h2>

  <img src="cute.jpg" alt="Cute Teddy with Chocolate">

  <p style="font-size:20px; max-width:600px; margin:auto;">
    A chocolate for the cutest person in my life.  
    May your days always be this sweet and full of love.  
    You
