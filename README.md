# Maxim Broadcast — Suite Profesional de Playout, Plugins para OBS y Adobe

¡Bienvenido a **Maxim Broadcast**! Esta es la suite de producción en vivo y automatización televisiva definitiva, optimizada sobre la base del popular plugin StreamFX para OBS Studio 32+. Diseñada para flujos de trabajo profesionales en televisión, radio online, producción en vivo y creadores de contenido avanzados.

---

## 🚀 Componentes de la Suite y Descargas Directas

Este repositorio contiene las compilaciones de producción oficiales listas para su uso. Puedes descargarlas directamente haciendo clic en los siguientes enlaces (parámetro de descarga forzada habilitado para dispositivos móviles):

1.  **[MaximBroadcast-Setup.exe](https://github.com/luisitoys12/maxim-broadcast-release-plugin/raw/main/MaximBroadcast-Setup.exe)**: Instalador inteligente todo-en-uno que configura el plugin nativo en tu OBS Studio (incluyendo los nuevos docks nativos de Playout y Editor) y crea el acceso directo a la estación de Playout.
2.  **[MaximRemote.apk (Android)](https://github.com/luisitoys12/maxim-broadcast-release-plugin/raw/main/MaximRemote.apk)**: Aplicación móvil híbrida para tablets y teléfonos Android que combina la **Mesa de Control Playout** (remota) con el **Diseñador de Overlays** (local y 100% offline).
3.  **[MaximEditor.exe (PC)](https://github.com/luisitoys12/maxim-broadcast-release-plugin/raw/main/MaximEditor.exe)**: Editor gráfico de escritorio para Windows, optimizado localmente para diseñar zócalos y overlays sin consumo de red.
4.  **[Maxim to OBS Extension (Adobe CEP)](https://github.com/luisitoys12/maxim-broadcast-release-plugin/raw/main/maxim-to-obs-adobe.zip)**: Panel de integración bidireccional para **Adobe Premiere Pro, After Effects y Photoshop**. *Nota: Este componente es de código cerrado y requiere clave de licencia comercial.*

---

## 📺 Características Principales

*   **Paneles Nativos C++ en OBS Studio**: Zócalos y paneles (docks) de Playout y Editor integrados directamente en la interfaz de OBS mediante widgets Qt nativos, 100% offline y sin consumo de recursos del navegador.
*   **App Móvil Unificada (APK)**: ¡Dile adiós a la versión web! La aplicación Android te permite conectarte de forma remota a tu playout (mediante IP o escaneo de código QR) y a la vez diseñar zócalos y tercios inferiores de forma offline directamente en tu dispositivo móvil.
*   **Integración Bidireccional OBS ↔ Adobe**: La extensión CEP conecta tus programas de diseño con tu transmisión en vivo mediante WebSocket:
    *   *Marcadores Dinámicos*: Al cambiar de escena en OBS, se inyectan marcadores de forma automática en la línea de tiempo activa de Premiere o After Effects.
    *   *Control de Reproducción*: Controla la reproducción o pausa del proyecto de Adobe directamente desde los triggers de OBS.
    *   *Sincronización de Fotogramas*: Exporta tu lienzo activo y actualiza la fuente de imagen de OBS al instante.
*   **Filtros Nativos de TV (OBS 32+)**: Filtros de vídeo basados en StreamFX v1.0.0 Beta 750 libre de duplicación visual de filtros en las señales de attach/detach y desenfoque optimizado.
*   **Estación Playout & CG**: Control interactivo de logotipos en pantalla, marquesinas móviles (Ticker), widgets de chat y cintillos de redes sociales.
*   **Cancelación de Ruido con IA**: Algoritmos nativos de remoción de eco acústico (AEC) y supresión de ruidos ambientales sin consumo excesivo de CPU.
*   **Maxim Flashback**: Generador de boletines de noticias generativos mediante voces artificiales (TTS de Microsoft gratis).

---

## ⚙️ Guía Rápida de Instalación

### 1. Servidor Playout y Plugin OBS (Windows)
1.  Asegúrate de cerrar OBS Studio por completo.
2.  Ejecuta **`MaximBroadcast-Setup.exe`**. El instalador detectará de forma automática tu carpeta de OBS Studio e instalará los plugins correspondientes.
3.  Al finalizar, inicia la estación **Maxim Playout** desde el acceso directo de tu Escritorio.

### 2. Extensión de Adobe (CEP)
1.  Descomprime el archivo `maxim-to-obs-adobe.zip`.
2.  Copia la carpeta resultante en la ruta de extensiones comunes de tu sistema:
    *   Windows: `C:\Program Files (x86)\Common Files\Adobe\CEP\extensions\com.maxim.to.obs`
3.  Abre Premiere, After Effects o Photoshop, y ve a **Ventana** -> **Extensiones** -> **Maxim to OBS**.
4.  Introduce tu clave de licencia para activar la integración.

---

*Desarrollado para Maxim TV. ¡Apoyamos las transmisiones de alta calidad!*
