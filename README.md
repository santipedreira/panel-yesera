# Panel de la yesera

Tablero de socios para seguir tareas, pasos y metas. Es solo la página: **no guarda ningún dato acá**. Los datos están en un repositorio privado y el panel los lee y los guarda con el token de GitHub de cada socio. Sin acceso a ese repositorio, el panel no muestra nada.

Dirección: https://santipedreira.github.io/panel-yesera/

## Instalarlo como app

- **iPhone o iPad:** abrir la dirección en Safari, tocar Compartir y después «Agregar a pantalla de inicio». Queda el ícono «Yesera» y se abre a pantalla completa.
- **Mac:** en Safari, Archivo → «Agregar al Dock».
- **Android o Chrome en la computadora:** menú del navegador → «Instalar app» o «Agregar a la pantalla principal».

La primera vez pide el token. Queda guardado solo en ese dispositivo (la app instalada en el iPhone guarda el suyo aparte de Safari). Cómo sacar el token está en el README del repositorio de datos. Conviene que venza a los 90 días y que el teléfono tenga bloqueo.

## Para cambiar el panel

Todo está en `index.html`. Los nombres de los socios no están en el código: salen de `socios` y `usuarios` en el archivo de datos.
