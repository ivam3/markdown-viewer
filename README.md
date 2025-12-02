# Visor de Markdown (Markdown Viewer)

![Logo de la aplicación](markdown_viewer_app/src/assets/logo-IbyC-circulo.png)

## Descripción General

**Markdown Viewer** es una aplicación ligera diseñada para visualizar archivos de texto Markdown (`.md`). Desarrollada completamente en Python utilizando el módulo `flet`, esta herramienta fue concebida para funcionar eficientemente en entornos móviles, particularmente en el sistema operativo Android a través del emulador de terminal Termux.

La motivación principal para su creación surgió de la necesidad de un visor de Markdown nativo y funcional directamente en Termux, un entorno donde las soluciones existentes eran limitadas o inexistentes.

## Características

*   **Visualización de Markdown:** Renderiza archivos `.md` de forma limpia y legible.
*   **Diseño Responsivo:** Interfaz adaptada para diferentes tamaños de pantalla, ideal para dispositivos móviles.
*   **Integración con Termux:** Optimizado para un rendimiento fluido en el ecosistema Termux.
*   **Desarrollado en Python/Flet:** Utiliza una pila tecnológica moderna que permite un desarrollo rápido y una interfaz de usuario atractiva.

## Instalación

### Requisitos

*   Python 3.x
*   PIP (Administrador de paquetes de Python)
*   Termux (si se instala en Android)
*   Módulo `flet`

### Pasos de Instalación (para Termux/Android)

1.  **Actualizar Termux:**
    ```bash
    pkg update && pkg upgrade
    ```

2.  **Instalar Python y PIP:**
    ```bash
    pkg install python python-pip
    ```

3.  **Clonar el Repositorio:**
    ```bash
    git clone https://github.com/tu_usuario/markdown-viewer.git
    cd markdown-viewer
    ```
    (Nota: Reemplaza `https://github.com/tu_usuario/markdown-viewer.git` con la URL real de tu repositorio si es diferente.)

4.  **Instalar Dependencias:**
    ```bash
    pip install -r markdown_viewer_app/requirements.txt
    ```

## Uso

Para iniciar la aplicación, navega hasta el directorio `markdown_viewer_app` y ejecuta el script `main.py`:

```bash
cd markdown_viewer_app/src
python main.py
```

La aplicación se abrirá, permitiéndote navegar y visualizar tus archivos Markdown.

## Contribuciones

Las contribuciones son bienvenidas. Si tienes sugerencias, mejoras o encuentras algún error, no dudes en abrir un "issue" o enviar un "pull request" en el repositorio de GitHub.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

**Desarrollado con ❤️ por IbyC Hacklab**