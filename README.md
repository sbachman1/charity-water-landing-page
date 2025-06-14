# charity-water-landing-page <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Charity: Water | Clean Water. Real Impact.</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #000;
      color: #fff;
    }

    .hero {
      background: url('img/hero-image.jpeg') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      align-items: center;
      padding-left: 5%;
    }

    .hero-text {
      max-width: 600px;
    }

    .hero h1 {
      font-size: 3.5rem;
      font-weight: 700;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }

    .button-group {
      display: flex;
      gap: 1rem;
    }

    .cta-button, .info-button {
      padding: 1rem 1.5rem;
      font-size: 1rem;
      font-weight: bold;
      border-radius: 8px;
      cursor: pointer;
      border: none;
    }

    .cta-button {
      background-color: #fcb900;
      color: #000;
    }

    .cta-button:hover {
      background-color: #e6a800;
    }

    .info-button {
      background-color: #fff;
      color: #000;
      border: 2px solid #fff;
    }

    .info-button:hover {
      background-color: #f0f0f0;
    }

    nav {
      position: absolute;
      top: 20px;
      left: 20px;
      right: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .logo img {
      height: 48px;
    }

    .login-button {
      background-color: #fcb900;
      color: #000;
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
    }

    .login-button:hover {
      background-color: #e6a800;
    }
  </style>
</head>
<body>
  <nav>
    <div class="logo">
      <img src="img/charity-water-logo.jpeg" alt="Charity: water logo" />
    </div>
    <button class="login-button">Log In</button>
  </nav>

  <header class="hero">
    <div class="hero-text">
      <h1>Clean Water.<br>Real Impact.</h1>
      <p>Donate $10, track the change. Give back with purpose—in seconds.</p>
      <div class="button-group">
        <button class="info-button">See Where Your $10 Goes</button>
        <button class="cta-button">TAKE ACTION</button>
      </div>
    </div>
  </header>
</body>
</html>
