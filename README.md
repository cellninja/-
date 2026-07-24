<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cell Ninja | Assistência Técnica e Acessórios</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        .card {
            width: 100%;
            max-width: 420px;
            background: #ffffff;
            border-radius: 20px;
            padding: 30px 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
        }
        .logo-container {
            margin-bottom: 20px;
        }
        .logo-container img {
            width: 140px;
            height: 140px;
            object-fit: contain;
            border-radius: 50%;
            border: 3px solid #6b1d2f;
            padding: 4px;
            background: #fff;
            box-shadow: 0 4px 10px rgba(0,0,0,0.08);
        }
        h1 {
            font-size: 1.6rem;
            color: #2c3e50;
            margin-bottom: 5px;
            font-weight: 700;
        }
        p.subtitle {
            font-size: 0.90rem;
            color: #666;
            margin-bottom: 25px;
            font-weight: 600;
        }
        .section-title {
            font-size: 1rem;
            color: #6b1d2f;
            margin: 20px 0 12px 0;
            text-align: left;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            font-weight: 600;
            border-left: 4px solid #6b1d2f;
            padding-left: 8px;
        }
        .services-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 10px;
            text-align: left;
            margin-bottom: 25px;
        }
        .service-item {
            background: #fdf8f8;
            padding: 12px 15px;
            border-radius: 8px;
            font-size: 0.92rem;
            color: #444;
            border: 1px solid #f2e6e6;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .service-item span {
            color: #28a745;
            font-weight: bold;
            font-size: 1.1rem;
        }
        .btn-container {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-top: 20px;
        }
        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 14px;
            border-radius: 10px;
            text-decoration: none;
            font-size: 1rem;
            font-weight: 600;
            transition: transform 0.2s, opacity 0.2s;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        }
        .btn:hover {
            transform: translateY(-2px);
            opacity: 0.95;
        }
        .btn-whatsapp {
            background-color: #25D366;
            color: white;
        }
        .btn-instagram {
            background: linear-gradient(45deg, #405de6, #5851db, #833ab4, #c13584, #fd1d1d, #fd8f3f);
            color: white;
        }
        footer {
            margin-top: 30px;
            font-size: 0.8rem;
            color: #888;
            border-top: 1px solid #eee;
            padding-top: 15px;
        }
    </style>
</head>
<body>

    <div class="card">
        <!-- Logo -->
        <div class="logo-container">
            <!-- Substitua o link abaixo pela imagem oficial da sua logo se preferir hospedar separadamente -->
            <img src="https://i.imgur.com/sua-logo-aqui.png" alt="Cell Ninja Logo">
            <h1>Cell Ninja</h1>
            <p class="subtitle">Serviços Básicos • Acessórios • Consertos Rápidos</p>
        </div>

        <!-- Serviços -->
        <div class="section-title">Nossos Serviços</div>
        <div class="services-grid">
            <div class="service-item"><span>✓</span> Troca de Telas e Displays</div>
            <div class="service-item"><span>✓</span> Manutenção e Consertos Básicos</div>
            <div class="service-item"><span>✓</span> Venda de Acessórios para Celular</div>
            <div class="service-item"><span>✓</span> Atendimento Rápido e de Confiança</div>
        </div>

        <!-- Contatos / Botões Clicáveis -->
        <div class="section-title">Fale Conosco</div>
        <div class="btn-container">
            <a href="https://wa.me/558581247263?text=Olá!%20Vim%20pelo%20site%20e%20gostaria%20de%20um%20orçamento." class="btn btn-whatsapp" target="_blank">
                💬 Chamar no WhatsApp
            </a>
            <a href="https://instagram.com/cell_ninjastory" class="btn btn-instagram" target="_blank">
                📸 Ver no Instagram (@cell_ninjastory)
            </a>
        </div>

        <footer>
            &copy; 2026 Cell Ninja • Fortaleza - CE
        </footer>
    </div>

</body>
</html>
