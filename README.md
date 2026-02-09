# 🎵 MetaLyrics Pro - Buscador de Letras

**MetaLyrics Pro** es una aplicación web desarrollada con **Python y Flask** que permite buscar letras de canciones de forma inteligente, extrayendo metadatos directamente de archivos de audio.

## 🚀 Características
* **Extracción de Metadatos:** Utiliza la librería `mutagen` para leer etiquetas ID3 (Artista y Título) de archivos subidos.
* **Búsqueda Automática:** Conecta con APIs de letras para mostrar resultados al instante.
* **Interfaz Dinámica:** Diseñada con HTML5, CSS3 y JavaScript para una experiencia fluida.
* **Despliegue Continuo:** Configurada para actualizarse automáticamente mediante Git y Render.

## 🛠️ Tecnologías utilizadas
* **Backend:** Python 3.x, Flask, Gunicorn.
* **Procesamiento:** Mutagen (Metadata extraction).
* **Frontend:** Jinja2, CSS Custom Properties, Vanilla JS.

## 📦 Instalación local
1. Clona el repositorio:
   `git clone https://github.com/faylwin/Metalyrics-Web.git`
2. Instala las dependencias:
   `pip install -r requirements.txt`
3. Ejecuta la app:
   `python app.py`

---
Desarrollado por [faylwin](https://github.com/faylwin) - 2026
