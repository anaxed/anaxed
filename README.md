<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portföy | Gelişmiş Tasarım</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background-color: #0f0f0f;
      color: #f0f0f0;
      line-height: 1.6;
    }

    header {
      background-color: #111;
      padding: 20px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.5);
    }

    header h1 {
      font-size: 28px;
      color: #f3cf04;
    }

    nav a {
      margin-left: 25px;
      color: #f0f0f0;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #f0b002;
    }

    section {
      padding: 60px 50px;
    }

    .hero {
      background: linear-gradient(135deg, #1f1f1f, #282c34);
      text-align: center;
      padding: 100px 20px;
    }

    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 18px;
      color: #aaa;
    }

    .about, .projects {
      max-width: 1000px;
      margin: auto;
    }

    .about h2, .projects h2 {
      font-size: 32px;
      margin-bottom: 20px;
      color: #fbff03;
    }

    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .project {
      background-color: #1e1e1e;
      padding: 20px;
      border-radius: 10px;
      transition: transform 0.3s;
    }

    .project:hover {
      transform: scale(1.05);
    }

    .project h3 {
      margin-bottom: 10px;
      color: #14a2da;
    }

    .project p {
      color: #07eafa;
    }

    footer {
      text-align: center;
      padding: 30px 0;
      background-color: #b775ec;
      color: #ffffff;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Muhammetin portföyü</h1>
    <nav>
      <a href="#about">Hakkımda</a>
      <a href="#projects">Projeler</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Merhaba, ben Muhammet ben bir Yazılım Geliştiricisiyim</h2>
    <p>Web geliştirme konusunda tutkuluyum .</p>
  </section>

  <section id="about" class="about">
    <h2>Hakkımda</h2>
    <p>Pyhton c/c++ html ve unity gibi araçlarla projeler geliştiriyorum. Yeni şeyler öğrenmeyi ve ekip çalışmasını severim.</p>
  </section>

  <section id="projects" class="projects">
    <h2>denediğim projeler</h2>
    <div class="project-grid">
      <div class="project">
        <h3>Proje 1</h3>
        <p>Pyhton kulanarak kulandığım siber güvenlik uygulamaları.</p>
      </div>
      <div class="project">
        <h3>Proje 2</h3>
        <p>geliştirdiğim oyunlar.</p>
      </div>
      <div class="project">
        <h3>Proje 3</h3>
        <p>geliştirdiğim web siteleri.</p>
      </div>
    </div>
  </section>

  <head>
      <div class="Hobilerim">
        <h4>Hobilerim</h4>
        <p>hobilerim oyun oynamak ve geliştirmek kod yazmak filim ve dizi izlemek gibi şeyler ve genelde odaklanarak yaptığım işler evde olur</p>
        <p>Ekibimiz (RespectCode)</p>
      

<head>
    <title>Document</title>
</head>
<body>
    <a href="https://discord.gg/ep4KdQeFwy">
    <img src="respect.png" width="250px"
    alt="respectCode"  title="RespectCode">

    <p>-RespectCode bilişim ve yazılım hakında aradığınız herşey demektir-</p>
</a>
</body>
</html>
      </div>
    </header>
  </head>
  <footer>
    &copy; 2025 Tüm hakları benimdir :).
  </footer>
</body>
</html>

</body>
</html>
