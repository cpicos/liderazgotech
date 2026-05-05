# BLOG_STRUCTURE.MD | Ingeniería Inversa: LiderazgoTech

## 1. Stack de Componentes Base
Para cada artículo, se deben importar y utilizar obligatoriamente:
- **Layout:** `../../layouts/Layout.astro`
- **Header:** `../../components/Header.astro`
- **Footer:** `../../components/Footer.astro`

## 2. Esquema de Metadatos (Props del Layout)
El componente `<Layout />` requiere:
- `title`: String format -> "LiderazgoTech | [Título del Post]"
- `metaDescription`: Resumen técnico orientado a SEO.

## 3. Anatomía del Hero Section (Cabecera)
Estructura visual de alto impacto con fondo `#1A1A1A` y panel de datos `#FFCC00`:
- **Categoría:** Badge superior (ej. "PROTOCOLO DE RED").
- **Referencia:** Código único (ej. "REF: LT-2024-INFRA").
- **H1:** Texto en mayúsculas, clase `font-headline-xl`, tracking-tighter.
- **Grid de Datos (4 columnas):**
    1. **FECHA:** Formato MMM DD, YYYY.
    2. **AUTOR:** Nombre del ingeniero.
    3. **ESTADO:** Generalmente "PUBLICADO".
    4. **LEER:** Tiempo estimado (ej. "12 MIN").
- **Imagen:** Filtro `grayscale`, objeto `cover`, relación de aspecto responsiva.

## 4. Cuerpo del Artículo (Grid System)
El contenido se divide en un grid de 12 columnas:
- **Sidebar (3 cols):** 
    - Tabla de contenidos con enlaces anclados (`#id`).
    - Widget de "Herramientas recomendadas" (Fondo `#1A1A1A`, texto `#FFCC00`).
- **Main Content (9 cols):**
    - **H2:** Numerados (01., 02., etc.), `font-black uppercase`.
    - **Párrafos:** Clase `font-serif` o `font-slab` para legibilidad técnica.
    - **Quote Block:** Fondo `#FFCC00`, borde `#1A1A1A`, con icono de material "terminal".
    - **Listas:** Items con número en fondo negro.

## 5. Visuales Técnicos (Placeholder)
Cada artículo debe incluir al menos un `industrial-border` que contenga:
- Título de figura (ej. "FIG. 04-A").
- Icono de Material Symbols.
- Un contenedor de diagrama con borde discontinuo (`border-dashed`).

## 6. Documentación Relacionada (Footer Section)
Sección final con fondo `#1A1A1A`:
- Grid de 3 columnas para "Cards" relacionadas.
- Cada card incluye: Categoría (amarillo), Título (blanco/mayúsculas), Link "ACCEDER" con flecha.

## 7. Reglas de Estilo (Tailwind)
- **Colores primarios:** `#FFCC00` (Industrial Yellow), `#1A1A1A` (Deep Black).
- **Tipografías:** `font-key-concept`, `font-headline-xl`, `font-label`.