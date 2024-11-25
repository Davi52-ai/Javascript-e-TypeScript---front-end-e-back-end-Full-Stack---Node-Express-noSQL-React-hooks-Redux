# Javascript e TypeScript - front-end e back-end Full Stack - Node, Express, noSQL, React, hooks, Redux, Design Patterns
Testes
# Página Básica com JavaScript:

# EXEMPLO:

<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Página Básica com JavaScript</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f9;
        color: #333;
        margin: 0;
        padding: 20px;
      }

      h1 {
        color: #0056b3;
      }

      button {
        background-color: #0056b3;
        color: white;
        border: none;
        padding: 10px 20px;
        font-size: 16px;
        cursor: pointer;
        border-radius: 5px;
        margin-top: 10px;
      }

      button:hover {
        background-color: #003f8a;
      }

      #content {
        margin-top: 20px;
        padding: 10px;
        border: 1px solid #ddd;
        border-radius: 5px;
        background-color: #fff;
      }
    </style>
  </head>
  <body>
    <h1>Bem-vindo à minha página</h1>
    <p>
      Esta é uma página básica com JavaScript. Clique no botão abaixo para
      adicionar conteúdo:
    </p>
    <button id="addContentButton">Adicionar Conteúdo</button>

    <div id="content"></div>

    <script>
      // Seleciona o botão e o container do conteúdo
      const button = document.getElementById("addContentButton");
      const contentDiv = document.getElementById("content");

      // Função para adicionar conteúdo dinâmico
      button.addEventListener("click", () => {
        const paragraph = document.createElement("p");
        paragraph.textContent = "Este é um conteúdo adicionado dinamicamente!";
        contentDiv.appendChild(paragraph);
      });
    </script>
  </body>
</html>
