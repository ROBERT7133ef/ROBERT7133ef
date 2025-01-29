<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Accesorios para Celulares J & R - Venta de Accesorios para Celulares</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #2c2c2c;
            color: white;
        }
        .header {
            background-color: #1a1a1a;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            font-size: 36px;
            color: #f5a623;
        }
        .products, .contact {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .product, .contact-form {
            background-color: #333;
            padding: 20px;
            border-radius: 8px;
            width: 45%;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        button {
            background-color: #f5a623;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Accesorios para Celulares J & R</h1>
        <p>Venta de cargadores, fundas, micas y protectores de alta calidad</p>
    </div>

    <!-- Sección de Productos -->
    <div class="products">
        <div class="product">
            <h2>Catálogo de Productos</h2>
            <p>Explora nuestra variedad de accesorios para celulares. Encuentra lo que necesitas para tu dispositivo.</p>
            
            <div class="product-item">
                <h3>Cargadores</h3>
                <img src="https://www.achemex.com/cdn/shop/products/31CQaoKyp-L.jpg?v=1681945911" alt="Cargadores">
            </div>
            
            <div class="product-item">
                <h3>Fundas</h3>
                <img src="https://www.achemex.com/cdn/shop/products/516bW022UZL.jpg?v=1681934259" alt="Fundas">
            </div>

            <div class="product-item">
                <h3>Micas</h3>
                <img src="https://http2.mlstatic.com/D_NQ_NP_748274-MLM44763090633_012021-O.webp" alt="Micas">
            </div>
        </div>

        <!-- Sección de Contacto -->
        <div class="contact-form">
            <h2>Contáctanos</h2>
            <p>Correo electrónico: <a href="mailto:rcortesfelipe02@gmail.com">rcortesfelipe02@gmail.com</a></p>
            <p>Teléfono: <a href="tel:+529942639320">9942639320</a></p>
            <form action="mailto:rcortesfelipe02@gmail.com" method="post" enctype="text/plain">
                <label for="name">Nombre:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Correo Electrónico:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Mensaje:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>

                <button type="submit">Enviar mensaje</button>
            </form>
        </div>
    </div>

    <!-- Sección de Métodos de Pago y Ubicación -->
    <div class="contact">
        <div class="payment">
            <h2>Métodos de Pago</h2>
            <p>Aceptamos pagos por transferencia bancaria y en efectivo.</p>
        </div>

        <div class="location">
            <h2>Visítanos</h2>
            <p>Dirección: Sabino Crespo, 70146</p>
        </div>
    </div>
</body>
</html>
