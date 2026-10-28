# SSG - Generadores de Sitios Estáticos

## 1. ¿Qué es un SSG?

Un **SSG (Static Site Generator)** es una herramienta que permite crear sitios web estáticos a partir de archivos de contenido y plantillas.

SSG significa *Static Site Generator*, que en español se traduce como *Generador de Sitios Estáticos*.

A diferencia de un CMS dinámico, un SSG genera las páginas web **antes de que sean publicadas**. Normalmente, el contenido se escribe en archivos Markdown y, mediante un proceso de construcción o *build*, se generan archivos HTML que pueden ser publicados en un servidor.

Los sitios generados de esta forma no necesitan consultar una base de datos cada vez que un usuario visita una página.

> Un SSG genera las páginas web durante el proceso de construcción para que puedan ser servidas como archivos estáticos.

### ¿Cómo funciona?

El funcionamiento básico de un SSG puede representarse así:

```text
Contenido en Markdown
          ↓
      Plantillas
          ↓
        SSG
          ↓
    Proceso de build
          ↓
      Archivos HTML
          ↓
     Servidor web
          ↓
       Visitante
```

## 2. Ventajas y desventajas de un SSG

### Ventajas

- **Rendimiento:** las páginas se generan previamente y se sirven como archivos estáticos.
- **Seguridad:** normalmente no necesita una base de datos ni un CMS ejecutándose en el servidor.
- **Simplicidad:** permite escribir el contenido utilizando Markdown.
- **Reutilización:** las plantillas permiten reutilizar elementos como menús, cabeceras y pies de página.
- **Facilidad de alojamiento:** los archivos generados pueden publicarse en servicios de alojamiento de sitios estáticos.

### Desventajas

- **Conocimientos técnicos:** es necesario aprender la herramienta y su estructura.
- **Proceso de construcción:** normalmente es necesario volver a generar el sitio después de realizar cambios.
- **Contenido dinámico:** no es la opción más adecuada para sitios que necesitan funciones muy dinámicas.
- **Configuración inicial:** algunos generadores pueden requerir una configuración inicial.

## 3. Principales generadores de sitios estáticos

En este trabajo se comparan **Jekyll, Hugo y Astro**.

### Jekyll

**Jekyll** es un generador de sitios estáticos desarrollado en **Ruby**. Permite utilizar archivos Markdown y plantillas para generar páginas HTML estáticas.

Es especialmente conocido por su uso en blogs y sitios personales. También puede utilizarse junto con GitHub Pages.

### Hugo

**Hugo** es un generador de sitios estáticos desarrollado en **Go**. Está diseñado para ser muy rápido y permite generar sitios web en poco tiempo.

Permite utilizar Markdown para escribir contenido y plantillas para definir la estructura del sitio.

### Astro

**Astro** es un generador de sitios web orientado principalmente al contenido y al rendimiento. Está basado en **JavaScript y TypeScript** y permite utilizar Markdown y MDX.

También permite utilizar componentes y diferentes tecnologías web para crear sitios modernos.

## 4. Comparación entre Jekyll, Hugo y Astro

| Característica | Jekyll | Hugo | Astro |
|---|---|---|---|
| **Lenguaje principal** | Ruby | Go | JavaScript / TypeScript |
| **Contenido** | Markdown | Markdown | Markdown / MDX |
| **Requisitos** | Ruby y Jekyll | Hugo | Node.js y Astro |
| **Velocidad** | Buena | Muy alta | Alta |
| **Uso habitual** | Blogs y sitios personales | Blogs, documentación y sitios grandes | Blogs, documentación y sitios modernos |
| **GitHub Pages** | Integración directa | Requiere configuración | Requiere configuración |

## 5. Vídeo explicativo sobre SSG

[CSR vs SSR vs SSG explained in 90 seconds](https://youtu.be/1qgJjnSXJqg)

## 6. Elementos de Markdown utilizados

En este documento se han utilizado diferentes elementos de la sintaxis Markdown:

- **Negrita**
- *Cursiva*
- Listas
- Tablas
- Enlaces
- Citas
- Bloques de código
- Diferentes niveles de títulos

---