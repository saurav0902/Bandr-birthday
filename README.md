!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Bandr</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(black, red);
      color: white;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      overflow-x: hidden;
    }
    h1 {
      font-size: 2.5em;
      margin-top: 20px;
      animation: glow 2s ease-in-out infinite alternate;
    }
    @keyframes glow {
      from { text-shadow: 0 0 10px red; }
      to { text-shadow: 0 0 20px white; }
    }
    img {
      width: 80%;
      max-width: 300px;
      border-radius: 20px;
      margin: 20px 0;
      box-shadow: 0 0 20px white;
      transition: transform 0.5s;
    }
    img:hover {
      transform: scale(1.05);
    }
    p {
      font-size: 1.2em;
      margin: 10px 20px;
    }
    .quote {
      font-style: italic;
      margin: 20px;
    }
    canvas {
      position: fixed;
      top: 0;
      left: 0;
      pointer-events: none;
    }
  </style>
</head>
<body>
  <h1>Happy Birthday Bandr ❤️</h1>

  <p class="quote">“May your day be as beautiful and radiant as your soul. Keep shining, keep growing, and keep inspiring everyone around you. 💛”</p>

  <img src="YOUR_IMAGE_LINK_1" alt="Bandr photo"/>
  <img src="YOUR_IMAGE_LINK_2" alt="Anime photo"/
