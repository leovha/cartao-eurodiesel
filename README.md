Put your HTML text here<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    
    <title>Leandro | Gerente Financeiro - Euro Diesel</title>
    <meta name="description" content="Cartão de Visita Digital - Euro Diesel">
    
    <meta property="og:image" content="hhttps://leovha.github.io/cartao-eurodiesel>
    <meta property="og:image:type" content="image/jpeg">
    <meta property="og:image:width" content="300">
    <meta property="og:image:height" content="300">
    <meta property="og:title" content="Leandro | Euro Diesel">
    <meta property="og:description" content="Gerente Financeiro - Clique para contatos e localização.">
    <meta property="og:url" content="https://seu-usuario.github.io/seu-repositorio/">
    <meta property="og:type" content="website">

    <style>
        :root {
            --gold: #D4AF37;
            --dark: #0a0a0a;
            --glass: rgba(255, 255, 255, 0.05);
        }

        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            background-color: var(--dark);
            font-family: 'Helvetica Neue', Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        .bg-gradient {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at top right, #1a1a1a, #000);
            z-index: -1;
        }

        .container {
            width: 90%;
            max-width: 400px;
            height: 85vh;
            background: var(--glass);
            border: 1px solid rgba(211, 175, 55, 0.3);
            border-radius: 25px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-around;
            padding: 40px 20px;
            box-sizing: border-box;
            backdrop-filter: blur(15px);
            box-shadow: 0 25px 50px rgba(0,0,0,0.8);
        }

        .logo-text {
            color: var(--gold);
            letter-spacing: 6px;
            font-size: 0.8rem;
            font-weight: 300;
            text-transform: uppercase;
        }

        .profile-name {
            font-size: 2.2rem;
            font-weight: 700;
            color: #fff;
            margin: 10px 0;
            letter-spacing: 2px;
        }

        .profile-job {
            color: var(--gold);
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 3px;
        }

        .actions {
            width: 100%;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .btn {
            width: 100%;
            padding: 18px;
            border-radius: 12px;
            text-align: center;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.9rem;
            display: block;
            text-transform: uppercase;
            transition: 0.3s;
        }

        .btn-primary {
            background: linear-gradient(135deg, #D4AF37, #B8860B);
            color: #000;
        }

        .btn-outline {
            border: 1px solid rgba(255,255,255,0.2);
            color: #fff;
        }

        .footer-info {
            text-align: center;
            color: rgba(255,255,255,0.4);
            font-size: 0.7rem;
        }
    </style>
</head>
<body>
    <div class="bg-gradient"></div>
    <div class="container">
        <div style="text-align: center;">
            <div class="logo-text">EURO DIESEL</div>
            <h1 class="profile-name">LEANDRO</h1>
            <p class="profile-job">Gerente Financeiro</p>
        </div>

        <div class="actions">
            <a href="https://wa.me/5569981128233" class="btn btn-primary">WhatsApp Direto</a>
            <a href="https://www.google.com/maps/place/Euro+Diesel+Especializada+linha+Volvo+Scania+Mecatronica+Inje%C3%A7%C3%A3o+Eletronica+Catalizador+Modulos+Centrais+Vilhena+RO/data=!4m2!3m1!1s0x0:0xe56ce9eadefe2e90?sa=X&ved=1t:2428&ictx=111" class="btn btn-outline" target="_blank">Localização</a>
            <a href="mailto:financeiro@eurodiesel.com" class="btn btn-outline">E-mail Corporativo</a>
        </div>

        <div class="footer-info">
            RO - BRASIL<br>
            © 2026 EURO DIESEL
        </div>
    </div>
</body>
</html>
