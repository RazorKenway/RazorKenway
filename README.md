<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
    }
    .hero-section {
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(135deg, #1f6feb 0%, #388bfd 100%);
      border-radius: 12px;
      margin-bottom: 30px;
    }
    .hero-section h1 {
      font-size: 2.5rem;
      font-weight: bold;
      color: white;
      margin-bottom: 20px;
    }
    .hero-section img {
      max-width: 100%;
      height: auto;
      border-radius: 12px;
    }
    .badge-group {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 12px;
      margin: 20px 0;
    }
    .about-section {
      background: #161b22;
      padding: 30px;
      border-radius: 12px;
      margin: 30px 0;
      border-left: 4px solid #1f6feb;
    }
    .about-section h2 {
      text-align: center;
      color: #79c0ff;
      margin-bottom: 25px;
      font-weight: bold;
    }
    .about-content {
      display: flex;
      align-items: center;
      gap: 30px;
    }
    .about-text ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    .about-text li {
      margin: 10px 0;
      font-size: 1.1rem;
      color: #c9d1d9;
    }
    .about-image {
      text-align: center;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .about-image img {
      max-width: 100%;
      height: auto;
    }
    .stats-section {
      background: #161b22;
      padding: 30px;
      border-radius: 12px;
      margin: 30px 0;
      border-top: 4px solid #1f6feb;
    }
    .stats-section h2 {
      text-align: center;
      color: #79c0ff;
      margin-bottom: 25px;
      font-weight: bold;
    }
    .tools-section {
      background: #161b22;
      padding: 30px;
      border-radius: 12px;
      margin: 30px 0;
      text-align: center;
      border-left: 4px solid #1f6feb;
    }
    .tools-section h2 {
      color: #79c0ff;
      margin-bottom: 25px;
      font-weight: bold;
    }
    .tools-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .tools-grid img {
      width: 70px;
      height: auto;
      transition: transform 0.3s;
    }
    .tools-grid img:hover {
      transform: scale(1.1);
    }
    .projects-section {
      background: #161b22;
      padding: 30px;
      border-radius: 12px;
      margin: 30px 0;
      border-top: 4px solid #1f6feb;
    }
    .projects-section h2 {
      text-align: center;
      color: #79c0ff;
      margin-bottom: 25px;
      font-weight: bold;
    }
    .project-card {
      background: #0d1117;
      border: 1px solid #30363d;
      border-radius: 8px;
      padding: 15px;
      transition: all 0.3s;
      margin-bottom: 20px;
    }
    .project-card:hover {
      transform: translateY(-5px);
      border-color: #1f6feb;
      box-shadow: 0 8px 16px rgba(31, 111, 235, 0.2);
    }
    .footer-section {
      text-align: center;
      padding: 30px 20px;
      background: #161b22;
      border-radius: 12px;
      margin: 30px 0;
    }
    .social-icons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px 0;
    }
    .social-icons a {
      display: inline-block;
      transition: transform 0.3s;
    }
    .social-icons a:hover {
      transform: scale(1.2) rotate(5deg);
    }
    .social-icons img {
      width: 32px;
      height: 32px;
      filter: brightness(0) invert(1);
    }
    @media (max-width: 768px) {
      .about-content {
        flex-direction: column;
      }
      .hero-section h1 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>

<div class="container py-5">

  <!-- Hero Section -->
  <div class="hero-section mb-5">
    <h1>👋 Razor Kenway - SL Android (Sri Lanka 🇱🇰) <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Earth.gif" height="28px" width="28px" alt="Earth"></h1>
    <img src="https://github.com/RazorKenway/RazorKenway/blob/main/SL_Android.jpg" width="80%" alt="SL Android" class="mt-3">
  </div>

  <!-- Social Badges -->
  <div class="badge-group mb-4">
    <a href="https://www.youtube.com/c/SLAndroid">
      <img title="YouTube" src="https://img.shields.io/badge/YouTube-SL Android-red?style=for-the-badge&logo=YouTube">
    </a>
    <a href="https://t.me/joinchat/AAAAAFHmxm72d-lboeaueg">
      <img title="Telegram Channel" src="https://img.shields.io/badge/Telegram-Channel-blue?style=for-the-badge&logo=Telegram">
    </a>
    <a href="https://t.me/joinchat/MaJux1c8gdMW2GSqCpEBxQ">
      <img title="Telegram Group" src="https://img.shields.io/badge/Telegram-Group-blue?style=for-the-badge&logo=Telegram">
    </a>
    <a href="https://www.facebook.com/groups/277920623081269/?ref=share">
      <img title="Facebook Group" src="https://img.shields.io/badge/Facebook-Group-1877F2?style=for-the-badge&logo=Facebook">
    </a>
    <a href="https://www.facebook.com/SLAndroidD/">
      <img title="Facebook Page" src="https://img.shields.io/badge/Facebook-Page-black?style=for-the-badge&logo=Facebook">
    </a>
  </div>

  <!-- GitHub & Instagram Badges -->
  <div class="badge-group mb-5">
    <a href="https://github.com/RazorKenway">
      <img src="https://img.shields.io/badge/GitHub-RazorKenway-000?style=flat&logo=GitHub">
    </a>
    <a href="https://www.instagram.com/sl_android_official/">
      <img src="https://img.shields.io/badge/Instagram-sl_android_official-c13584?style=flat&logo=Instagram">
    </a>
  </div>

  <!-- About Me Section -->
  <div class="about-section">
    <h2>👨🏽‍💻 About Me</h2>
    <div class="about-content">
      <div class="about-text col-lg-6">
        <ul>
          <li>💻 <strong>I'm Razor Kenway</strong></li>
          <li>🌱 Currently learning Python, Shell, HTML, PHP, Java, JS, CSS, C++</li>
          <li>🤝 Looking to collaborate with <a href="https://t.me/SL_Android" style="color: #79c0ff;">SL Android</a></li>
          <li>🎥 Check out my tutorials: <a href="https://www.youtube.com/c/SLAndroid" style="color: #79c0ff;">YouTube - SL Android</a></li>
          <li>🧠 Always exploring new coding methods</li>
          <li>💬 Ask me anything</li>
          <li>🎓 Still a student</li>
          <li>📧 Email: <strong>service.slandro.official@gmail.com</strong></li>
        </ul>
      </div>
      <div class="about-image col-lg-6">
        <img src="https://github.com/RazorKenway/RazorKenway/blob/main/Developer.gif" width="55%" alt="Developer">
      </div>
    </div>
  </div>

  <!-- GitHub Stats Section -->
  <div class="stats-section">
    <h2>📊 GitHub Stats</h2>
    <div class="row">
      <div class="col-lg-6 mb-3 mb-lg-0">
        <img src="https://github-readme-stats.vercel.app/api?username=RazorKenway&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=151515" alt="GitHub Stats" class="img-fluid">
      </div>
      <div class="col-lg-6">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RazorKenway&layout=compact" alt="Top Languages" class="img-fluid">
      </div>
    </div>
  </div>

  <!-- Languages & Tools Section -->
  <div class="tools-section">
    <h2>💻 Languages & Tools</h2>
    <div class="tools-grid">
      <img src="https://www.vectorlogo.zone/logos/python/python-ar21.svg" alt="Python" title="Python">
      <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-official.svg" alt="Bash" title="Bash">
      <img src="https://www.vectorlogo.zone/logos/netlifyapp_watercss/netlifyapp_watercss-official.svg" alt="CSS" title="CSS">
      <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg" alt="Git" title="Git">
      <img src="https://www.vectorlogo.zone/logos/php/php-vertical.svg" alt="PHP" title="PHP">
      <img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-ar21.svg" alt="HTML5" title="HTML5">
      <img src="https://www.vectorlogo.zone/logos/mysql/mysql-ar21.svg" alt="MySQL" title="MySQL">
      <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-ar21.svg" alt="SQLite" title="SQLite">
      <img src="https://www.vectorlogo.zone/logos/firebase/firebase-ar21.svg" alt="Firebase" title="Firebase">
      <img src="https://www.vectorlogo.zone/logos/json/json-ar21.svg" alt="JSON" title="JSON">
      <img src="https://www.vectorlogo.zone/logos/github/github-ar21.svg" alt="GitHub" title="GitHub">
      <img src="https://www.vectorlogo.zone/logos/gitlab/gitlab-ar21.svg" alt="GitLab" title="GitLab">
    </div>
  </div>

  <!-- Featured Projects Section -->
  <div class="projects-section">
    <h2>🔥 Featured Projects</h2>
    <div class="row">
      <div class="col-lg-6">
        <div class="project-card">
          <a href="https://github.com/RazorKenway/GalleryHack">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=RazorKenway&repo=GalleryHack&theme=radical" alt="GalleryHack" class="img-fluid">
          </a>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="project-card">
          <a href="https://github.com/RazorKenway/Unlocker">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=RazorKenway&repo=Unlocker&theme=highcontrast" alt="Unlocker" class="img-fluid">
          </a>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="project-card">
          <a href="https://github.com/RazorKenway/EvilEye-Banner">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=RazorKenway&repo=EvilEye-Banner&theme=vision-friendly-dark" alt="EvilEye-Banner" class="img-fluid">
          </a>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="project-card">
          <a href="https://github.com/RazorKenway/Hide-In-Picture">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=RazorKenway&repo=Hide-In-Picture&theme=highcontrast" alt="Hide-In-Picture" class="img-fluid">
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer Section -->
  <div class="footer-section">
    <img src="https://i.pinimg.com/originals/57/dd/7b/57dd7be982ce9049be3dc1ddacc100cb.gif" width="30%" alt="Footer Decoration" class="mb-4">
    <h2 style="color: #79c0ff; margin-bottom: 20px;">🌐 Connect with Me</h2>
    <div class="social-icons">
      <a href="https://github.com/RazorKenway" title="GitHub">
        <img alt="GitHub" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
      </a>
      <a href="https://t.me/Razor_Kenway" title="Telegram">
        <img alt="Telegram" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/telegram.svg" />
      </a>
      <a href="https://www.instagram.com/sl_android_official/" title="Instagram">
        <img alt="Instagram" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
      </a>
      <a href="https://www.facebook.com/groups/277920623081269/?ref=share" title="Facebook">
        <img alt="Facebook" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/facebook.svg" />
      </a>
    </div>
    <p style="margin-top: 20px; font-size: 1.1rem; color: #79c0ff;">
      ⭐ If you find my work helpful, please consider giving it a star! ⭐
    </p>
  </div>

</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
