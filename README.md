# miniature-giggle
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NovaPlay | Gaming Hub</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <header class="navbar">
    <h1 class="logo">NovaPlay</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#games">Games</a>
      <a href="#news">News</a>
      <a href="#community">Community</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="hero-content">
      <h2>Enter the Game</h2>
      <p>The ultimate hub for competitive and casual gamers</p>
      <button class="cta">Play Now</button>
    </div>
  </section>

  <!-- Games Section -->
  <section class="games" id="games">
    <h2>Featured Games</h2>
    <div class="game-grid">
      <div class="game-card">
        <h3>Cyber Arena</h3>
        <p>Fast-paced sci-fi shooter</p>
      </div>
      <div class="game-card">
        <h3>Shadow Realm</h3>
        <p>Dark fantasy RPG</p>
      </div>
      <div class="game-card">
        <h3>Speed Rivals</h3>
        <p>High-octane racing battles</p>
      </div>
    </div>
  </section>

  <!-- News Section -->
  <section class="news" id="news">
    <h2>Latest Updates</h2>
    <p>🔥 New tournaments coming soon. Patch 1.2 drops this week.</p>
  </section>

  <!-- Community Section -->
  <section class="community" id="community">
    <h2>Join the Community</h2>
    <p>Connect with players worldwide</p>
    <button class="cta">Join Discord</button>
  </section>

  <!-- Contact Section -->
  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Email" required />
      <textarea placeholder="Message"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>© 2026 NovaPlay. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
