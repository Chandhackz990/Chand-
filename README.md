<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Chand_hackz — Frontend Developer</title>

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;700&family=Inter:wght@300;500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />

  <style>
    :root{
      --bg:#fbfbfb;
      --card:#ffffff;
      --muted:#8d8d8d;
      --accent:#2b2b2b;
      --pill:#f6f6f6;
      --shadow:0 10px 30px rgba(11,11,11,0.06);
    }
    [data-theme="dark"]{
      --bg:#0b0b0c;
      --card:#0f1113;
      --muted:#9aa0a6;
      --accent:#f5f5f5;
      --pill:#111214;
      --shadow:0 8px 20px rgba(0,0,0,0.6);
    }
    body{
      margin:0; font-family:Inter,system-ui; background:var(--bg); color:var(--accent);
    }
    .container{max-width:920px;margin:0 auto;padding:26px 18px;}
    .hero{text-align:center;margin-top:8px;}
    .hero h1{font-family:"Merriweather",serif;font-weight:700;font-size:22px;}
    .hero span.title-sub{display:block;font-weight:600;font-size:15px;color:var(--muted)}
    .top-nav{display:flex;justify-content:center;gap:18px;margin:10px 0;}
    .nav-link{text-decoration:none;font-weight:700;color:var(--accent)}
    .avatar{width:220px;height:300px;border-radius:12px;overflow:hidden;display:block;margin:0 auto;box-shadow:var(--shadow);}
    .avatar img{width:100%;height:100%;object-fit:cover;}
    .socials{margin-top:10px;display:flex;justify-content:center;gap:14px;font-size:22px;}
    .socials a{color:var(--accent);}
    .bio,.contact{background:var(--card);padding:16px;border-radius:12px;box-shadow:var(--shadow);margin:14px 0;}
    .section-head{font-family:"Merriweather",serif;font-weight:700;margin-bottom:8px;}
    .skills-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:18px;}
    .skill{background:var(--card);border-radius:18px;padding:14px;text-align:center;box-shadow:var(--shadow);}
    .skill .icon{font-size:26px;color:var(--muted);margin-bottom:6px;}
    .bottom-pill{position:fixed;left:50%;transform:translateX(-50%);bottom:20px;width:min(860px,94%);background:var(--card);border-radius:40px;padding:12px 18px;box-shadow:var(--shadow);display:flex;align-items:center;justify-content:space-between;}
  </style>
</head>
<body>
  <div class="container">
    <header id="home" class="hero">
      <h1><strong>Hi, I'm CHAND_HACKZ</strong><br><span class="title-sub">Frontend Developer</span></h1>
    </header>

    <nav class="top-nav">
      <a href="#home" class="nav-link">𝐇𝐎𝐌𝐄</a>
      <a href="#skills" class="nav-link">𝐒𝐊𝐈𝐋𝐋𝐒</a>
      <a href="#projects" class="nav-link">𝐏𝐑𝐎𝐉𝐄𝐂𝐓𝐒</a>
      <a href="https://t.me/chand_hackz" target="_blank" class="nav-link">Telegram</a>
    </nav>

    <div class="avatar">
      <img src="assets/avatar.jpg" alt="Chand_hackz">
    </div>

    <div class="socials">
      <a href="https://t.me/chand_hackz" target="_blank" title="Telegram"><i class="fab fa-telegram-plane"></i></a>
      <a href="#" title="YouTube"><i class="fab fa-youtube"></i></a>
      <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
    </div>

    <section class="bio">
      <div class="section-head">BIOGRAPHY</div>
      <p>I'm <strong>CHAND_HACKZ</strong> — a frontend developer blending creativity with code to build engaging, immersive web experiences.</p>
    </section>

    <section class="contact">
      <div class="section-head">CONTACT</div>
      <p>India<br>sarfarazaalam762@gmail.com</p>
      <form action="https://formspree.io/f/yourFormID" method="POST">
        <label>Name</label><br><input type="text" name="name" required><br>
        <label>Email</label><br><input type="email" name="email" required><br>
        <label>Message</label><br><textarea name="message" rows="4" required></textarea><br>
        <button type="submit">Send</button>
      </form>
    </section>

    <section id="skills">
      <div class="section-head">Skills & Experience</div>
      <div class="skills-grid">
        <div class="skill"><div class="icon"><i class="fa-solid fa-code"></i></div><h4>C</h4><p>Advanced</p></div>
        <div class="skill"><div class="icon"><i class="fa-solid fa-code"></i></div><h4>C++</h4><p>Advanced</p></div>
        <div class="skill"><div class="icon"><i class="fa-brands fa-java"></i></div><h4>Java</h4><p>Advanced</p></div>
        <div class="skill"><div class="icon"><i class="fa-brands fa-html5"></i></div><h4>HTML</h4><p>Advanced</p></div>
        <div class="skill"><div class="icon"><i class="fa-brands fa-css3-alt"></i></div><h4>CSS</h4><p>Advanced</p></div>
        <div class="skill"><div class="icon"><i class="fa-brands fa-python"></i></div><h4>Python</h4><p>Advanced</p></div>
        <div class="skill"><div class="icon"><i class="fa-solid fa-terminal"></i></div><h4>Kali Linux</h4><p>Advanced</p></div>
        <div class="skill"><div class="icon"><i class="fa-solid fa-network-wired"></i></div><h4>Metasploit</h4><p>Advanced</p></div>
        <div class="skill"><div class="icon"><i class="fa-solid fa-eye"></i></div><h4>Nmap</h4><p>Advanced</p></div>
      </div>
    </section>

    <section id="projects">
      <div class="section-head">PROJECTS</div>
      <p>Coming soon — showcase of projects will appear here.</p>
    </section>
  </div>

  <nav class="bottom-pill">
    <div style="display:flex;align-items:center;gap:10px;">
      <img src="assets/avatar.jpg" style="width:44px;height:44px;border-radius:50%;">
      <div>
        <b>Chand_hackz</b><br><span style="font-size:12px;color:gray">Frontend • Hacker</span>
      </div>
    </div>
    <div>
      <a href="https://t.me/chand_hackz" target="_blank" title="Telegram" style="font-size:18px;margin-right:10px;"><i class="fab fa-telegram-plane"></i></a>
      <button id="theme-toggle" style="font-size:18px;border:none;background:none;cursor:pointer;"><i class="fa-regular fa-moon"></i></button>
    </div>
  </nav>

  <script>
    // Theme toggle
    const btn = document.getElementById('theme-toggle');
    btn.addEventListener('click',()=>{
      document.documentElement.toggleAttribute('data-theme','dark');
    });
  </script>
</body>
</html>
