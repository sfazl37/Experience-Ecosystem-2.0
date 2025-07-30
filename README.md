<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Experience Enabler Deck</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-dark: #121212;
      --card-bg: #1f1f1f;
      --accent-beige: #f5deb3;
      --accent-brown: #c49a6c;
      --text-light: #e0e0e0;
      --highlight: #ffb347;
    }
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: var(--bg-dark);
      color: var(--text-light);
      overflow-x: hidden;
    }
    .slide {
      min-height: 100vh;
      padding: 60px 40px;
      box-sizing: border-box;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      scroll-snap-align: start;
    }
    .title-slide {
      background: linear-gradient(135deg, #2c2c2c, #1e1e1e);
      text-align: center;
      color: var(--highlight);
    }
    h1, h2 {
      color: var(--accent-beige);
    }
    h1 {
      font-size: 3rem;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    h3 {
      color: var(--accent-brown);
      font-weight: normal;
    }
    ul {
      margin-top: 10px;
      padding-left: 1.2rem;
      line-height: 1.6;
    }
    .icon {
      width: 50px;
      height: 50px;
      vertical-align: middle;
      margin-right: 10px;
    }
    .slide-content {
      background-color: var(--card-bg);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.5);
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
      align-items: center;
      max-width: 1000px;
      transition: transform 0.3s ease;
    }
    .slide-content:hover {
      transform: scale(1.02);
    }
    .text-box {
      flex: 1;
      min-width: 300px;
    }
    .image-box img {
      max-width: 250px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }
    html {
      scroll-snap-type: y mandatory;
      scroll-behavior: smooth;
    }
    .button-nav {
      position: fixed;
      bottom: 20px;
      left: 50%;
      transform: translateX(-50%);
      z-index: 999;
    }
    .button-nav button {
      background-color: var(--highlight);
      color: #000;
      padding: 10px 20px;
      border: none;
      margin: 0 5px;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 600;
      box-shadow: 0 2px 8px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>  <!-- Slide 1: Title -->  <div class="slide title-slide">
    <h1>🔁 Evolving the Role of Experience Enablers</h1>
    <h3>Modern, Empathetic & Data-Led Approaches</h3>
    <p>By: [Your Name]</p>
  </div>  <!-- Additional slides here in same format -->  <!-- Use slide-content + text-box + image-box for layout -->  <div class="button-nav">
    <button onclick="window.scrollBy(0, window.innerHeight)">Next ⬇️</button>
    <button onclick="window.scrollBy(0, -window.innerHeight)">⬆️ Back</button>
  </div></body>
</html>