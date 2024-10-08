# Harmony
Clínica
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: pink;
        }
        .btn {
            padding: 10px 20px;
            background-color: purple;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .btn:hover {
            background-color: skyblue;
        }
        video {
            margin: 20px 0;
        }

        h1 {
            font-family: 'Pacifico', cursive; /* Fuente divertida */
            color: #ff69b4; /* Rosa fuerte */
            text-align: center;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <!-- audio-->
    <body onclick="PlayAudio()">
        <audio id="audio" autoplay controls loop>
            <source src="audios/lofi.mp3" type= "audio/mpeg">
            </audio>

    <h1>🌸 Bienvenido a Mi Emprendimiento Familiar 🌸</h1>
    <p>Descubre los servicios que Pablo, Birna y Sofía tenemos para ofrecerte.</p>
    <br>
    <title>Resumen de la Empresa Familiar</title>
    <style>
     .justificado {
            text-align: justify;
            line-height: 1.6; 
            width: 65%;
            margin-left: 20%; /* Margen izquierdo del 20% */
            margin-right: 20%; /* Opcional: para un mejor aspecto, puedes centrar también a la derecha */
            margin-top: 50px; /* Espacio en la parte superior */
        
        }
    </style>
</head>
<body>

    <div class="justificado">
        <p>
            Este es un pequeño resumen de nuestra empresa familiar que se dedica a ofrecer servicios especializados en el cuidado, embellecimiento y rejuvenecimiento de la piel del rostro. Los tratamientos que se realizan suelen incluir limpieza facial profunda, exfoliaciones, hidratación, tratamientos antiarrugas, mascarillas, masajes faciales, peeling, tratamientos para manchas, acné, entre otros. 
        </p>
        <p>
            El objetivo principal es mejorar la apariencia de la piel, prevenir el envejecimiento prematuro y tratar problemas cutáneos específicos para que los clientes logren una piel más saludable y estéticamente agradable. Algunas empresas también pueden ofrecer productos para el cuidado facial que complementan los tratamientos realizados en el establecimiento.
        </p>
    </div>




<!-- video -->
    <video width="400" controls>
        <source src="videos/1006.mp4" type="video/mp4">
        Tu navegador no soporta el video.
    </video>

    <div>
        <button class="btn" onclick="window.location.href='mision.html'">Nuestra Misión</button>
        <button class="btn" onclick="window.location.href='galeria2.html'">Galería</button>
        <button class="btn" onclick="window.location.href='contacto.html'">Contáctanos</button>
    </div>

    <p>Nuestra dirección es: 
        
    <p>7 calle 32-32 Z. 11 ,El Zompopero, Guatemala City, Guatemala</p>

    <p>Síguenos en nuestras redes sociales: 
        
        <a href="https://www.instagram.com/clinicaharmonygt/">Instagram</a> 
        <p>Para más información comuníquese al Tel. +502 5871-6808</p>
        
    </p>

        
    </p>
</body>
</html>

