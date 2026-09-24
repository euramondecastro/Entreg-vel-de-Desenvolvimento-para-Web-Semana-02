# Entreg-vel-de-Desenvolvimento-para-Web-Semana-02

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Formulário de Inscrição</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <main class="main-container">
    <form class="form-card">
      <h2 class="form-title">Inscreva-se no Blog</h2>
      <p class="form-subtitle">Receba as melhores novidades e conteúdos semanalmente.</p>

      <!-- Linha lado a lado (Bônus) -->
      <div class="form-row">
        <div class="form-group">
          <label for="nome">Nome completo</label>
          <input type="text" id="nome" name="nome" placeholder="Seu nome completo" required>
        </div>

        <div class="form-group">
          <label for="email">E-mail</label>
          <input type="email" id="email" name="email" placeholder="seu@email.com" required>
        </div>
      </div>

      <!-- Outros campos verticais -->
      <div class="form-group">
        <label for="interesses">Área de interesse</label>
        <select id="interesses" name="interesses" required>
          <option value="" disabled selected>Selecione uma opção</option>
          <option value="tecnologia">Tecnologia & Desenvolvimento</option>
          <option value="design">Design & UX</option>
          <option value="negocios">Negócios & Inovação</option>
        </select>
      </div>

      <button type="submit" class="btn-submit">Garantir Minha Vaga</button>
    </form>
  </main>

</body>
</html>
