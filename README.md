# Agrinho.-2026
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agrinho 2026 - Campo e Cidade</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Agrinho 2026</h1>
    <p>Conectando o Campo e a Cidade</p>
</header>

<section class="banner">
    <h2>Tecnologia e Sustentabilidade</h2>
    <p>O futuro da agricultura depende da inovação e do cuidado com o meio ambiente.</p>
</section>

<section class="cards">
    <div class="card">
        <h3>🌱 Sustentabilidade</h3>
        <p>Produzir alimentos preservando os recursos naturais.</p>
    </div>

    <div class="card">
        <h3>🚜 Tecnologia</h3>
        <p>Máquinas inteligentes aumentam a produtividade no campo.</p>
    </div>

    <div class="card">
        <h3>🏙️ Campo e Cidade</h3>
        <p>Uma parceria essencial para o desenvolvimento da sociedade.</p>
    </div>
</section>

<section class="contador">
    <h2>Árvores Plantadas</h2>
    <p id="numero">0</p>
    <button onclick="plantar()">Plantar Árvore</button>
</section>body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4fff4;
}

header {
    background: #2e8b57;
    color: green;
    text-align: center;
    padding: 30px;
}

.banner {
    text-align: center;
    padding: 40px;
}

.cards {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
    padding: 20px;
}

.card {
    background: white;
    width: 250px;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.contador {
    text-align: center;
    padding: 40px;
}

button {
    background: green;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 8px;
    cursor: pointer;
}

button:hover {
    background: darkgreen;
}

footer {
    text-align: center;
    background: #2e8b57;let arvores = 0;

function plantar() {
    arvores++;
    document.getElementById("numero").textContent = arvores;
}
    color: pink;
    padding: 15px;
}
