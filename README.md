<!-- ================= GLOBAL CSS (GitHub-safe) ================= -->
<svg width="0" height="0">
  <style>
    :root {
      --bg-main:#0d1117;
      --bg-soft:#161b22;
      --accent:#58a6ff;
      --accent-2:#7ee787;
      --text-main:#c9d1d9;
      --text-soft:#8b949e;
    }

    @keyframes fadeUp {
      from { opacity:0; transform:translateY(20px); }
      to { opacity:1; transform:translateY(0); }
    }

    @keyframes float {
      0%,100% { transform:translateY(0); }
      50% { transform:translateY(-10px); }
    }

    @keyframes glow {
      0% { box-shadow:0 0 10px var(--accent); }
      50% { box-shadow:0 0 25px var(--accent); }
      100% { box-shadow:0 0 10px var(--accent); }
    }

    .card {
      background:var(--bg-soft);
      border-radius:18px;
      padding:30px;
      margin:50px auto;
      max-width:900px;
      animation:fadeUp 1.2s ease;
    }

    .title {
      color:var(--accent);
      font-size:2em;
      margin-bottom:15px;
    }

    .text {
      color:var(--text-main);
      font-size:1.05em;
      line-height:1.7;
    }

    .muted {
      color:var(--text-soft);
    }

    .center { text-align:center; }
  </style>
</svg>

<!-- ================= WELCOME ================= -->
<div class="card center" style="background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);">
  <h1 style="color:white;font-size:3em;">Welcome 👋</h1>
  <img src="https://media.giphy.com/media/h408T6Y5GfmXBKW62l/giphy.gif"
       width="200"
       style="margin-top:20px;animation:float 4s infinite;">
</div>

<!-- ================= ABOUT ================= -->
<div class="card">
  <h2 class="title">About Me</h2>
  <p class="text">I’m <b>Ahmad</b>, a 21-year-old Information Technology student.</p>

  <p class="muted">
    <b>EmberRenewed</b> means a spark that didn’t fade — it returned stronger.<br>
    Resilience. Growth. Rebuilding after challenges.
  </p>

  <p class="text">Always learning. Always improving.</p>

  <div class="center">
    <img src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif"
         width="400"
         style="margin-top:20px;">
  </div>
</div>

<!-- ================= SOCIALS ================= -->
<div class="card center">
  <h2 class="title">🌐 Socials</h2>

  <a href="https://discord.gg/830733842624020500">
    <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white">
  </a>

  <a href="https://instagram.com/emberrenewed">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
  </a>

  <a href="https://youtube.com/@brokurdish">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
  </a>

  <a href="https://t.me/emberrenewed">
    <img src="https://media.giphy.com/media/ya4eevXU490Iw/giphy.gif"
         width="42"
         style="vertical-align:middle;">
  </a>
</div>

<!-- ================= TECH STACK ================= -->
<div class="card">
  <h2 class="title">💻 Tech Stack</h2>

  <p class="center">
    <!-- badges unchanged -->
    ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
    ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
    ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
    ![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
    ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
  </p>
</div>

<!-- ================= STATS ================= -->
<div class="card center">
  <h2 class="title">📊 GitHub Stats</h2>

  <img src="https://github-readme-stats.vercel.app/api?username=emberrenewed&theme=monokai"
       style="animation:glow 4s infinite;"><br><br>

  <img src="https://nirzak-streak-stats.vercel.app/?user=emberrenewed&theme=monokai"><br><br>

  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=emberrenewed&layout=compact&theme=monokai">
</div>

<!-- ================= FOOTER ================= -->
<div class="center muted" style="margin:40px 0;">
  Built slow. Built right. Built to last 🔥
</div>
