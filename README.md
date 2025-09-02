<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soporte Garantizado Playa Ancha</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            width: 100%;
        }
        
        .flyer {
            max-width: 350px;
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
            margin: 0 auto;
        }
        
        .header {
            background: linear-gradient(135deg, #2c3e50 0%, #4a6491 100%);
            color: white;
            padding: 25px 20px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 28px;
            margin-bottom: 5px;
            font-weight: 700;
            letter-spacing: 1px;
        }
        
        .header h2 {
            font-size: 18px;
            font-weight: 400;
            letter-spacing: 1.5px;
        }
        
        .price {
            background: #f8f9fa;
            padding: 15px;
            text-align: center;
            border-bottom: 2px dashed #e0e0e0;
        }
        
        .price p {
            font-size: 18px;
            color: #2c3e50;
            font-weight: 600;
        }
        
        .price span {
            color: #e74c3c;
            font-weight: 700;
            font-size: 20px;
        }
        
        .services {
            padding: 20px;
        }
        
        .services ul {
            list-style: none;
        }
        
        .services li {
            padding: 10px 0;
            border-bottom: 1px solid #f0f0f0;
            display: flex;
            align-items: center;
        }
        
        .services li:last-child {
            border-bottom: none;
        }
        
        .services i {
            color: #27ae60;
            margin-right: 10px;
            font-size: 18px;
        }
        
        .contact {
            background: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        .contact-info {
            margin-bottom: 20px;
        }
        
        .phone {
            font-size: 22px;
            font-weight: 700;
            letter-spacing: 1px;
            margin: 10px 0;
            color: #3498db;
        }
        
        .email {
            font-size: 16px;
            margin: 15px 0;
            color: #f1c40f;
            word-break: break-all;
        }
        
        .qr-instruction {
            font-style: italic;
            margin-top: 15px;
            font-size: 15px;
        }
        
        .highlight {
            background: #f1c40f;
            color: #2c3e50;
            padding: 3px 5px;
            border-radius: 3px;
            font-weight: 600;
        }
        
        .logo {
            font-size: 24px;
            font-weight: 700;
            margin-bottom: 5px;
            color: #f1c40f;
        }
        
        .qr-container {
            margin: 15px auto;
            width: 150px;
            height: 150px;
            background: white;
            padding: 10px;
            border-radius: 10px;
        }
        
        .qr-container img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
        
        /* Estilos responsivos */
        @media (min-width: 768px) {
            .flyer {
                max-width: 700px;
                display: flex;
                flex-wrap: wrap;
            }
            
            .header {
                width: 100%;
            }
            
            .price {
                width: 100%;
            }
            
            .services {
                width: 50%;
            }
            
            .contact {
                width: 50%;
                display: flex;
                flex-direction: column;
                justify-content: center;
            }
        }
        
        @media (min-width: 992px) {
            .flyer {
                max-width: 900px;
            }
            
            .header h1 {
                font-size: 32px;
            }
            
            .services {
                padding: 30px;
            }
            
            .contact {
                padding: 30px;
            }
        }
        
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 40px;
            right: 40px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 3px #999;
            z-index: 100;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .whatsapp-float:hover {
            background-color: #128C7E;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="flyer">
            <div class="header">
                <div class="logo">SOPORTE GARANTIZADO</div>
                <h2>PLAYA ANCHA - VALPARAÍSO</h2>
            </div>
            
            <div class="price">
                <p>Desde <span>$5.000</span> dependiendo de la falla</p>
            </div>
            
            <div class="services">
                <ul>
                    <li><i class="fas fa-check-circle"></i> Diagnóstico superficial sin costo</li>
                    <li><i class="fas fa-check-circle"></i> Solución de fallas, cambio de pantalla y componentes</li>
                    <li><i class="fas fa-check-circle"></i> Formateo e instalación de programas</li>
                    <li><i class="fas fa-check-circle"></i> Recuperación de archivos</li>
                    <li><i class="fas fa-check-circle"></i> Atención de forma remota o presencial</li>
                    <li><i class="fas fa-check-circle"></i> Asesoramiento de armado de PC o de tecnología</li>
                </ul>
            </div>
            
            <div class="contact">
                <div class="contact-info">
                    <div class="phone">+56 9 9269 0324</div>
                    <div class="email">garantizadosoporte@gmail.com</div>
                </div>
                
                <div class="qr-container">
                    <img src="https://raw.githubusercontent.com/kmra00/garantizadovalparaiso/main/qr_whatsapp.png" alt="QR Code de WhatsApp">
                </div>
                
                <p class="qr-instruction"><span class="highlight">ESCANEA</span> Y CONTÁCTANOS</p>
            </div>
        </div>
    </div>
    
    <a href="https://wa.me/56992690324" class="whatsapp-float" target="_blank">
        <i class="fab fa-whatsapp"></i>
       <div>AQUI  (https://wa.me/56992690324)</div>
    </a>
</body>
</html>
