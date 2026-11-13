# Plan Clínico Biomecánico L5-S1 | Usuario

Aplicación web interactiva (PWA) de rehabilitación biomecánica, control postural, guía por voz y registro de cargas para **Anterolistesis L5-S1, Protrusión Discal Central y Hernia Lateroforaminal Derecha**.

## Características Principales
- **16 Animaciones Biomecánicas HD en Canvas 2D**:
  - **Modo Rayos-X de Columna Vertebral** (visualización de vértebras y alineación del segmento L5-S1 en tiempo real).
  - Siluetas musculares anatómicas con resaltado térmico de los músculos diana (transverso abdominal, glúteo medio/mayor, psoas, oblicuos).
  - Etiquetas flotantes (*callouts* clínicos), vectores de tracción/fuerza, indicador de respiración (`INHALA` / `EXHALA` / `HOLD`) y barra de fase en vivo.
- **Periodización Inteligente por Fases**:
  - Selector superior de modo diario: *Día Estándar*, *Post-Moto / Descarga*, *Consolidación Fuerza* y *Pre-Trekking*.
- **Modo Rutina Guiada por Voz (Manos Libres)**:
  - Asistente por síntesis de voz (`SpeechSynthesis API`) que guía paso a paso toda la rutina de casa y marca las series automáticamente.
- **Control de Cargas de Gimnasio + Diario del Semáforo Clínico**:
  - Registro persistente en `localStorage` de pesos (`kg`) en cada ejercicio de fuerza, check-in matutino del estado L5-S1 (🟢 Verde / 🟡 Amarilla / 🔴 Roja) y exportación/importación en JSON.
- **PWA Instalable + Pantalla Siempre Encendida (`Screen Wake Lock API`)**:
  - Incluye `manifest.json`, icono vectorial `icon.svg` y `sw.js` para uso desde el móvil.
