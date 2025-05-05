<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>L'imper + | Limpeza e Impermeabilização Profissional</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0; padding: 0;
    background: #f9f9f9;
    color: #333;
  }
  header {
    background: #0077cc;
    color: white;
    padding: 20px;
    text-align: center;
  }
  header h1 {
    margin: 0;
    font-weight: 700;
  }
  nav {
    background: #005fa3;
    display: flex;
    justify-content: center;
    gap: 30px;
    padding: 15px 0;
    flex-wrap: wrap;
  }
  nav a {
    color: white;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1rem;
  }
  nav a:hover {
    text-decoration: underline;
  }
  .hero {
    background: url('https://images.unsplash.com/photo-1581091012184-9b7e4b6a5e2e?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    text-shadow: 2px 2px 8px rgba(0,0,0,0.7);
    flex-direction: column;
    padding: 0 20px;
    text-align: center;
  }
  .hero h2 {
    font-size: 2.8rem;
    margin-bottom: 15px;
  }
  .hero p {
    font-size: 1.2rem;
    max-width: 600px;
    margin-bottom: 25px;
  }
  .btn-contact {
    background: #ff6600;
    color: white;
    padding: 15px 30px;
    font-weight: 700;
    border: none;
    border-radius: 30px;
    cursor: pointer;
    font-size: 1.1rem;
    transition: background 0.3s ease;
    text-decoration: none;
  }
  .btn-contact:hover {
    background: #e65500;
  }
  main {
    max-width: 1100px;
    margin: 40px auto;
    padding: 0 20px;
  }
  section {
    margin-bottom: 60px;
  }
  h3 {
    color: #0077cc;
    margin-bottom: 20px;
    font-weight: 700;
    border-bottom: 3px solid #0077cc;
    display: inline-block;
    padding-bottom: 5px;
  }
  .services {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: space-between;
  }
  .service-card {
    background: white;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    border-radius: 12px;
    flex: 1 1 300px;
    padding: 20px;
    transition: transform 0.3s ease;
  }
  .service-card:hover {
    transform: translateY(-8px);
  }
  .service-card img {
    width: 100%;
    border-radius: 12px;
    margin-bottom: 15px;
  }
  .service-card h4 {
    margin-top: 0;
    margin-bottom: 10px;
    color: #005fa3;
  }
  .gallery {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
    justify-content: center;
  }
  .gallery img {
    width: 300px;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  .gallery img:hover {
    transform: scale(1.05);
  }
  .testimonials {
    background: #e6f0fa;
    padding: 30px;
    border-radius: 12px;
  }
  .testimonial {
    margin-bottom: 20px;
  }
  .testimonial p {
    font-style: italic;
  }
  .testimonial strong {
    display: block;
    margin-top: 8px;
    color: #0077cc;
  }
  form {
    max-width: 500px;
    background: white;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }
  form label {
    display: block;
    margin-bottom: 6px;
    font-weight: 600;
  }
  form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 1rem;
    resize: vertical;
  }
  form button {
    background: #0077cc;
    color: white;
    border: none;
    padding: 12px 25px;
    font-size: 1rem;
    border-radius: 30px;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  form button:hover {
    background: #005fa3;
  }
  footer {
    background: #222;
    color: #ccc;
    text-align: center;
    padding: 20px;
  }
  @media(max-width: 768px) {
    .services {
      flex-direction: column;
    }
    .gallery img {
      width: 100%;
      max-width: 350px;
    }
  }
</style>
</head>
<body>
<header>
  <h1>L'imper +</h1>
</header>
<nav>
  <a href="#sobre">Sobre</a>
  <a href="#servicos">Serviços</a>
  <a href="#galeria">Galeria</a>
  <a href="#depoimentos">Depoimentos</a>
  <a href="#contato">Contato</a>
</nav>
<section class="hero">
  <h2>Limpeza e Impermeabilização Profissional</h2>
  <p>Proteja e renove seus estofados com tecnologia de ponta e produtos biodegradáveis.</p>
  <a href="#contato" class="btn-contact">Solicite um Orçamento</a>
</section>
<main>
  <section id="sobre">
    <h3>Sobre Nós</h3>
    <p>Desde 2018, a L'imper + oferece serviços especializados em limpeza e impermeabilização de estofados, cortinas, tapetes e carpetes. Utilizamos nanotecnologia e produtos certificados para garantir a máxima proteção e durabilidade, sempre com respeito ao meio ambiente.</p>
  </section>
  <section id="servicos">
    <h3>Serviços</h3>
    <div class="services">
      <div class="service-card">
        <img src="https://images.unsplash.com/photo-1581579180386-1a0a4e1e9c2b?auto=format&fit=crop&w=600&q=80" alt="Limpeza de Estofados" />
        <h4>Limpeza de Estofados</h4>
        <p>Remoção profunda de sujeiras, manchas e odores, restaurando a aparência original dos seus móveis.</p>
      </div>
      <div class="service-card">
        <img src="https://images.unsplash.com/photo-1590080877777-0a1a8f1a6e8f?auto=format&fit=crop&w=600&q=80" alt="Impermeabilização" />
        <h4>Impermeabilização</h4>
        <p>Proteção duradoura contra líquidos e manchas, aumentando a vida útil dos seus estofados.</p>
      </div>
      <div class="service-card">
        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80" alt="Limpeza de Tapetes e Carpetes" />
        <h4>Tapetes e Carpetes</h4>
        <p>Limpeza especializada para manter seus tapetes e carpetes limpos, macios e livres de ácaros.</p>
      </div>
    </div>
  </section>
  <section id="galeria">
    <h3>Galeria Antes e Depois</h3>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1581579180386-1a0a4e1e9c2b?auto=format&fit=crop&w=600&q=80" alt="Antes" title="Antes" />
      <img src="https://images.unsplash.com/photo-1590080877777-0a1a8f1a6e8f?auto=format&fit=crop&w=600&q=80" alt="Depois" title="Depois" />
      <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80" alt="Antes" title="Antes" />
      <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=600&q=80" alt="Depois" title="Depois" />
    </div>
  </section>
  <section id="depoimentos">
    <h3>Depoimentos</h3>
    <div class="testimonials">
      <div class="testimonial">
        <p>"Excelente serviço! Meu sofá ficou como novo e o atendimento foi muito profissional."</p>
        <strong>– Ana Silva</strong>
      </div>
      <div class="testimonial">
        <p>"Recomendo a L'imper + para quem quer qualidade e rapidez na limpeza e impermeabilização."</p>
        <strong>– Carlos Pereira</strong>
      </div>
      <div class="testimonial">
        <p>"Ótima equipe, produtos seguros e resultados visíveis. Meu tapete nunca esteve tão limpo."</p>
        <strong>– Mariana Souza</strong>
      </div>
    </div>
  </section>
  <section id="contato">
    <h3>Contato</h3>
    <p>Entre em contato para solicitar um orçamento ou tirar dúvidas.</p>
    <form action="https://formspree.io/f/mgebqzqv" method="POST">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="name" required />
      <label for="email">Email:</label>
      <input type="email" id="email" name="_replyto" required />
      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="message" rows="4" required></textarea>
      <button type="submit">Enviar</button>
    </form>
    <p style="margin-top: 15px;">
      Email: <a href="mailto:contato@limpermais.com.br">contato@limpermais.com.br</a><br />
      Telefone: <a href="tel:+5511999999999">(11) 99999-9999</a><br />
      <a href="https://wa.me/5511999999999" target="_blank" style="color:#0077cc; font-weight:bold;">Fale conosco pelo WhatsApp</a>
    </p>
  </section>
</main>
<footer>
  &copy; 2025 L'imper +. Todos os direitos reservados.
</footer>
</body>
</html>
