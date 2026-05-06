# 🛠️ BLOG BLUEPRINT: Generador de Artículos Técnicos

## 1. Entrada de Datos (User Input)
> [!IMPORTANT]
> Pega aquí tus notas, audios transcritos o puntos clave. No importa el orden, la IA se encargará de la estructura.

**TEXTO EN BRUTO:**
Como volverte visible y generar oportunidades
Problema: Expertos invisibles, conocen de todo pero nadie los ubica para tomar decisiones.
Enseñanza: Agente de cambio, tecnología a negocio, posicionamiento dentro de la empresa, autoridad.
Ideal para: Ingenieros de sistemas, analistas de datos, project managers
Autor: Ing. Christian Picos

---

## 2. Instrucciones de Procesamiento (Para la IA)
Al recibir este archivo, debes actuar como un **Senior Content Engineer** y realizar las siguientes tareas:

1.  **Analizar el contenido:** Identifica el tema central y los puntos técnicos clave.
2.  **Generar Metadatos:** 
    - Crea un `title` de alto impacto siguiendo el estilo "LiderazgoTech".
    - Genera una `metaDescription` de máximo 160 caracteres.
    - Asigna una referencia única (ej. `REF: LT-2026-X`).
3.  **Estructurar el Artículo:**
    - Crea 3 o 4 secciones numeradas (01, 02, 03...).
    - Extrae una frase potente para el `TECHNICAL INSIGHT` (Quote Block).
    - Crea la tabla de contenidos para la Sidebar.
4.  **Generar el Código:** Devuelve el código completo en un bloque de código compatible con **Astro**.

## 3. Especificaciones Técnicas (Referencia)
- **Layout de referencia:** Consultar `@BLOG_STRUCTURE.MD` para clases de Tailwind y componentes.
- **Tono de voz:** Experto, autoritario, orientado a resultados y liderazgo en IT.
- **Componentes obligatorios:** `<Layout>`, `<Header>`, `<Footer>`.
- **Placeholder de Imagen:** Usa una URL de Unsplash relacionada con tecnología industrial o servidores si no se proporciona una.