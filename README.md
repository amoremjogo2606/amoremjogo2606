<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amor em Jogo</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Bem-vindo ao <span>Amor em Jogo</span></h1>
    <p>Descubra o quanto vocês se conhecem!</p>
    <button onclick="startGame()">Começar</button>
  </div>
  <div class="overlay"></div> <!-- Overlay escuro -->
</body>
</html>
/* Estilo básico para o body e fundo */
body {
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
  background-image: url('sua-imagem.jpg'); /* Substitua pelo nome correto da sua imagem */
  background-size: cover;
  background-position: center;
  height: 100vh;
}

/* Sobreposição escura para suavizar a imagem */
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.4); /* Escurece a imagem */
  z-index: -1;
}

/* Estilo do conteúdo central */
.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  text-align: center;
  color: #fff; /* Texto claro para contraste */
  z-index: 1;
}

/* Título */
h1 {
  font-size: 3em;
  margin: 0;
  font-weight: bold;
}

h1 span {
  color: #ff66b2; /* Cor romântica para destaque */
}

/* Botão de início */
button {
  background-color: #ff66b2;
  color: #fff;
  border: none;
  padding: 15px 30px;
  font-size: 1.2em;
  cursor: pointer;
  border-radius: 5px;
  margin-top: 20px;
  transition: background-color 0.3s;
}

button:hover {
  background-color: #ff3385; /* Cor de hover mais forte */
}
