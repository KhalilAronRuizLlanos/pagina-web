nstalación

1. Incluir Bootstrap desde CDN (Opción rápida)

Agrega el siguiente enlace en el <head> de tu archivo HTML:

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

2. Instalación con npm (Opción recomendada)

Si prefieres usar Bootstrap con npm, ejecuta:

npm install bootstrap

Luego, impórtalo en tu archivo JavaScript o SCSS:

import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap/dist/js/bootstrap.bundle.min';

Uso básico

Ejemplo de una estructura HTML con Bootstrap:

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Proyecto con Bootstrap</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container">
        <h1 class="text-center">Bienvenido a Bootstrap</h1>
        <button class="btn btn-primary">Haz clic</button>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

Personalización

Para modificar estilos, puedes sobrescribir las clases de Bootstrap en tu propio archivo CSS o utilizar SASS si instalaste Bootstrap con npm.

Créditos

Este proyecto utiliza Bootstrap 5 para facilitar el diseño y la maquetación.

Licencia

Este proyecto está bajo la licencia MIT.