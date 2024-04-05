<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mynex - Venta de Portátiles</title>
    <link rel="icon" href="Logo.ico">
    <style>
        /* Estilos CSS aquí */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7; /* Color de fondo */
        }
        header {
            background-color: #353536;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #555;
        }
        section {
            padding: 20px;
            background-color: #fff; /* Fondo blanco para secciones */
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Sombra suave */
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            width: 100%;
            margin-top: 20px; /* Añadir margen superior */
        }
        .product-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-gap: 20px;
        }
        .product {
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #fff;
            transition: all 0.3s ease;
        }
        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        /* Estilos para el texto "Bienvenido a Mynex" */
        #inicio h2 {
            font-size: 36px; /* Tamaño de fuente más grande */
            color: #333; /* Cambiar color del texto */
            font-weight: bold; /* Hacer el texto negrita */
            text-transform: uppercase; /* Convertir texto a mayúsculas */
            text-align: center; /* Centrar el texto */
        }
        /* Estilos para el texto "Encuentra las mejores computadoras al mejor precio" */
        #inicio p {
            font-size: 24px; /* Tamaño de fuente más grande */
            color: #555; /* Cambiar color del texto */
            text-align: center; /* Centrar el texto */
            margin-top: 10px; /* Añadir margen superior */
            font-style: italic; /* Aplicar estilo cursiva */
        }
    </style>
</head>
<body>
    <header>
        <h1>Mynex - Venta de Computadoras</h1>
    </header>
    <nav>
        <a href="#inicio" style="background-color: #777;">Inicio</a> |
        <a href="#productos">Productos</a> |
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="inicio">
        <h2>Bienvenido a Mynex</h2>
        <p>¡Encuentra las mejores ofertas en computadoras!</p>
    </section>
    <section id="productos">
        <h2>Nuestros Productos</h2>
        <div class="product-container">
            <!-- Primer producto -->
            <div class="product">
                <ul>
                    <figure>
                        <img src="web3.jpg" height="100px " >
                    </figure>
                    <h1><li>Modelo: Portátil Lenovo V14-IGL (82C2006UCL)</li></h1>
                    
                    <p>Procesador: Intel® Celeron® N4020 caché de 4 M, hasta 2,80 GHz</p>
        
                    <p>Memoria Ram: 4 GB DDR4-2400 SDRAM (1 x 4 GB)</p>
        
                    <p>Disco Duro: 256 GB SSD M.2 PCIe® NVMe™</p>
                    <p>Precio: $230</p>
                    <a href="https://www.paypal.com/bo/home">
                    <button>Añadir al carrito</button>
                    </a>
                </ul>
            </div>
            
            </ul>
            <div class="product">
                <ul>
                    <figure>
                        <img src="web2.jpg" height="106px">
                    </figure>
                    <h1><li>Modelo: Portátil HP Pavilion 15-EG0508LA (766L8LA)</li></h1>
                   
                    <p>Procesador: Intel® Core™ i5-1135G7 caché de 8 MB, hasta 4,20 GHz</p>
                    <p>Memoria Ram: 8 GB DDR4-3200 SDRAM</p>
                    <p>Disco Duro: 256 GB SSD M.2 PCIe® NVMe™</p>
                    <p>Pantalla: 15.6" FHD (1920 x 1080) WLED IPS de microborde</p>
                    <p>Tarjeta de Video: Intel® Iris® Xe Graphics Integrada</p>
                    <p>Sistema Operativo: Windows 11 Home 64 Original</p>
                    <p>Teclado: Numérico En Español</p>
                    <p>Estado: Nuevo de caja sellada (Garantía HP Hardware)</p>
                    <p>Precio: $800</p>
                    <a href="https://www.paypal.com/bo/home">
                        <button>Añadir al carrito</button>
                    </a>
                </ul>
            </div>
            <!-- Tercer producto -->
            <div class="product">
                <ul>
                    <figure>
                        <img src="web4.jpg" height="100px">
                    </figure>
                    <h1><li>Modelo: Portátil HP 250 G9 (7C6E4LT)</li></h1>
                   
                    <p>Procesador: Intel® Celeron® N4020 caché de 4 M, hasta 2,80 GHz</p>
        
                    <p>Memoria Ram: 4 GB DDR4-2400 SDRAM (1 x 4 GB)</p>
        
                    <p>Disco Duro: 256 GB SSD M.2 PCIe® NVMe™</p>
                    <p>Precio: $230</p>
                    <a href="https://www.paypal.com/bo/home">
                    <button>Añadir al carrito</button>
                    </a>
                </UL>  
            </div>
            <!-- Repite el patrón para los siguientes grupos de productos -->
        </div>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Estamos ubicados en [Dirección].</p>
        <p>Puedes contactarnos al teléfono: wa.link/2dqs52 o por correo electrónico: info.mynex@gmail.com.</p>
    </section>
    <footer>
        <p>&copy; 2024 Mynex - Todos los derechos reservados</p>
    </footer>
</body>
</html>
