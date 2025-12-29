<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sensorr's 🎧</title>
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#ff9900">
<style>
  body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background: linear-gradient(135deg,#111,#222);
    color: #fff;
    text-align: center;
  }

  header {
    background: url('https://via.placeholder.com/600x300') center/cover no-repeat;
    height: 250px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #ffb703;
    font-size: 2em;
    font-weight: bold;
    text-shadow: 2px 2px 5px #000;
  }

  main {
    padding: 30px 20px;
  }

  .button {
    display: block;
    margin: 15px auto;
    padding: 15px 25px;
    width: 80%;
    max-width: 300px;
    text-decoration: none;
    font-weight: bold;
    font-size: 18px;
    color: #fff;
    background: #ff9900;
    border-radius: 50px;
    transition: 0.3s;
  }

  .button:hover {
    background: #ffb703;
  }

  footer {
    margin: 40px 0 20px;
    font-size: 14px;
    color: #aaa;
  }
</style>
</head>
<body>

<header>
  🎧 Sensorr's
</header>

<main>
  <p>Upcoming Music Artist 🎵</p>
  <a class="button" href="#">🎧 Listen on Audiomack</a>
  <a class="button" href="#">🎵 Follow on TikTok</a>
  <a class="button" href="mailto:moziamichaelaghasensorr@gmail.com">✉ Contact</a>
</main>

<footer>
  &copy; 2025 Sensorr. All rights reserved.
</footer>

<script>
if ("serviceWorker" in navigator) {
  navigator.serviceWorker.register("service-worker.js");
}
</script>

</body>
</html>

