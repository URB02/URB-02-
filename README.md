# URB-02-<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>URB'02 Streetwear</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Roboto&display=swap');

  body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    background: #121212;
    color: #eee;
  }

  header {
    background: #000;
    padding: 1rem 2rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .logo {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    font-size: 2rem;
    color: #e63946;
    letter-spacing: 2px;
  }

  nav a {
    color: #eee;
    text-decoration: none;
    margin-left: 2rem;
    font-weight: 600;
    transition: color 0.3s ease;
  }

  nav a:hover {
    color: #e63946;
  }

  main {
    padding: 2rem;
    max-width: 1200px;
    margin: 0 auto;
  }

  h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 3rem;
    margin-bottom: 1rem;
    color: #e63946;
    text-align: center;
  }

  .products {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap: 2rem;
  }

  .product-card {
    background: #222;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 0 10px rgba(230,57,70,0.6);
    transition: transform 0.3s ease;
  }

  .product-card:hover {
    transform: scale(1.05);
  }

  .product-image {
    width: 100%;
    height: 250px;
    object-fit: cover;
  }

  .product-info {
    padding: 1rem;
  }

  .product-name {
    font-weight: 700;
    font-size: 1.2rem;
    margin-bottom: 0.5rem;
    color: #e63946;
  }

  .product-price {
    font-weight: 600;
    color: #aaa;
  }

  footer {
    background: #000;
    color: #555;
    text-align: center;
    padding: 1rem 0;
    margin-top: 3rem;
    font-size: 0.9rem;
  }
</style>
</head>
<body>

<header>
  <div class="logo">URB'02</div>
  <nav>
    <a href="#">Home</a>
    <a href="#">Coleção</a>
    <a href="#">Sobre</a>
    <a href="#">Contato</a>
  </nav>
</header>

<main>
  <h1>Streetwear que define estilo</h1>

  <section class="products">
    <div class="product-card">
      <img class="product-image" src="https://images.unsplash.com/photo-1521334884684-d80222895322?auto=format&fit=crop&w=400&q=80" alt="Camiseta URB'02 Preta" />
      <div class="product-info">
        <div class="product-name">Camiseta URB'02 Preta</div>
        <div class="product-price">R$ 79,90</div>
      </div>
    </div>

    <div class="product-card">
      <img class="product-image" src="https://images.unsplash.com/photo-1503341455253-b2e723bb3dbb?auto=format&fit=crop&w=400&q=80" alt="Moletom URB'02 Vermelho" />
      <div class="product-info">
        <div class="product-name">Moletom URB'02 Vermelho</div>
        <div class="product-price">R$ 199,90</div>
      </div>
    </div>

    <div class="product-card">
      <img class="product-image" src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246?auto=format&fit=crop&w=400&q=80" alt="Boné URB'02" />
      <div class="product-info">
        <div class="product-name">Boné URB'02</div>
        <div class="product-price">R$ 59,90</div>
      </div>
    </div>

    <div class="product-card">
      <img class="product-image" src="https://images.unsplash.com/photo-1520975694226-cd6ff8f35d50?auto=format&fit=crop&w=400&q=80" alt="Jaqueta URB'02" />
      <div class="product-info">
        <div class="product-name">Jaqueta URB'02</div>
        <div class="product-price">R$ 299,90</div>
      </div>
    </div>
  </section>
</main>

<footer>
  &copy; 2025 URB'02 Streetwear. Todos os direitos reservados.
</footer>

</body>
</html>