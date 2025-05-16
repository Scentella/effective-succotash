# effective-succotash<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Scentella - Perfumes Artesanais</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #fff;
      color: #222;
    }
    header {
      background: #000;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    header p {
      margin-top: 0.5rem;
      font-style: italic;
    }
    .banner {
      background: url('https://source.unsplash.com/1600x500/?perfume') no-repeat center/cover;
      height: 300px;
    }
    .container {
      padding: 2rem;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .produto {
      border: 1px solid #ddd;
      border-radius: 12px;
      overflow: hidden;
      transition: 0.3s;
    }
    .produto:hover {
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
    .produto img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    .produto-info {
      padding: 1rem;
    }
    .produto-info h3 {
      margin: 0.5rem 0;
    }
    .produto-info p {
      font-size: 0.9rem;
      color: #555;
    }
    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Scentella</h1>
    <p>Contratipos de perfumes importados, feitos artesanalmente. Para quem gosta de produtos de qualidade com preço justo.</p>
  </header>  <div class="banner"></div>  <div class="container">
    <h2>Perfumes em Destaque</h2>
    <div class="produtos">
      <div class="produto">
        <img src="https://source.unsplash.com/300x300/?perfume,bottle" alt="Perfume 1" />
        <div class="produto-info">
          <h3>Inspiração: Sauvage</h3>
          <p>Notas amadeiradas e frescas para homens marcantes.</p>
        </div>
      </div>
      <div class="produto">
        <img src="https://source.unsplash.com/300x300/?perfume,luxury" alt="Perfume 2" />
        <div class="produto-info">
          <h3>Inspiração: La Vie Est Belle</h3>
          <p>Um floral doce e sofisticado para mulheres intensas.</p>
        </div>
      </div>
      <div class="produto">
        <img src="https://source.unsplash.com/300x300/?perfume,glass" alt="Perfume 3" />
        <div class="produto-info">
          <h3>Inspiração: One Million</h3>
          <p>Fragrância ousada, com notas especiadas e sensuais.</p>
        </div>
      </div>
    </div>
  </div>  <footer>
    &copy; 2025 Scentella. Todos os direitos reservados.
  </footer>
</body>
</html>
