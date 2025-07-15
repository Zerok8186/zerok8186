<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portafolio - Desarrollador Full Stack</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: #fff;
    }
    #header {
      text-align: center;
      padding: 40px 20px;
      background-image: url('https://media.giphy.com/media/3o7TKrWYW4R7jzk2Gs/giphy.gif');
      background-size: cover;
      background-position: center;
      animation: fadeIn 2s ease-in-out;
    }
    #header h1 {
      font-size: 2.5rem;
      color: #00ffc8;
      text-shadow: 2px 2px 10px black;
    }
    #header h3 {
      font-weight: normal;
    }
    .badge-container {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
      flex-wrap: wrap;
    }
    .badge-container img {
      transition: transform 0.3s;
    }
    .badge-container img:hover {
      transform: scale(1.1);
    }
    section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
      animation: fadeIn 2s ease-in-out;
    }
    h2 {
      color: #00ffc8;
      border-left: 5px solid #00ffc8;
      padding-left: 10px;
    }
    .tech-icons {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      padding-top: 15px;
    }
    .tech-icons img {
      width: 50px;
      height: 50px;
      transition: transform 0.3s;
    }
    .tech-icons img:hover {
      transform: rotate(15deg) scale(1.1);
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(20px);}
      to {opacity: 1; transform: translateY(0);}
    }
    .gif-divider {
      width: 100%;
      margin: 20px 0;
      text-align: center;
    }
    .gif-divider img {
      width: 100px;
    }
    footer {
      text-align: center;
      padding: 30px;
      background-color: #111;
      color: #999;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <div id="header">
    <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100" />
    <h1>Hola, soy Carlos Armando 👋</h1>
    <h3>Desarrollador Full-Stack con enfoque en soluciones robustas, IA, y nuevas tecnologías.</h3>
    <div class="badge-container">
      <a href="https://www.linkedin.com/in/tu-linkedin/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
      </a>
      <a href="https://twitter.com/tu-twitter" target="_blank">
        <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="Twitter" />
      </a>
      <a href="https://tu-portfolio.com" target="_blank">
        <img src="https://img.shields.io/badge/Mi%20Portfolio-DA5B0B?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
      </a>
      <a href="mailto:tu-email@example.com">
        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
      </a>
    </div>
  </div>

  <section>
    <h2>🧠 Sobre Mí</h2>
    <p>
      Soy un <strong>Desarrollador con experiencia en Python, C++, C#, JavaScript, Java, PHP</strong>, especializado en el desarrollo web <strong>Full-Stack</strong> y la administración de servidores <strong>Linux/Windows</strong>. He trabajado con bases de datos SQL y NoSQL, desarrollando APIs RESTful, gestionando infraestructura cloud en <strong>AWS y Azure</strong>, y aplicando <strong>Machine Learning</strong> para soluciones inteligentes.
    </p>
    <p>
      También me apasiona la integración de tecnologías emergentes como <strong>APIs de IA</strong> (OpenAI, Gemini, HuggingFace) en proyectos de automatización, chatbots, visión por computadora y asistentes virtuales.
    </p>
  </section>

  <div class="gif-divider">
    <img src="https://media.giphy.com/media/l3q2K5jinAlChoCLS/giphy.gif" alt="divider" />
  </div>

  <section>
    <h2>🛠️ Stack Tecnológico</h2>
    <div class="tech-icons">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angularjs/angularjs-original.svg" alt="Angular" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" alt="Vue" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original.svg" alt=".NET" />
      <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="Kubernetes" />
      <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="Tensorflow" />
      <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="PyTorch" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit-learn" />
    </div>
  </section>

  <section>
    <h2>📊 Estadísticas GitHub</h2>
    <div style="text-align: center">
      <img src="https://github-readme-stats.vercel.app/api?username=TU_USUARIO&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="GitHub Stats" />
      <br />
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TU_USUARIO&layout=compact&langs_count=8&theme=tokyonight" alt="Top Langs" />
    </div>
  </section>

  <footer>
    <p>Diseñado con ❤️ por Carlos Armando - Desarrollador Full Stack | IA | DevOps | Cloud</p>
  </footer>

</body>
</html>
