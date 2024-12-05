# Estoque-por-packs
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contagem de Estoque</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      transition: background-color 0.3s, color 0.3s;
    }

    .container {
      width: 80%;
      max-width: 600px;
      margin: 50px auto;
      text-align: center;
    }

    h1 {
      margin-bottom: 20px;
    }

    .stock-item {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 10px;
      margin-bottom: 20px;
      font-size: 18px;
    }

    button {
      padding: 10px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 18px;
      width: 40px;
      height: 40px;
      text-align: center;
    }

    button.add {
      background-color: #28a745;
      color: white;
    }

    button.add:hover {
      background-color: #218838;
    }

    button.remove {
      background-color: #dc3545;
      color: white;
    }

    button.remove:hover {
      background-color: #c82333;
    }

    .theme-toggle {
      display: flex;
      justify-content: flex-end;
      margin-bottom: 20px;
      font-size: 24px;
      cursor: pointer;
    }

    .theme-toggle span {
      padding: 5px;
      border-radius: 50%;
    }

    .theme-toggle span:hover {
      background-color: var(--bg-color-hover);
    }

    /* Tema claro e escuro */
    :root {
      --bg-color: #f5f5f5;
      --text-color: #333;
      --bg-color-hover: #ccc;
    }

    body.dark {
      --bg-color: #333;
      --text-color: #f5f5f5;
      --bg-color-hover: #555;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Gestão de Estoque</h1>

... (72 linhas)
