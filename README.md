# Proyecto: Sitio estático

Este repositorio contiene un pequeño sitio estático con los archivos:

- `index.html`
- `styles.css`

A continuación encontrarás instrucciones para levantar el proyecto localmente usando Live Server (extensión de Visual Studio Code) y una alternativa con la utilidad `live-server` de npm.

## Requisitos

- Visual Studio Code (recomendado) 
- Extensión Live Server (Ritwick Dey) instalada en VS Code

## Levantar con Live Server (Visual Studio Code)

Sigue estos pasos para abrir y servir el proyecto con la extensión Live Server:

1. Abre la carpeta del proyecto en VS Code:

   - Menú: File > Open Folder... y selecciona la carpeta que contiene `index.html`.
   - O desde la terminal (si tienes el comando `code` disponible):

```bash
code .
```

2. Instala la extensión Live Server (si aún no la tienes):

   - Abre el panel de Extensiones (icono de cuadrados en la barra lateral) y busca "Live Server" (autor: Ritwick Dey).
   - O instala desde la línea de comandos de VS Code (opcional):

```bash
code --install-extension ritwickdey.LiveServer
```

3. Abre el archivo `index.html` en el editor y lanza Live Server:

   - Haz clic derecho sobre `index.html` y selecciona "Open with Live Server".
   - O usa el botón "Go Live" en la barra de estado (abajo a la derecha).
   - También puedes abrir la paleta de comandos (Ctrl+Shift+P) y ejecutar: "Live Server: Open with Live Server".
   - Atajo: Alt+L, Alt+O (puede variar según tu sistema y configuración).

4. Live Server abrirá tu navegador por defecto en una URL local, típicamente:

```
http://127.0.0.1:5500/index.html
```

5. Para detener el servidor, haz clic en el botón "Port: 5500" en la barra de estado y selecciona "Stop Live Server", o cierra la ventana del servidor desde la paleta de comandos.
# parcial1Prog3
