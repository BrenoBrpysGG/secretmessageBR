<!DOCTYPE html>
<html>
<head>
  <title>Insira a senha para entrar!</title>
  <script>
    function verificarSenha() {
      var senhaInserida = document.getElementById("senha").value;
      
      if (senhaInserida === "255404") {
        window.location.href = "https://youtube.com/@BrenoPlayerZ_IMDD"
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
