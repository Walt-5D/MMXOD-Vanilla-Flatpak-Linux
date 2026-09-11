# Mega Man X Online: Deathmatch - Guía de Ayuda / Help Guide

Guía rápida para configurar servidores por IP e instalar mapas personalizados en la versión Flatpak.

---

## 1. Ubicación de los archivos del juego / Game Files Location

Debido al aislamiento del sandbox de Flatpak, los archivos modificables del juego se encuentran en la carpeta de datos de usuario de tu sistema:

`~/.local/share/mmxod/`

> **Nota:** La carpeta `.local` es una carpeta oculta. Para verla en tu explorador de archivos, presiona la combinación de teclas **Ctrl + H**.

---

## 2. Conectarse a un Servidor por IP (`region.txt`)

Para cambiar de servidor o conectarte a una IP personalizada (método oficial de gamemaker19):

1. Abre tu gestor de archivos y navega a la ruta:  
   `~/.local/share/mmxod/`
2. Busca el archivo llamado `region.txt` y ábrelo con un editor de texto (como Gedit, KWrite o Text Editor).
3. Reemplaza el contenido del archivo por la IP o dirección del servidor al que deseas conectarte.
4. Guarda el archivo y ejecuta el juego normalmente.

---

## 3. Agregar Mapas Personalizados / Custom Maps

Para instalar mapas creados por la comunidad:

1. Descarga los archivos del mapa personalizado.
2. Abre la carpeta de mapas del juego en la siguiente ruta:  
   `~/.local/share/mmxod/maps/`
   *(Si la carpeta `maps` no existe dentro de `mmxod`, créala manualmente).*
3. Copia los archivos del mapa descargado dentro de esa carpeta.
4. Inicia el juego; los nuevos escenarios aparecerán en la lista de selección de mapas al crear una partida.
