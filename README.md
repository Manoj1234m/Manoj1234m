
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ride On - Motorcycle Game</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Ride On - The Ultimate Motorcycle Game</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#screenshots">Screenshots</a>
      <a href="#download">Download</a>
      <a href="#leaderboard">Leaderboard</a>
    </nav>
  </header>

  <section id="hero">
    <h2>Experience the thrill of racing!</h2>
    <button onclick="window.location.href='#download'">Play Now</button>
  </section>

  <section id="about">
    <h2>About the Game</h2>
    <p>High-speed motorcycle action with stunts, challenges, and endless fun!</p>
  </section>

  <section id="leaderboard">
    <h2>Top Players</h2>
    <div id="leaderboard-data"></div>
  </section>

  <footer>
    <p>© 2024 Ride On. All Rights Reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #121212;
  color: #fff;
}

header {
  background: #222;
  padding: 1em;
  text-align: center;
}

nav a {
  margin: 0 10px;
  color: #f1c40f;
  text-decoration: none;
}

#hero {
  text-align: center;
  padding: 50px 20px;
  background: url('motorcycle-bg.jpg') no-repeat center/cover;
}

#leaderboard {
  margin: 20px auto;
  padding: 20px;
  background: #333;
}
