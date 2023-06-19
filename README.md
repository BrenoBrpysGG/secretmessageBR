<!DOCTYPE html>
<html>
<head>
  <title>Tela de Senha</title>
  <script>
    function verificarSenha() {
      var senhaInserida = document.getElementById("senha").value;
      
      if (senhaInserida === "255") {
        window.location.href = "https://www.example.com"; // Substitua o link pelo seu link específico
      } else {
        alert("Senha incorreta. Tente novamente.");
      }
    }
  </script>
</head>
<body>
  <h1>Tela de Senha</h1>
  <input type="password" id="senha" placeholder="Digite a senha">
  <br>
  <button onclick="verificarSenha()">Enviar</button>
</body>
</html>
