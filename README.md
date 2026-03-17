<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Leandro | Euro Diesel</title>
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
            overflow: hidden; /* Evita rolagem desnecessária no celular */
        }

        /* Fundo com degradê de luxo */
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
            height: 90vh; /* Ocupa quase a tela toda verticalmente */
            background: var(--glass);
            border: 1px solid rgba(211, 175, 55, 0.3);
            border-radius: 25px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            padding: 40px 20px;
            box-sizing: border-box;
            backdrop-filter: blur(15px);
            box-shadow: 0 25px 50px rgba(0,0,0,0.8);
        }

        .header { text-align: center; }

        .logo-text {
            color: var(--gold);
            letter-spacing: 6px;
            font-size: 0.8rem;
            font-weight: 300;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .profile-name {
            font-size: 2.2rem;
            font-weight: 700;
            color: #fff;
            margin: 5px 0;
            letter-spacing: 2px;
        }

        .profile-job {
            color: var(--gold);
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 3px;
            font-weight: 400;
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
            letter-spacing: 1px;
            transition: 0.3s;
            box-sizing: border-box;
            display: block;
            text-transform: uppercase;
        }

        /* Botão Principal WhatsApp */
        .btn-primary {
            background: linear-gradient(135deg, #D4AF37, #B8860B);
            color: #000;
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.2);
        }

        /* Botões Secundários */
        .btn-outline {
            border: 1px solid rgba(255,255,255,0.2);
            color: #fff;
        }

        .btn:active {
            transform: scale(0.98);
            opacity: 0.8;
        }

        .footer-info {
            text-align: center;
            color: rgba(255,255,255,0.4);
            font-size: 0.7rem;
            line-height: 1.5;
        }

        /* Detalhe decorativo */
        .gold-line {
            width: 40px;
            height: 2px;
            background: var(--gold);
            margin: 20px auto;
        }
    </style>
</head>
<body>

    <div class="bg-gradient"></div>

    <div class="container">
        <div class="header">
            <div class="logo-text">EURO DIESEL</div>
            <div class="gold-line"></div>
            <h1 class="profile-name">LEANDRO</h1>
            <p class="profile-job">Gerente Financeiro</p>
        </div>

        <div class="actions">
            <a href="https://wa.me/5569981128233" class="btn btn-primary">
                Falar no WhatsApp
            </a>
            
            <a href="https://www.google.com/maps/place/Euro+Diesel+Especializada+linha+Volvo+Scania+Mecatronica+Inje%C3%A7%C3%A3o+Eletronica+Catalizador+Modulos+Centrais+Vilhena+RO/data=!4m2!3m1!1s0x0:0xe56ce9eadefe2e90?sa=X&ved=1t:2428&ictx=111" class="btn btn-outline" target="_blank">
                Localização Euro Diesel
            </a>

            <a href="mailto:leandro@eurodiesel.com" class="btn btn-outline">
                Enviar E-mail
            </a>
        </div>

        <div class="footer-info">
            ESTRADA DO DIESEL, RO<br>
            © 2026 EURO DIESEL - PREMIUM SOLUTIONS
        </div>
    </div>

</body>
</html>
