<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Turismo em Portugal</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: linear-gradient(to right, #4facfe, #00f2fe); color: #fff; }
        header { background: #0073e6; color: white; padding: 15px; text-align: center; }
        nav { text-align: center; padding: 10px; background: #005bb5; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        .container { padding: 20px; text-align: center; }
        .destaque { background: rgba(255, 255, 255, 0.2); padding: 20px; border-radius: 10px; }
        .lugares { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
        .lugar { border: 2px solid #fff; padding: 15px; width: 250px; text-align: center; background: rgba(0, 0, 0, 0.2); border-radius: 10px; }
        .lugar img { max-width: 100%; height: auto; border-radius: 5px; }
        h1, h2, h3 { text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); }
        .galeria { display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 30px; }
        .galeria img { width: 150px; height: 100px; border-radius: 5px; cursor: pointer; transition: transform 0.3s; }
        .galeria img:hover { transform: scale(1.1); }
    </style>
</head>
<body>
    <header>
        <h1>Turismo em Portugal</h1>
    </header>
    <nav>
        <a href="#">Início</a>
        <a href="#">Destinos</a>
        <a href="#">Contato</a>
    </nav>
    <div class="container">
        <section class="destaque">
            <h2>Descubra Portugal</h2>
            <p>Explore os melhores destinos turísticos de Portugal!</p>
            <img src="Gastronomia Portugal/6.jpg" alt="Paisagem de Portugal">
        </section>
        <section class="lugares">
            <div class="lugar">
                <img src="Lisboa1.jpg" alt="Lisboa">
                <h3>Lisboa</h3>
                <p>A capital cheia de história e cultura.</p>
            </div>
            <div class="lugar">
                <img src="porto.jpg" alt="Porto">
                <h3>Porto</h3>
                <p>Conhecida pelo seu vinho e arquitetura incrível.</p>
            </div>
            <div class="lugar">
                <img src="algarve.jpg" alt="Algarve">
                <h3>Algarve</h3>
                <p>Praias paradisíacas e clima maravilhoso.</p>
            </div>
        </section>
        <section class="galeria">
            <h2>Galeria de Fotos</h2>
            <img src="Castelos Portugal/Mouros_Final1.jpg" alt="Paisagem 1">
            <img src="torre_belem_lisboa.jpg" alt="Paisagem 2">
            <img src="Castelos Portugal/Monsaraz_Final.jpg" alt="Paisagem 3">
            <img src="Praiasenhora-da-rocha-vilamoura-algarve.jpg" alt="Paisagem 4">
        </section>
    </div>
</body>
</html>
