---
name: axiopri-document-styling
description: >-
  Estiliza y genera informes académicos y corporativos de AxioPri S.A.S BIC bajo la identidad visual llanera-tech, estructurando las salidas en formatos compatibles con Google Docs y Microsoft Word para edición inmediata.
---

# AxioPri Document Styling Skill

## Overview
Esta skill habilita a la IA para redactar, diseñar y dar formato de manera automática a cualquier informe técnico, entrega universitaria (para la Universidad La Gran Colombia) o documento corporativo de **AxioPri S.A.S BIC**, plasmando fielmente su ADN llanero-tech.

La skill está optimizada para que los resultados generados puedan ser importados o copiados directamente en **Google Docs o Microsoft Word** sin perder su formato, sus colores corporativos, sus fuentes ni su estructura.

---

## 1. Brand Visual Tokens (Valores de Marca / Brand Colors)

La IA debe inyectar de manera obligatoria los siguientes parámetros estéticos en el formato de cualquier documento:

*   **Paleta de Colores Llaneros (Brand Palette):**
    *   **Verde Moriche (Primary / Verde Esmeralda):** `#1F8C4E` (RGB: `31, 140, 78`) — Usado para títulos principales, acentos y bordes de tablas.
    *   **Dorado Llanero (Secondary / Gold / Dorado / Acento):** `#C8A94C` (RGB: `200, 169, 76`) — Usado para subtítulos, resaltados, detalles premium y decoraciones de marca.
    *   **Naranja Ocaso (Alert / Naranja / Acción):** `#E06A3B` (RGB: `224, 106, 59`) — Usado para destacados, llamadas de atención y notas críticas.
    *   **Gris Lino (Light Background / Fondo de Lectura):** `#F4F6F4` (RGB: `244, 246, 244`) — Fondo sutil para bloques y tablas.
    *   **Verde Carbón (Dark Typography / Color de Texto):** `#121714` (RGB: `18, 23, 20`) — Color de texto primario (negro suavizado muy elegante).
*   **Tipografía Sugerida:**
    *   **Títulos:** Outfit o Arial (Negrita).
    *   **Cuerpo:** Inter o Arial (Regular).
*   **Lema Corporativo (Footer):**
    *   *"Infraestructura que piensa. Ingeniería estratégica desde el Meta."*

---

## 2. Formato de Salida Compatible con Google Docs y Word

Para garantizar que el usuario pueda editar y trabajar el documento directamente en **Google Docs o Microsoft Word**, la IA debe estructurar el resultado bajo dos modalidades de salida según lo solicite el usuario:

### Método A: Salida en HTML Estilizado Inline (Recomendado para Máxima Fidelidad)
El formato HTML estructurado con estilos CSS en línea (*inline*) es el método más potente, ya que tanto MS Word como Google Docs lo leen de forma nativa. Al copiar el código HTML renderizado (o guardarlo como archivo `.html` y abrirlo en Word/Docs), se conservan exactamente todos los colores, márgenes, bordes y fuentes.

**Reglas de Formateo HTML:**
*   Usar un contenedor principal con tipografía Arial, interlineado de `1.5`, márgenes y un color de texto `#121714` para el cuerpo.
*   Los títulos `<h1>` deben llevar estilos inline: `color: #1F8C4E; font-family: Arial, sans-serif; font-size: 24pt; border-bottom: 2px solid #C8A94C; padding-bottom: 4px; margin-top: 20px;`.
*   Los subtítulos `<h2>` deben llevar estilos inline: `color: #C8A94C; font-family: Arial, sans-serif; font-size: 16pt; margin-top: 15px;`.
*   Los apartados `<h3>` deben llevar estilos inline: `color: #E06A3B; font-family: Arial, sans-serif; font-size: 13pt; margin-top: 12px;`.
*   Los bloques de notas/destacados deben estructurarse como `blockquote` con: `border-left: 4px solid #C8A94C; background-color: #F4F6F4; padding: 12px; margin: 15px 0; border-radius: 0 8px 8px 0;`.
*   Las tablas deben formatearse con estilos explícitos: `border-collapse: collapse; width: 100%;`. El encabezado `<th>` debe llevar `background-color: #1F8C4E; color: #FFFFFF; padding: 8px; border: 1px solid #C8A94C;`. Las filas de datos `<td>` deben llevar `padding: 8px; border: 1px solid #DDDDDD;` alternando fondos suaves `#F4F6F4` para filas pares.

### Método B: Salida en Markdown Limpio (Para Copia Rápida)
Ideal para copiar y pegar en editores que soporten Markdown (como el propio Google Docs con la extensión Markdown o en editores de código).
*   Usar `#` para títulos principales y `##` para secundarios.
*   Estructurar las tablas usando la sintaxis estándar de Markdown.
*   Utilizar bloques de cita `>` para notas importantes e identificar los acentos de color mediante descripciones de texto o etiquetas sutiles.

---

## 3. Estructura de Documento Académico/Corporativo AxioPri

Al invocar esta skill para redactar un informe o trabajo universitario para la **Universidad La Gran Colombia**, la IA estructurará el contenido con la siguiente arquitectura:

1.  **Portada Estilizada:**
    *   Alineado a la derecha: `UNIVERSIDAD LA GRAN COLOMBIA` (Académico) o `AXIOPRI S.A.S BIC` (Corporativo).
    *   Título del documento en tamaño grande (Verde Moriche).
    *   Subtítulo del documento (Dorado Llanero / Gold).
    *   Bloque de metadatos:
        *   **Autor:** Juan Pablo Velásquez Prieto (CEO & Fundador)
        *   **Origen:** Villavicencio, Meta (Orinoquia)
        *   **Área de Trabajo:** [Área académica o consultoría del proyecto]
        *   **Fecha:** [Mes] [Año]
2.  **Tabla de Contenido / Introducción**
3.  **Cuerpo del Informe:** Desarrollado con secciones claras (`h2` y `h3`), tablas de datos con el diseño de la paleta y bloques destacados para notas de campo y geotecnia.
4.  **Conclusiones e Impacto Sostenible (Capa BIC):** Una sección obligatoria que describe cómo el proyecto o temática se alinea con la sostenibilidad, la descarbonización, el impacto social regional en el Meta o la transformación digital.
5.  **Pie de Página (Footer):** En cursiva y centrado: *"Infraestructura que piensa. Ingeniería estratégica desde el Meta."*

---

## 4. Tono de Comunicación (La Voz del Meta)

La redacción de los informes debe fusionar:
*   **El Sabio e Innovador:** Rigor técnico de ingeniería civil, metodologías BIM (NTC-ISO 19650) y optimización algorítmica de Inteligencia Artificial.
*   **La Calidez y Resistencia del Llano:** Expresiones de comunicación claras, honestas, con un profundo arraigo territorial y respeto al entorno natural de la Orinoquia colombiana.

---

## 5. Ejemplos de Invocación y Casos de Uso

### Caso 1: Redactar un Informe de Universidad
*   *Usuario:* `/axiopri-document-styling Redacta un informe técnico sobre la dinámica de suelos y geología aplicada en las sabanas del departamento del Meta para mi materia de Geotecnia.`
*   *Comportamiento de la IA:* La IA leerá esta skill, generará el informe estructurando la portada de la Universidad La Gran Colombia, la introducción, el desarrollo técnico y la capa BIC, entregando el código HTML estilizado en línea listo para ser copiado en Microsoft Word o Google Docs.

### Caso 2: Estructurar un Documento Corporativo
*   *Usuario:* `/axiopri-document-styling Genera una propuesta técnica de servicios de consultoría de auditoría automatizada de metrados para un cliente constructor en Villavicencio.`
*   *Comportamiento de la IA:* Aplicará el tono corporativo de AxioPri, mantendrá el perfil Asset-Light, formateará la propuesta con la paleta de colores Verde Moriche y Dorado / Gold, e inyectará el lema en el pie de página, presentándolo en HTML editable.
