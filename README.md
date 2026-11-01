# 🎲 Rubik Studio 3D • Simulador y Extracción de Piezas

Un simulador interactivo y realista en 3D de un Cubo de Rubik 3x3 construido con **Three.js**, **GSAP** y **Tailwind CSS**. Permite interactuar con el cubo, rotar capas con notación oficial, y desmontar / extraer físicamente **la pieza exacta que seleccionaste** con animaciones fluidas, efectos de sonido sintetizados y visualización en tiempo real.

---

## ✨ Características Principales

- 🎯 **Extracción Exacta de Piezas**: Pasa el cursor sobre cualquier pieza para ver el contorno iluminado en tiempo real y su clasificación exacta (Esquinas, Aristas o Centros). Al hacer clic, **sale exactamente la pieza seleccionada** sin fallos ni desplazamientos aleatorios.
- 🔁 **Reintegración Suave**: Devuelve piezas individuales al cubo haciendo clic sobre ellas en el espacio 3D, desde el panel lateral, o regresa todas juntas con un solo botón.
- 🔄 **Giro de Capas Robusto**: Rotación de caras F, B, U, D, L, R (horario y antihorario) con notación oficial del cubo de Rubik, manteniendo la alineación matemática perfecta y sin desfase de coordenadas.
- 🔀 **Mezclador Aleatorio**: Algoritmo de desordenamiento paso a paso con secuencias realistas.
- 🔊 **Efectos de Sonido con Web Audio API**: Sonidos sintetizados procedurales de giros mecánicos, extracción (pop) y encastre (snap), sin descargas pesadas y con botón de silenciar.
- 🎨 **Estilo Realista**: Stickers con esquinas redondeadas generados por canvas procedural, plástico negro mate tipo ABS y reflejos luminosos.
- 📱 **100% Responsive y Desplegable en Vercel**: Compatible con navegadores de escritorio (Brave, Chrome, Safari, Edge, Firefox) y dispositivos móviles.

---

## ⌨️ Controles y Atajos de Teclado

| Tecla | Acción |
| :--- | :--- |
| **Clic izquierdo** | Extraer pieza (Modo Extraer) o devolver pieza extraída |
| **Clic + Arrastrar** | Rotar vista y orbitar cámara 3D |
| **Scroll / Rueda** | Acercar / Alejar zoom |
| **Barra Espaciadora** | Alternar entre Modo *Extraer Pieza* y Modo *Girar Caras* |
| `F`, `B`, `U`, `D`, `L`, `R` | Girar capa correspondiente en sentido horario |
| `Shift` + `F`, `B`, `U`, `D`, `L`, `R` | Girar capa en sentido antihorario (F', B', etc.) |
| `S` | Mezclar el cubo aleatoriamente |

---

## 🛠️ Tecnologías

- **Three.js (r128)**: Renderizado 3D WebGL, iluminación, sombras y raycasting preciso.
- **GSAP (3.12)**: Animaciones e interpolaciones cinemáticas suaves.
- **Tailwind CSS**: Interfaz moderna con paneles translúcidos (Glassmorphism).
- **Web Audio API**: Efectos de sonido procedurales sin dependencias externas.