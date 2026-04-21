# Birthday--surprise
This is my first respiratory on GitHub
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For Someone Special ❤️</title>
<style>
body {
  margin:0;
  font-family: Arial;
  background: black;
  color: white;
  text-align:center;
}
.container {
  margin-top: 100px;
}
button {
  padding: 15px 30px;
  font-size: 18px;
  background: pink;
  border: none;
  border-radius: 10px;
}
.hidden {
  display:none;
}
</style>
</head>
<body>

<div class="container">
  <h1>Hey ❤️</h1>
  <p>I have something for you...</p>
  <button onclick="showSurprise()">Open 🎁</button>
</div>

<div id="surprise" class="hidden">
  <h1>Happy Birthday My Love 🎂❤️</h1>
  <p>You are the best thing in my life 💖</p>
  <p>I made this just for you 😘</p>
</div>

<script>
function showSurprise() {
  document.querySelector('.container').style.display = "none";
  document.getElementById('surprise').style.display = "block";
}
</script>

</body>
</html>
