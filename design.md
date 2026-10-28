# Especificaciones del Diseño Estético (Design System Prompting for AI)

Este documento define la guía de estilo y el sistema de diseño del proyecto para ser interpretado por agentes de IA en el mantenimiento y evolución del sitio web.

## 1. Filosofía de Diseño
- **Estilo**: Minimalista, limpio, premium y orientado al producto (Inspiración en **Apple.com**).
- **Enfoque de Maquetación**: Layouts modernos con **Flexbox** como pilar estructural primario.
- **Jerarquía Visual**: Espacios en blanco amplios, tipografía clara con diferentes pesos y sombras suaves para profundidad.

## 2. Sistema de Colores
- **Color Principal (Acción/Branding)**: `#0071e3` (Azul eléctrico Tech)
- **Fondo de Sitio**: `#f5f5f7` (Gris claro de tono neutro)
- **Superficies / Cards**: `#ffffff` (Blanco puro)
- **Texto Principal**: `#1d1d1f` (Gris casi negro para alto contraste sin ser agresivo)
- **Texto Secundario**: `#86868b` (Gris medio)
- **Pie de página**: `#161617` (Oscuro profundo)

## 3. Tipografía
- **Familia**: `'Inter'`, sans-serif vía Google Fonts.
- **Escala de Fuentes**:
  - Título Hero: `3.5rem` (Bold, 700)
  - Títulos de Sección (`h2`): `2rem` (SemiBold, 600)
  - Títulos de Artículos (`h3`): `1.4rem` (SemiBold, 600)
  - Cuerpo de texto (`p`): `0.95rem` a `1rem` (Regular, 400)

## 4. Estructura y Dimensiones
- **Contenedor Principal**:
  - Ancho Mínimo: `1000px`
  - Ancho Máximo: `2000px`
- **Uso de Unidades**:
  - **Absolutas (`px`)**: Dimensiones de contenedor general, alturas de header fijo, tamaños de iconos fijos.
  - **Relativas (`rem`, `%`, `em`)**: Margen interior, espaciados entre elementos internos de cards y tamaños tipográficos.

## 5. Directivas de Usabilidad e Accesibilidad
- **Imágenes**: Todas las imágenes deben incluir explícitamente el atributo `alt` descriptivo.
- **Componentes Fijos**: El botón de soporte/chat flotante usa `position: fixed` en la esquina inferior derecha (`bottom: 30px; right: 30px;`).
- **Navegación**: Menú con estados `:hover` e interacción en desplegables.

---
*Prompt de instrucción para la IA*:
> "Mantén siempre la coherencia del diseño siguiendo las variables del archivo CSS (`:root`), asegurando que cualquier nuevo componente implemente Flexbox, mantenga el rango de ancho entre 1000px y 2000px y preserve la usabilidad y la estética minimalista descrita en este documento."