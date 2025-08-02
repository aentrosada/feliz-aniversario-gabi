<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapa da Vida da Gabriela</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            background: linear-gradient(135deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4);
            background-size: 400% 400%;
            animation: gradientShift 15s ease infinite;
            min-height: 100vh;
            overflow-x: auto;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .header {
            text-align: center;
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .header h1 {
            color: #2c3e50;
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }

        .header p {
            color: #7f8c8d;
            font-size: 1.2em;
        }

        .map-container {
            position: relative;
            display: flex;
            justify-content: center;
            padding: 20px;
            min-height: 80vh;
        }

        .main-map {
            position: relative;
            max-width: 1200px;
            width: 100%;
            border-radius: 15px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            background: white;
        }

        .main-map img {
            width: 100%;
            height: auto;
            display: block;
        }

        .hotspot {
            position: absolute;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(255, 0, 0, 0.8);
            border: 3px solid white;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: white;
            font-size: 14px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .hotspot:hover {
            transform: scale(1.2);
            background: rgba(255, 0, 0, 1);
            box-shadow: 0 6px 20px rgba(255, 0, 0, 0.4);
        }

        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            backdrop-filter: blur(5px);
        }

        .modal-content {
            background: white;
            margin: 5% auto;
            padding: 0;
            border-radius: 15px;
            width: 90%;
            max-width: 800px;
            max-height: 80vh;
            overflow-y: auto;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
            animation: modalSlideIn 0.3s ease;
        }

        @keyframes modalSlideIn {
            from {
                transform: translateY(-50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        .modal-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            border-radius: 15px 15px 0 0;
            position: relative;
        }

        .modal-header h2 {
            margin: 0;
            font-size: 1.8em;
        }

        .close {
            position: absolute;
            right: 20px;
            top: 20px;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .close:hover {
            color: #ff6b6b;
        }

        .modal-body {
            padding: 20px;
        }

        .modal-image {
        max-width: 100%;
        max-height: 500px;
        height: auto;
        width: auto;
        display: block;
        margin: 0 auto 20px auto;
        border-radius: 10px;
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .modal-description {
            font-size: 1.1em;
            line-height: 1.6;
            color: #2c3e50;
        }

        .instructions {
            background: rgba(255, 255, 255, 0.9);
            margin: 20px;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .instructions h3 {
            color: #e74c3c;
            margin-bottom: 10px;
            font-size: 1.5em;
        }

        .instructions p {
            color: #2c3e50;
            font-size: 1.1em;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }
            
            .header p {
                font-size: 1em;
            }
            
            .hotspot {
                width: 30px;
                height: 30px;
                font-size: 12px;
            }
            
            .modal-content {
                width: 95%;
                margin: 10% auto;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>🔍 Mapa da Vida da Gabriela</h1>
        <p>Versão Interativa - Onde Está a Wally?</p>
    </div>

    <div class="instructions">
        <h3>Como Jogar</h3>
        <p>Clique nos pontos vermelhos para explorar os locais da vida da Gabriela. Encontre a Gabriela escondida em pequenos fragmentos de sua história.</p>
    </div>

    <div class="map-container">
        <div class="main-map">
            <img src="gabriela_wally_main_map_revised1.png" alt="Mapa da Vida da Gabriela" id="mainMapImage">
            
            <!-- Hotspots serão adicionados dinamicamente via JavaScript -->
        </div>
    </div>

    <!-- Modal -->
    <div id="modal" class="modal">
        <div class="modal-content">
            <div class="modal-header">
                <h2 id="modalTitle">Título</h2>
                <span class="close">&times;</span>
            </div>
            <div class="modal-body">
                <img id="modalImage" class="modal-image" src="" alt="">
                <div id="modalDescription" class="modal-description"></div>
            </div>
        </div>
    </div>

    <script>
        // Dados dos locais
        const locations = [
            {
                id: 'hospital-usp',
                name: 'Hospital USP',
                x: 15, // Porcentagem da posição X
                y: 20, // Porcentagem da posição Y
                image: 'hospital_usp_filled.png',
                description: 'O início de tudo! Hospital da USP em São Paulo, onde Gabriela nasceu em 01/08/1998 as 16:11. Deixou o ventre de dona Elaine e estreou nesse espetáculo que ela chama de vida.'
            },
            {
                id: 'rua-23',
                name: 'Rua 23',
                x: 25,
                y: 35,
                image: 'rua_23_metalurgicos_filled.png',
                description: 'Rua 23 - Conjunto dos Metalúrgicos, Novo Osasco. O primeiro lar da Gabriela, onde viveu até os 4 meses de idade. Uma rua simples que marcou seus primeiros dias.'
            },
            {
                id: 'rua-elioterio',
                name: 'Rua Eliotério',
                x: 40,
                y: 25,
                image: 'passagem_elioterio_filled.png',
                description: 'Passagem - Rua Eliotério de Medeiros. Dos 4 meses aos 3 anos, Gabriela viveu nesta passagem acolhedora em Osasco, onde começou a descobrir o mundo.'
            },
            {
                id: 'rua-yamamoto',
                name: 'Rua J.Y. Yamamoto',
                x: 60,
                y: 40,
                image: 'rua_jose_yoshie_yamamoto_filled.png',
                description: 'Rua José Yoshie Yamamoto, 155. Dos 3 aos 19 anos, este foi o lar da Gabriela por mais tempo. Aqui ela cresceu, estudou e se tornou a pessoa que é hoje.'
            },
            {
                id: 'prisma',
                name: 'Prisma',
                x: 20,
                y: 60,
                image: 'prisma_pre_escola_filled.png',
                description: 'Colégio Prisma - A pré-escola onde Gabriela deu seus primeiros passos na educação. Fez seu primeiro livro, babadeiro e divonico com desenhos MIL de lindos'
            },
            {
                id: 'fito',
                name: 'FITO',
                x: 35,
                y: 70,
                image: 'fito_escola_filled.png',
                description: 'FITO - Fundação Instituto Tecnológico de Osasco. Até a 5ª série, Gabriela estudou nesta instituição reconhecida, construindo as bases de sua educação.'
            },
            {
                id: 'papa-mike',
                name: 'Papa Mike',
                x: 55,
                y: 65,
                image: 'papa_mike_escola_filled.png',
                description: 'Colégio Papa Mike - Uma página de sua vida, Gabi como sempre brilhou mais do que Glitter e que Blaine.'
            },
            {
                id: 'haya',
                name: 'Haya',
                x: 75,
                y: 55,
                image: 'haya_escola_filled.png',
                description: 'Colégio Haya - Ensino Médio. Aqui Gabriela se preparou para o resto de sua vida e PRO VESTIBULAAAAR.'
            },
            {
                id: 'uel',
                name: 'UEL',
                x: 80,
                y: 30,
                image: 'uel_universidade_filled.png',
                description: 'Universidade Estadual de Londrina (UEL) - Palco do desfilar acadêmico da diva. Graduou e Mestrará nesses prédios e jardins.'
            },
            {
                id: 'universiflex',
                name: 'Universiflex',
                x: 85,
                y: 45,
                image: 'universiflex_republica_filled.png',
                description: 'Rua Delaine Negro, 50 - Universiflex. Só Deus e Scoth sabem ao certo o que aconteceu lá (rs).'
            },
            {
                id: 'amor-vida',
                name: 'Amor da Vida',
                x: 70,
                y: 75,
                image: 'encontro_no_people.png',
                description: 'O encontro com o amor da vida em 15/12/2019 mudou muito aquele dia e os anos seguintes.'
            },
           {
                id: 'av-jk',
                name: 'Av. JK',
                x: 90,
                y: 60,
                image: 'familia.png',
                description: 'Av. JK, lar de sua família onde ela constrói seu futuro ao lado de Thainá, Valentina, Mia e Chico.'
            }
        
];

        // Função para criar hotspots
        function createHotspots() {
            const mapContainer = document.querySelector('.main-map');
            
            locations.forEach((location, index) => {
                const hotspot = document.createElement('div');
                hotspot.className = 'hotspot';
                hotspot.style.left = location.x + '%';
                hotspot.style.top = location.y + '%';
                hotspot.textContent = index + 1;
                hotspot.setAttribute('data-location', location.id);
                
                hotspot.addEventListener('click', () => openModal(location));
                
                mapContainer.appendChild(hotspot);
            });
        }

        // Função para abrir modal
        function openModal(location) {
            const modal = document.getElementById('modal');
            const modalTitle = document.getElementById('modalTitle');
            const modalImage = document.getElementById('modalImage');
            const modalDescription = document.getElementById('modalDescription');
            
            modalTitle.textContent = location.name;
            modalImage.src = location.image;
            modalImage.alt = location.name;
            modalDescription.textContent = location.description;
            
            modal.style.display = 'block';
            document.body.style.overflow = 'hidden';
        }

        // Função para fechar modal
        function closeModal() {
            const modal = document.getElementById('modal');
            modal.style.display = 'none';
            document.body.style.overflow = 'auto';
        }

        // Event listeners
        document.addEventListener('DOMContentLoaded', function() {
            createHotspots();
            
            // Fechar modal
            const closeBtn = document.querySelector('.close');
            closeBtn.addEventListener('click', closeModal);
            
            // Fechar modal clicando fora
            const modal = document.getElementById('modal');
            modal.addEventListener('click', function(e) {
                if (e.target === modal) {
                    closeModal();
                }
            });
            
            // Fechar modal com ESC
            document.addEventListener('keydown', function(e) {
                if (e.key === 'Escape') {
                    closeModal();
                }
            });
        });
    </script>
</body>
</html>

