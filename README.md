!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ruhani Afroz</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    *{margin:0;padding:0;box-sizing:border-box}
    body{
      font-family:'Poppins',sans-serif;
      background:hsl(240, 92%, 56%);
      color:#fff;
      line-height:1.6;
    }
    header{
      text-align:center;
      padding:80px 20px;
      background:linear-gradient(135deg,#00f7ff,#8a2be2);
      color:#fff;
    }
    header h1{
      font-family:'Orbitron',sans-serif;
      font-size:3rem;
    }
    header p{margin-top:10px;font-size:1.2rem}
    section{padding:60px 20px;max-width:1000px;margin:auto}
    h2{color:#00f7ff;margin-bottom:20px}
    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:20px;
    }
    .card{
      background:hsl(240, 93%, 47%);
      padding:20px;
      border-radius:15px;
      box-shadow:0 0 15px rgba(0,247,255,0.2);
      transition:0.3s;
    }
    .card:hover{
      transform:translateY(-5px);
      box-shadow:0 0 25px rgba(0,247,255,0.5);
    }
    footer{
      text-align:center;
      padding:20px;
      border-top:1px solid hsl(248, 90%, 48%);
      color:#aaa;
    }
    a{color:#00f7ff;text-decoration:none}
  </style>
</head>
<body>

<header>
  <h1>🤖 Ruhani Afroz</h1>
  <p>AI Engineer | Python Developer | Django Specialist</p>
</header>

<section>
  <h2>👨‍💻 About Me</h2>
  <p>I am a Python developer and future AI engineer passionate about building intelligent systems, web apps, and data-driven solutions.</p>
</section>

<section>
  <h2>🚀 Projects</h2>
  <div class="cards">
    <div class="card">
      <h3>Django TODO App</h3>
      <p>Full CRUD web app using Django.</p>
    </div>
    <div class="card">
      <h3>Data Analysis</h3>
      <p>Data cleaning & visualization with Pandas.</p>
    </div>
    <div class="card">
      <h3>AI Task Manager</h3>
      <p>Upcoming AI-powered productivity tool.</p>
    </div>
  </div>
</section>

<section>
  <h2>🛠️ Skills</h2>
  <p>Python | Django | HTML | CSS | Git | Data Science</p>
</section>

<section>
  <h2>🌐 Connect</h2>
  <p>GitHub: <a href="#">afrozruhani@gmail.com</a></p>
  <p><Email:afrozruhani@gmail.com></p>
</section>

<footer>
  <p>⭐ Built by Ruhani Afroz</p>
</footer>

</body>
</html>
