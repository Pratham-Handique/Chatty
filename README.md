<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chatty Screens</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #121212;
      color: #fff;
    }
    header {
      text-align: center;
      padding: 20px;
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }
    .screen {
      border: 2px solid #444;
      border-radius: 10px;
      overflow: hidden;
      background: #1e1e1e;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .screen:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.5);
    }
    .screen img {
      width: 100%;
      height: auto;
      display: block;
    }
    .screen-title {
      padding: 10px;
      text-align: center;
      font-size: 1rem;
      font-weight: bold;
      color: #ffba08;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #1e1e1e;
      color: #fff;
      font-size: 0.9rem;
    }
    footer a {
      color: #2575fc;
      text-decoration: none;
    }
    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>Chatty Screens</header>
  <div class="container">
    <div class="screen">
      <img src="your-first-image-link.png" alt="Login Screen">
      <div class="screen-title">Login Screen</div>
    </div>
    <div class="screen">
      <img src="your-second-image-link.png" alt="Profile Screen">
      <div class="screen-title">Profile Screen</div>
    </div>
    <div class="screen">
      <img src="your-third-image-link.png" alt="Chat Interface">
      <div class="screen-title">Chat Interface</div>
    </div>
  </div>
  <footer>
    © 2024 Chatty Application | Designed by <a href="#">Your Name</a>
  </footer>
</body>
</html>
