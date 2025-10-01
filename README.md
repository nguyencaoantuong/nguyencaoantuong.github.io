<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="icon" href="https://raw.githubusercontent.com/NammIsADev/nammisadev.github.io/main/favicon.ico" type="image/x-icon" />
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>namm's page</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    :root {
      --bg: #0f1117;
      --text: #e0e0e0;
      --accent: #258aff;
      --accent-hover: #4ea6ff;
      --card: #1a1d29;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      background: var(--bg);
      color: var(--text);
      font-family: 'Segoe UI', sans-serif;
      transition: background 0.3s, color 0.3s;
    }

    .toggle-btn {
      position: fixed;
      top: 1rem;
      right: 1rem;
      background: var(--accent);
      color: #fff;
      border: none;
      padding: 0.4rem 1rem;
      border-radius: 2rem;
      cursor: pointer;
      display: none;
    }

    .container {
      max-width: 750px;
      margin: auto;
      padding: 2rem;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 1rem;
      border: 3px solid var(--accent);
    }

    .center {
      text-align: center;
    }

    h1 {
      margin: 0.5rem 0;
      font-size: 2.2rem;
      color: var(--accent);
    }

    h2 {
      font-size: 1.3rem;
      margin-bottom: 0.6rem;
      color: var(--accent);
    }

    p, ul {
      margin: 0.3rem 0 1rem;
      line-height: 1.6;
    }

    .badge {
      display: inline-block;
      background: var(--accent);
      color: #fff;
      padding: 0.3rem 0.7rem;
      border-radius: 999px;
      font-size: 0.85rem;
      margin: 0.2rem;
      transition: background 0.3s, transform 0.2s;
    }

    .badge:hover {
      background: var(--accent-hover);
      transform: scale(1.05);
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    .socials a {
      margin-right: 0.6rem;
      display: inline-block;
      margin-top: 0.3rem;
      font-size: 1rem;
      transition: transform 0.2s;
    }

    .socials a:hover {
      transform: scale(1.05);
    }

    .socials a i, .socials a img {
      margin-right: 0.3rem;
      vertical-align: middle;
      height: 1em;
    }

    .card {
      background: var(--card);
      padding: 1.4rem;
      border-radius: 1rem;
      box-shadow: 0 3px 15px rgba(0, 0, 0, 0.08);
      margin-bottom: 2rem;
      animation: fadein 0.6s ease-in-out;
    }

    .project-card {
      background: var(--card);
      padding: 1rem;
      border-radius: 1rem;
      margin-top: 1rem;
      margin-bottom: 1rem;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      animation: fadein 0.6s ease-in-out;
    }

    .project-card h3 {
      margin-top: 0;
      color: var(--accent);
    }

    @keyframes fadein {
      from {
        opacity: 0;
        transform: translateY(10px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="center">
      <img class="avatar" src="https://avatars.githubusercontent.com/u/194782918?s=400&u=d200dc6af93ee53ae1e550ee903b0b9a01284af3&v=4" alt="avatar" />
      <h1>namm</h1>
      <p>13 years old ・ 1m61 ・ 54kg</p>
      <p>full-time developer (but i hate java 😤)</p>
    </div>

    <div class="card">
      <h2>about me</h2>
      <p>i like modding phones, linux, and windows. i code in python, html, css, js, powershell, shell, batch, and more.</p>
      <p>i enjoy playing roblox, osu!, minecraft, and listening to music. i love cats and strawberry-flavored sweets.</p>
      <p>i'm shy about my voice and face 😣. don’t tease me when i’m coding 💢</p>
    </div>

    <div class="card">
      <h2>skills</h2>
      <div class="badge">Python</div>
      <div class="badge">C++</div>
      <div class="badge">HTML</div>
      <div class="badge">CSS</div>
      <div class="badge">JS</div>
      <div class="badge">Powershell</div>
      <div class="badge">Batch</div>
      <div class="badge">Shell</div>
      <div class="badge">TWRP Edify</div>
      <div class="badge">SQLite</div>
      <div class="badge">Android Modding</div>
      <div class="badge">Linux Expert</div>
      <div class="badge">Windows Modder</div>
    </div>

    <div class="card">
      <h2>currently learning</h2>
      <p>Python, HTML, CSS, JS, Powershell, Batch, TWRP Edify</p>
    </div>

    <div class="card">
      <h2>projects</h2>
      <div class="project-card">
        <h3><a href="https://nammisadev.github.io/OptimizedToolsPlusPlus/" target="_blank">OptimizedToolsPlusPlus</a></h3>
        <p>a lightweight collection of portable windows tools packed with speed-focused utilities.</p>
      </div>
      <div class="project-card">
        <h3><a href="https://nammisadev.github.io/microG-Installer/" target="_blank">microG Installer</a></h3>
        <p>flashable zip installer for microG setup with edify script and advanced compatibility.</p>
      </div>
      <div class="project-card">
        <h3><a href="https://github.com/NammIsADev/glautude" target="_blank">glautude</a></h3>
        <p>cli-based youtube player with yt-dlp and conplayer/mpv, portable and colorful interface.</p>
      </div>
      <div class="project-card">
        <h3><a href="https://nammisadev.github.io/hupe/" target="_blank">hupe</a></h3>
        <p>my own IT services.</p>
      </div>
      <div class="project-card">
        <h3><a href="https://fireOS.my.canva.site" target="_blank">fireOS</a></h3>
        <p>OS that based on Windows/Linux, aimed for maximum privacy and performance.</p>
      </div>
    </div>

    <div class="card">
      <h2>socials</h2>
      <div class="socials">
        <a href="https://www.roblox.com/users/2935364619/profile" target="_blank"></i>roblox</a>
        <a href="https://www.facebook.com/namnee6/" target="_blank"><i class="fab fa-facebook"></i>facebook</a>
        <a href="https://zalo.me/0931981731" target="_blank"><i class="fas fa-comment-dots"></i>zalo</a>
        <a href="https://www.youtube.com/@bnamm12" target="_blank"><i class="fab fa-youtube"></i>youtube</a>
        <a href="https://steamcommunity.com/id/bnamnee" target="_blank"><i class="fab fa-steam"></i>steam</a>
        <a href="https://atoka.pw/u/3550" target="_blank"><i class="fas fa-link"></i>atoka</a>
        <a href="https://github.com/NammIsADev" target="_blank"><i class="fab fa-github"></i>github</a>
        <a href="https://www.xbox.com/play/user?gamertag=RIPNamNe" target="_blank"><i class="fab fa-xbox"></i>xbox</a>
        <a href="https://www.tiktok.com/@_.techphone_" target="_blank"><i class="fab fa-tiktok"></i>tiktok</a>
        <a href="https://discord.com/users/1184676055462715453" target="_blank"><i class="fab fa-discord"></i>discord</a>
      </div>
    </div>

    <div class="card">
      <h2>contact</h2>
      <p>email: <a href="mailto:namb20994@gmail.com">namb20994@gmail.com</a></p>
    </div>

    <div class="card">
      <h2>fun fact</h2>
      <p>i slep vezy muck 💤</p>
    </div>
  </div>
</body>
</html>
