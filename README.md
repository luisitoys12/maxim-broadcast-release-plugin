# Maxim Broadcast - OBS Studio Plugin & Playout Control Room

¡Bienvenido a **Maxim Broadcast**! Esta es una versión optimizada de código abierto basada en el popular plugin StreamFX para OBS Studio 32, diseñada para flujos de trabajo profesionales de televisión, transmisiones y control de emisión en vivo.

## Contenido del Repositorio

Este repositorio contiene las compilaciones finales de producción listas para ser utilizadas:
1. **`MaximBroadcast-Setup.exe`**: Instalador inteligente todo-en-uno que configurará el plugin en tu OBS Studio y creará accesos directos.
2. **`MaximPlayout.exe`**: La aplicación de control de emisión y reproducción de listas de clips compatible con OBS WebSocket.
3. **`media/`**: Recursos visuales de identidad de la marca.

## Características Principales

*   **Filtros Nativos de TV (y StreamFX):** Efectos avanzados integrados con StreamFX v1.0.0 Beta 750 para OBS 32.0.1, con correcciones para evitar filtros duplicados visuales, señales de attach/detach y transformaciones 3D.
*   **Sin Crashes al Iniciar:** Totalmente compatible y probado con OBS Studio 32.1.2.
*   **Totalmente de Código Abierto:** Integra un menú de acceso rápido en OBS que te lleva al repositorio principal de desarrollo.
*   **Generador de Caracteres y Zócalos:** Control interactivo de logos en pantalla y texto marquesina dinámico (Ticker) desde la mesa de control.
*   **Generador de Gráficos de Redes:** Widget para insertar cintillos en tiempo real, tercios inferiores interactivos y visualización de chat en pantalla.
*   **Control Total Remoto:** Cambia de escena, silencia tus micrófonos y dispara efectos de sonido rápidos directamente desde tu móvil.
*   **Efectos y Cancelación de Ruido Inteligente:** Algoritmos de filtrado nativos para remoción de eco acústico y ruidos de fondo no deseados.
*   **Detección Inteligente NDI / SRT:** Búsqueda automática de cámaras de teléfonos celulares en la red y auto-configuración de fuentes, con soporte para Adobe Premiere Pro o After Effects mediante el plugin especial *Maxim to OBS*.
*   **Maxim Flashback (Noticias con IA):** Generación automática de boletines de noticias interactivos y flashbacks con voces de Microsoft TTS gratuitas y otros motores locales.

## Instalación Rápida

1. Descarga y ejecuta el archivo **`MaximBroadcast-Setup.exe`**.
2. Asegúrate de tener OBS Studio cerrado durante la instalación.
3. El instalador detectará automáticamente tu directorio de OBS Studio (ProgramData o AppData) y copiará todos los archivos necesarios.
4. Al finalizar, tendrás un acceso directo a **Maxim Playout** en tu Escritorio listo para operar.

## Requisitos
*   OBS Studio 32.x
*   WebSocket de OBS habilitado (Herramientas -> Configuración del servidor WebSocket en OBS)

---
*Desarrollado para Maxim TV. ¡Somos open source!*
