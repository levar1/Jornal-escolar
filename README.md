<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Jornal Escolar Mário Braga - Edição 6º TD 2025</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f7f8;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #004080;
      color: white;
      padding: 20px 30px;
      text-align: center;
      box-shadow: 0 3px 6px rgba(0,0,0,0.2);
      position: sticky;
      top: 0;
      z-index: 100;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      letter-spacing: 1.5px;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #cce4ff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffffff;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px 40px 20px;
    }
    .news-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      margin-bottom: 30px;
      overflow: hidden;
      transition: transform 0.3s;
    }
    .news-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }
    .news-image {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    .news-content {
      padding: 20px 25px;
    }
    .news-content h2 {
      margin-top: 0;
      color: #004080;
      font-size: 1.8rem;
    }
    .news-content p {
      line-height: 1.6;
      font-size: 1.1rem;
      margin-bottom: 15px;
    }
    .news-content img.inline-image {
      float: right;
      width: 200px;
      height: 120px;
      object-fit: cover;
      margin-left: 15px;
      margin-bottom: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .news-meta {
      font-size: 0.9rem;
      color: #666;
      font-style: italic;
      margin-top: 10px;
    }
    footer {
      text-align: center;
      padding: 15px 10px;
      font-size: 0.9rem;
      color: #777;
      background-color: #e1e8f0;
      border-top: 1px solid #ccc;
      margin-top: 40px;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.5rem;
      }
      nav a {
        margin: 0 8px;
        font-size: 0.9rem;
      }
      .news-content h2 {
        font-size: 1.4rem;
      }
      .news-content p {
        font-size: 1rem;
      }
      .news-content img.inline-image {
        float: none;
        display: block;
        margin: 15px auto;
        width: 90%;
        height: auto;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Jornal Escolar Mário Braga</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Notícias</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <main>
    <article class="news-card">
      <img
        class="news-image"
        src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=900&q=80"
        alt="Alunos jogando futebol"
      />
      <div class="news-content">
        <h2>⚽ Interclasse no Colégio Mário Braga: emoção, garra e muita energia em campo!</h2>
        <p>
          Foi o pedido dos próprios alunos do Colégio Mário Braga que colocou fogo no jogo! Cheios de entusiasmo, eles pediram aos professores que organizassem o tão esperado interclasse, e em 2022/2023, a escola atendeu com muita animação.
        </p>
        <p>
          <img
            src="https://images.unsplash.com/photo-1553979459-3f6ecf49b3b8?auto=format&fit=crop&w=400&q=80"
            alt="Time de futebol juvenil"
            class="inline-image"
          />
          O interclasse reúne competições esportivas que vão muito além do futebol e do vôlei, incluindo também basquete, handebol e atletismo — cinco modalidades que colocam à prova o talento e a força dos nossos alunos, além de criar um espetáculo de torcida, rivalidade saudável e muita diversão.
        </p>
        <p>
          A cada lance, a cada gol e cada ponto disputado, o clima de competição cresce, mostrando o verdadeiro espírito esportivo que move nossa escola. A união entre turmas, o incentivo à prática esportiva e a alegria contagiante tomaram conta do colégio, deixando todos ansiosos pela próxima edição!
        </p>
        <p class="news-meta">
          📌 Turma: 6º TD &nbsp;&nbsp;|&nbsp;&nbsp; 🧠 Autor: Ravel &nbsp;&nbsp;|&nbsp;&nbsp; 📅 Ano: 2025
        </p>
      </div>
    </article>
  </main>

  <footer>
    <p>© 2025 Jornal Escolar Mário Braga. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
