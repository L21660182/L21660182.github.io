<!DOCTYPE html>
<html lang="es">
<!-- Definición del documento HTML5 y declaración del idioma español -->
<head>
    <meta charset="UTF-8">
    <!-- Configura la codificación de caracteres como UTF-8, soporta la mayoría de caracteres -->
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Hace que el ancho de la página se ajuste al dispositivo, para mejor visualización en móviles -->
    
    <title>Mostrar Mensaje</title>
    <!-- El título que aparecerá en la pestaña del navegador -->
</head>
<body>
    <!-- Cuerpo de la página, donde se define el contenido visible -->
    
    <p id="soyelid"></p>
    <!-- Párrafo con el id 'soyelid', inicialmente vacío, donde se mostrará el mensaje -->

    <script>
        // El código JavaScript se ejecutará cuando la página se haya cargado por completo
        window.onload = function() {
            // Selecciona el elemento con el id 'soyelid' y cambia su texto interno
            document.getElementById("soyelid").innerText = "¡No me gusta la programación!";
        };
    </script>
    <!-- El bloque <script> contiene el JavaScript que controla la página -->
</body>
</html>

