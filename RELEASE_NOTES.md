# Release Notes — Maxim Broadcast & Maxim FX

## v2.6.0 — Maxim Flashback & StreamFX Integration 🚀

**Fecha:** Junio 2026  
**Tipo:** Feature Release  

Esta versión introduce grandes mejoras de interactividad y estabilidad en Maxim Broadcast y Maxim FX, destacando el nuevo componente **Maxim Flashback (Noticias con IA)** y la integración completa de **StreamFX v1.0.0 Beta 750 (para OBS Studio 32.0.1)**.

---

### 🆕 Novedades Principales

#### 1. Maxim Flashback (Noticias con IA)
*   **Boletines Automatizados:** Genera flashbacks y boletines de noticias interactivos directamente para OBS Studio usando las voces de Microsoft IA gratis (TTS) y otros motores locales.
*   **Controles de Audio y BGM:** Configura faders de volumen, música de fondo de jingles informativos o ritmos cyberpunk, y haz preescuchas al instante desde el editor web.
*   **Enlaces de Audio OBS:** Copia y pega un enlace de red directo para OBS Studio que emitirá la locución generada al instante.

#### 2. Integración StreamFX v1.0.0 Beta 750
*   **Corrección de Regresión (Filtros Duplicados):** Se soluciona el error de la versión 1.0.0b721 que provocaba que los filtros visuales se duplicaran al agregarlos de nuevo, debido a la activación de señales en el origen incorrecto.
*   **Renombrado de Señales Core:** Las señales internas personalizadas de `filter_add` y `filter_remove` han sido renombradas a `attach` y `detach` para modularidad.
*   **Actualización de Requisitos:** Compatibilidad total con OBS Studio 32.0.1+ en Windows 10/11, Ubuntu 24.04+ y macOS 15.0+.
*   **Notas sobre Funciones:** 
    *   La función Blur ahora carece de enmascaramiento dinámico (Dynamic Mask maneja esto con mayor eficiencia).
    *   NVIDIA Maxine requiere una GPU Tensor compatible y redistribuibles de SDK.
    *   Problemas conocidos: la recursión en Spout/Sink está rota; las entradas de textura en Shaders requieren migración; error de pixel format en pantallas verdes virtuales en ciertos sistemas.

#### 3. Generador de Gráficos de Redes
*   **Widget en Tiempo Real:** Permite insertar cintillos y tercios inferiores interactivos directamente sobre tus fuentes de OBS.
*   **Interacción en Pantalla:** Visualización y moderación de chat en pantalla para involucrar a tu audiencia en tiempo real.
*   **Editor Web:** Diseña y exporta gráficos animados listos para OBS desde tu navegador.

#### 4. Control Total Remoto
*   **Control Móvil Activo:** Cambia de escenas, silencia tus micrófonos y ajusta niveles de audio directamente desde tu celular.
*   **Efectos de Sonido Rápidos:** Dispara efectos pregrabados a tu mezcladora de audio principal con un solo toque desde tu dispositivo móvil.

#### 5. Efectos y Cancelación de Ruido Inteligente
*   **Cancelación de Eco Acústico (AEC):** Algoritmos nativos de filtrado acústico para transmisiones limpias y sin retornos de audio.
*   **Filtro de Ruido de Fondo:** Remueve ruidos no deseados (ventiladores, ruidos ambientales, clics de teclado) con un bajo consumo de CPU.

#### 6. Detección Inteligente NDI / SRT
*   **Auto-configuración de Red:** Búsqueda automática de cámaras de teléfonos celulares en la red local y auto-configuración de fuentes en OBS.
*   **Plugin "Maxim to OBS" para Adobe:** Envía contenido en vivo directamente desde Adobe Premiere Pro y After Effects con un plugin dedicado de alta velocidad.

---

### 📥 Descargas y Actualización

| Componente | Archivo | Plataforma |
|------------|---------|------------|
| Suite Todo-en-Uno | `MaximBroadcast-Setup.exe` | Windows 10 / 11 (64-bit) |
| Editor Gráfico Visual | `MaximEditor.exe` | Windows 10 / 11 (64-bit) |
| Playout de Transmisión | `MaximPlayout.exe` | Windows 10 / 11 (64-bit) |
| Generador de Flashback | `MaximFlashback.exe` | Windows 10 / 11 (64-bit) |

### ⚙️ Instalación Rápida
1. Asegúrate de cerrar OBS Studio por completo.
2. Ejecuta `MaximBroadcast-Setup.exe` como Administrador.
3. Sigue el asistente de instalación visual.
4. Abre OBS Studio y verifica que los filtros y el menú superior estén correctamente activados.
5. Inicia `MaximPlayout.exe` o accede al panel remoto para verificar el control móvil.
