
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Anurudh Singh - Official Website</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
    }

    header {
      padding: 22px 8%;
      background: #111827;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      color: #818cf8;
      font-size: 25px;
      font-weight: bold;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 15px;
    }

    .hero {
      min-height: 75vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 30px 20px;
      background: linear-gradient(135deg, #0f172a, #312e81);
    }

    .hero h1 {
      font-size: clamp(35px, 7vw, 60px);
      margin: 20px 0;
    }

    .hero span {
      color: #818cf8;
    }

    .hero p {
      color: #cbd5e1;
      line-height: 1.8;
    }

    .btn {
      display: inline-block;
      background: #6366f1;
      color: white;
      text-decoration: none;
      padding: 14px 25px;
      border-radius: 8px;
      margin-top: 25px;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    section h2 {
      color: #a5b4fc;
      margin-bottom: 20px;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #111827;
      color: #cbd5e1;
    }

    @media (max-width: 500px) {
      header {
        flex-direction: column;
        gap: 18px;
      }

      nav a {
        margin: 0 7px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">ANURUDH.</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <div class="hero" id="home">
      <p>HELLO, WELCOME TO MY WEBSITE</p>

      <h1>I'm <span>Anurudh Singh</span></h1>

      <p>Welcome to my personal website!</p>

      <a href="#contact" class="btn">Contact Me →</a>
    </div>

    <section id="about">
      <h2>About Me</h2>
      <p>
        Hello! My name is Anurudh Singh.
        Welcome to my personal website.
      </p>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>You can contact me through email.</p>

      <a href="mailto:your@email.com" class="btn">
        Send Email
      </a>
    </section>
  </main>

  <footer>
    © 2026 Anurudh Singh | All Rights Reserved
  </footer>

</body>
</html>
