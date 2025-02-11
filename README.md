



<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Fluxograma</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #2c3e50;
        }
        .example {
            background-color: #ecf0f1;
            padding: 10px;
            margin-top: 20px;
            border-radius: 5px;
        }
        .flowchart {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }
        .flowchart div {
            background-color: #3498db;
            color: white;
            padding: 10px;
            margin: 5px;
            border-radius: 5px;
            text-align: center;
            width: 200px;
        }
        .flowchart .decision {
            background-color: #e74c3c;
        }
        .flowchart .arrow {
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1>Exemplo de Fluxograma</h1>
    <p>A seguir, um exemplo simples de um fluxograma que representa o processo de decisão para levar um guarda-chuva:</p>
    <div class="example">
        <div class="flowchart">
            <div>Início</div>
            <div class="arrow">↓</div>
            <div class="decision">Está chovendo?</div>
            <div class="arrow">↓</div>
            <div>Sim → Levar um guarda-chuva</div>
            <div class="arrow">↓</div>
            <div>Não → Não levar um guarda-chuva</div>
            <div class="arrow">↓</div>
            <div>Fim</div>
        </div>
    </div>
</body>
</html>


