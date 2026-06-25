# Release Notes — Maxim Broadcast & Maxim FX

## v2.7.0 — App Híbrida Android (APK), Integración Bidireccional Adobe y Nueva Documentación 🚀

**Fecha:** Junio 2026  
**Tipo:** Feature & Release Update  

Esta versión representa el salto definitivo de Maxim Broadcast a ecosistemas nativos. Decimos adiós al editor web interactivo convencional en línea (convertido ahora en un centro oficial de documentación y descargas de alta velocidad) y presentamos la nueva aplicación móvil APK para Android y la suite de integración bidireccional cerrada para Adobe Creative Cloud.

---

### 🆕 Novedades Principales

#### 1. Paneles Nativos C++ en OBS Studio (`maxim-fx`)
*   **Docks Nativos Integrados**: Zócalos de "Playout Remoto" y "Diseñador de Overlays" integrados directamente como paneles nativos Qt dentro de la interfaz de OBS Studio, cargando de forma offline sin depender de ningún navegador.
*   **Editor Nactivo por GPU**: Permite diseñar figuras, textos con brillo de neón, redondeados y degradados con un alto rendimiento de renderizado por hardware local de Qt.

#### 2. Aplicación Móvil Unificada (`MaximRemote.apk`)
*   **Editor e Integración Local**: Incluye el editor gráfico directamente en los recursos de la aplicación, haciéndolo 100% independiente del servidor web, offline y con renderizado acelerado.
*   **Dashboard de Control Premium**: Pantalla de inicio renovada con diseño de alta fidelidad que permite alternar fácilmente entre la mesa de control de Playout (conexión por IP manual o escaneo de código QR) y el Diseñador de Overlays.
*   **UserAgent Nativo**: Inyección de UserAgent `"MaximAndroidApp"` para desactivar el banner web de descarga y optimizar la visualización de capas de texto en pantallas móviles.

#### 3. Extensión de Integración Adobe CEP (`Maxim to OBS`)
*   **Soporte Multiaplicación**: Panel de herramientas compatible con Adobe Premiere Pro, After Effects y Photoshop.
*   **Integración Bidireccional Completa**:
    *   *Marcadores Dinámicos (Timeline Sync)*: Genera marcadores automáticamente en la línea de tiempo activa de Adobe al ocurrir cambios de escena en OBS Studio en vivo.
    *   *Control de Reproducción*: Permite pausar o reproducir la secuencia de Premiere de forma automática mediante triggers de OBS.
    *   *Enviar Fotograma Activo*: Exporta el lienzo de diseño en Photoshop o la composición en After Effects actualizando la fuente de imagen `MaximFrameSource` en OBS de forma instantánea.
*   **Licenciamiento Comercial (Código Cerrado)**: Interfaz de bloqueo integrada. Requiere una clave de licencia en formato `MAXIM-XXXX-XXXX-XXXX` para habilitar las características premium.

#### 4. Centro de Documentación y Descarga (`editor.html` / `index.html`)
*   **Descontinuación del Editor Web**: La dirección tradicional de `editor.html` ha sido reemplazada por una guía interactiva oficial de usuario y manual de instalación de descargas con advertencias de funciones limitadas para navegadores.
*   **Enlaces de Descarga Mejorados**: Migración a URLs directas de tipo `raw` de GitHub para evitar bloqueos y pantallas muertas en dispositivos móviles.

---

### 📥 Descargas y Actualización (v2.7.0)

| Componente | Archivo / Descarga | Plataforma |
|------------|---------|------------|
| Suite Todo-en-Uno (OBS & Playout) | [Descargar (.exe)](https://github.com/luisitoys12/maxim-broadcast-release-plugin/raw/main/MaximBroadcast-Setup.exe) | Windows 10 / 11 (64-bit) |
| App Móvil (Playout & Editor) | [Descargar (.apk)](https://github.com/luisitoys12/maxim-broadcast-release-plugin/raw/main/MaximRemote.apk) | Android (Tablets y Celulares) |
| Editor de Overlays Local | [Descargar (.exe)](https://github.com/luisitoys12/maxim-broadcast-release-plugin/raw/main/MaximEditor.exe) | Windows 10 / 11 (64-bit) |
| Extensión Adobe CEP (Código Cerrado) | [Descargar (.zip)](https://github.com/luisitoys12/maxim-broadcast-release-plugin/raw/main/maxim-to-obs-adobe.zip) | Premiere, AE y Photoshop |

---

### ⚙️ Instalación Rápida de la Extensión
1. Descomprime el archivo `maxim-to-obs-adobe.zip`.
2. Copia la carpeta en: `C:\Program Files (x86)\Common Files\Adobe\CEP\extensions\com.maxim.to.obs`
3. Abre Premiere, After Effects o Photoshop, y ve a **Ventana** -> **Extensiones** -> **Maxim to OBS**.
4. Introduce tu clave de licencia y conéctate al WebSocket de tu OBS Studio (Puerto default `4455`).
5. Activa el timeline sync para inyectar marcadores automáticamente.
