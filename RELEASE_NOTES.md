# Release Notes — Maxim Broadcast & Maxim FX

## v2.5.0 — Novedades y Control Inteligente 🚀

**Fecha:** Junio 2026  
**Tipo:** Feature Release  

Esta versión introduce grandes mejoras de interactividad, control remoto móvil, calidad de audio y automatización de red en la suite Maxim Broadcast y Maxim FX.

---

### 🆕 Novedades Principales

#### 1. Generador de Gráficos de Redes
*   **Widget en Tiempo Real:** Permite insertar cintillos y tercios inferiores interactivos directamente sobre tus fuentes de OBS.
*   **Interacción en Pantalla:** Visualización y moderación de chat en pantalla para involucrar a tu audiencia en tiempo real.
*   **Editor Web:** Diseña y exporta gráficos animados listos para OBS desde tu navegador.

#### 2. Control Total Remoto
*   **Control Móvil Activo:** Cambia de escenas, silencia tus micrófonos y ajusta niveles de audio directamente desde tu celular.
*   **Efectos de Sonido Rápidos:** Dispara efectos pregrabados a tu mezcladora de audio principal con un solo toque desde tu dispositivo móvil.
*   **Sin Consumo de Recursos:** No requiere paneles locales pesados; el WebSocket nativo optimiza la velocidad de respuesta.

#### 3. Efectos y Cancelación de Ruido Inteligente
*   **Cancelación de Eco Acústico (AEC):** Algoritmos nativos de filtrado acústico para transmisiones limpias y sin retornos de audio.
*   **Filtro de Ruido de Fondo:** Remueve ruidos no deseados (ventiladores, ruidos ambientales, clics de teclado) con un bajo consumo de CPU.
*   **Integración Nativa C++:** Procesamiento de audio optimizado de baja latencia directo en el motor de OBS.

#### 4. Detección Inteligente NDI / SRT
*   **Auto-configuración de Red:** Búsqueda automática de cámaras de teléfonos celulares en la red local y auto-configuración de fuentes en OBS.
*   **Plugin "Maxim to OBS" para Adobe:** Envía contenido en vivo directamente desde Adobe Premiere Pro y After Effects con un plugin dedicado de alta velocidad.
*   **Estabilidad de Señal:** Protocolos SRT nativos con corrección de errores de transmisión en redes inalámbricas.

---

### 📥 Descargas y Actualización

| Componente | Archivo | Plataforma |
|------------|---------|------------|
| Suite Todo-en-Uno | `MaximBroadcast-Setup.exe` | Windows 10 / 11 (64-bit) |
| Editor Gráfico Visual | `MaximEditor.exe` | Windows 10 / 11 (64-bit) |
| Playout de Transmisión | `MaximPlayout.exe` | Windows 10 / 11 (64-bit) |

### ⚙️ Instalación Rápida
1. Asegúrate de cerrar OBS Studio por completo.
2. Ejecuta `MaximBroadcast-Setup.exe` como Administrador.
3. Sigue el asistente de instalación visual.
4. Abre OBS Studio y verifica que los filtros y el menú superior estén correctamente activados.
5. Inicia `MaximPlayout.exe` o accede al panel remoto para verificar el control móvil.
