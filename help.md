# Mega Man X Online: Deathmatch - Guía de Ayuda / Help Guide

Guía rápida para configurar servidores por IP e instalar mapas personalizados en la versión Flatpak.

---

## 1. Ubicación de los archivos del juego / Game Files Location

Debido al aislamiento del sandbox de Flatpak, todos los archivos configurables del juego se encuentran en la carpeta del contenedor:

`~/.var/app/org.mmxod.MMXOD/data/mmxod/`

> **Nota:** La carpeta `.var` está en tu directorio personal. Si usas un navegador de archivos gráfico, presiona **Ctrl + H** para mostrar las carpetas ocultas.

---

## 2. Conectarse a un Servidor por IP (`region.txt`)

Para cambiar de servidor o conectarte a una IP personalizada (método oficial de gamemaker19):

1. Abre tu gestor de archivos y navega a la ruta:  
   `~/.var/app/org.mmxod.MMXOD/data/mmxod/`
2. Busca el archivo `region.txt` y ábrelo con un editor de texto.
3. Reemplaza la dirección por la IP o dominio del servidor al que deseas conectarte.
4. Guarda el archivo y reinicia el juego.

---

## 3. Agregar Mapas Personalizados (`maps_custom`)

Para instalar escenarios creados por la comunidad:

1. Descarga los archivos del mapa personalizado.
2. Abre la carpeta de mapas en la siguiente ruta:  
   `~/.var/app/org.mmxod.MMXOD/data/mmxod/assets/maps_custom/`
   *(Si la carpeta `maps_custom` no existe, créala dentro de `assets`).*
3. Copia los archivos del mapa dentro de esa carpeta.
4. Inicia el juego; los nuevos escenarios aparecerán en el menú de selección.
