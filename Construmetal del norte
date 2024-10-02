<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Construmetal del Norte - Compras en Línea</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .banner {
            background-image: url('URL_DE_TU_IMAGEN_BANNER'); /* Cambia esto por la URL de tu imagen */
            height: 300px;
            background-size: cover;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2em;
        }
        .container {
            padding: 20px;
            text-align: center;
        }
        .product-category {
            display: inline-block;
            width: 30%;
            margin: 20px;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
        }
        .product-category img {
            max-width: 100%;
            height: auto;
        }
        .cart {
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            margin: 20px;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .quote-form {
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 20px auto;
            width: 50%;
        }
        .quote-form input, .quote-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>Construmetal del Norte</h1>
    <nav>
        <a href="#productos">Productos</a>
        <a href="#cotizaciones">Cotizaciones</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <p>Llámanos al 3116612744</p>
</header>

<div class="banner">
    <h2>Los mejores materiales para tus proyectos</h2>
</div>

<div class="container">
    <h2 id="productos">Productos</h2>
    <div class="product-category">
        <img src="URL_IMAGEN_CEMENTO" alt="Cemento">
        <h3>Cemento</h3>
        <p>Descripción breve del cemento.</p>
    </div>
    <div class="product-category">
        <img src="URL_IMAGEN_HERRAMIENTAS" alt="Herramientas">
        <h3>Herramientas</h3>
        <p>Descripción breve de herramientas.</p>
    </div>
    <div class="product-category">
        <img src="URL_IMAGEN_MATERIALES" alt="Materiales Eléctricos">
        <h3>Materiales Eléctricos</h3>
        <p>Descripción breve de materiales eléctricos.</p>
    </div>

    <h2>Venta de Pintura</h2>
    <div class="product-category">
        <img src="URL_IMAGEN_PINTURA_TIPO1" alt="Pintura Tipo 1">
        <h3>Pintura Tipo 1</h3>
        <p>Descripción breve de la pintura tipo 1.</p>
    </div>
    <div class="product-category">
        <img src="URL_IMAGEN_PINTURA_TIPO2" alt="Pintura Tipo 2">
        <h3>Pintura Tipo 2</h3>
        <p>Descripción breve de la pintura tipo 2.</p>
    </div>
    <div class="product-category">
        <img src="URL_IMAGEN_PINTURA_TIPO3" alt="Pintura Tipo 3">
        <h3>Pintura Tipo 3</h3>
        <p>Descripción breve de la pintura tipo 3.</p>
    </div>

    <div class="cart">
        <h2>Carrito de Compras</h2>
        <p>No hay productos en tu carrito.</p>
        <button onclick="processPayment()">Proceder al Pago</button>
    </div>

    <h2 id="cotizaciones">Solicitar Cotización</h2>
    <div class="quote-form">
        <h3>Formulario de Cotización</h3>
        <input type="text" id="quote-name" placeholder="Nombre" required>
        <input type="tel" id="quote-phone" placeholder="Número de Teléfono" required>
        <textarea id="quote-details" placeholder="Detalles de la cotización" rows="5" required></textarea>
        <button onclick="submitQuote()">Enviar Cotización</button>
    </div>
</div>

<footer>
    <p>&copy; 2024 Construmetal del Norte. Todos los derechos reservados.</p>
</footer>

<script>
    function submitQuote() {
        const name = document.getElementById('quote-name').value;
        const phone = document.getElementById('quote-phone').value;
        const details = document.getElementById('quote-details').value;

        if (name && phone && details) {
            alert('Cotización enviada. Gracias, ' + name + '!');
            document.getElementById('quote-name').value = '';
            document.getElementById('quote-phone').value = '';
            document.getElementById('quote-details').value = '';
        } else {
            alert('Por favor, completa todos los campos.');
        }
    }

    async function processPayment() {
        // Aquí iría el código para procesar el pago con Stripe
        // Para este ejemplo, se omite la implementación real de Stripe.
        alert('Procediendo al pago (implementación de Stripe necesaria).');
    }
</script>

</body>
</html>
