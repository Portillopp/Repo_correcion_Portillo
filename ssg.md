
# SSG - Generadores de Sitios Estáticos

## 1. ¿Qué es un SSG?

Un **SSG (Static Site Generator)** es una herramienta que permite crear sitios web estáticos a partir de archivos de contenido y plantillas.

SSG significa *Static Site Generator*, que en español se traduce como *Generador de Sitios Estáticos*.

A diferencia de un CMS dinámico, un SSG genera las páginas web **antes de que sean publicadas**. Normalmente, el contenido se escribe en archivos Markdown y, mediante un proceso de construcción o *build*, se generan archivos HTML que pueden publicarse en un servidor.

Los sitios generados de esta forma no necesitan consultar una base de datos cada vez que un usuario visita una página.

> Un SSG genera las páginas web durante el proceso de construcción para que puedan servirse como archivos estáticos.

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

![Imagen ilustrativa de un generador de sitios estáticos](imagenes/ssg.png)

## 2. Ventajas y desventajas de un SSG

### Ventajas

- **Rendimiento:** las páginas se generan previamente y se sirven como archivos estáticos.
- **Seguridad:** normalmente no necesita una base de datos ni un CMS ejecutándose en el servidor público.
- **Simplicidad:** permite escribir el contenido utilizando Markdown.
- **Reutilización:** las plantillas permiten reutilizar menús, cabeceras y pies de página.
- **Alojamiento:** los archivos generados pueden publicarse en servicios de alojamiento de sitios estáticos.

### Desventajas

- **Conocimientos técnicos:** es necesario aprender a utilizar la herramienta y su estructura.
- **Proceso de construcción:** normalmente hay que volver a generar y publicar el sitio después de realizar cambios.
- **Contenido dinámico:** puede requerir servicios adicionales para funciones como comentarios, cuentas de usuario o datos personalizados.
- **Configuración inicial:** algunos generadores necesitan una configuración inicial antes de poder utilizarse.

## 3. Principales generadores de sitios estáticos

En este trabajo se comparan Jekyll, Hugo y Astro.

### Jekyll

**Jekyll** es un generador de sitios estáticos desarrollado en Ruby. Permite utilizar archivos Markdown y plantillas para generar páginas HTML estáticas.

Es especialmente conocido por su uso en blogs y sitios personales. También puede utilizarse junto con GitHub Pages.

### Hugo

**Hugo** es un generador de sitios estáticos desarrollado en Go. Está diseñado para generar sitios web rápidamente.

Permite utilizar Markdown para escribir el contenido y plantillas para definir la estructura del sitio.

### Astro

**Astro** es una herramienta para crear sitios web orientados principalmente al contenido y al rendimiento. Está basada en JavaScript y TypeScript y permite utilizar Markdown y MDX.

También permite utilizar componentes y diferentes tecnologías web para crear sitios modernos.

## 4. Comparación entre Jekyll, Hugo y Astro

| Característica | Jekyll | Hugo | Astro |
|---|---|---|---|
| Lenguaje principal | Ruby | Go | JavaScript / TypeScript |
| Contenido | Markdown | Markdown | Markdown / MDX |
| Requisitos | Ruby y Jekyll | Instalar Hugo | Node.js y Astro |
| Velocidad de construcción | Buena | Muy alta | Alta, según el proyecto |
| Uso habitual | Blogs y sitios personales | Blogs, documentación y sitios grandes | Blogs, documentación y sitios modernos |
| GitHub Pages | Compatible directamente | Requiere configurar la generación | Requiere configurar la generación |

Los tres permiten generar sitios estáticos, pero se diferencian en el lenguaje, la configuración y las características que ofrecen.

## 5. SSG frente a escribir HTML manualmente

Un SSG y la escritura manual de HTML permiten crear páginas web, pero el proceso de trabajo es diferente.

| Característica | HTML manual | SSG |
|---|---|---|
| Creación de páginas | Se escribe el HTML de cada página. | Las páginas se generan automáticamente a partir del contenido y las plantillas. |
| Automatización | Baja si hay muchas páginas repetidas. | Alta gracias a las plantillas y al proceso de construcción. |
| Reutilización | Hay que copiar elementos o utilizar otras técnicas. | Las plantillas permiten reutilizar cabeceras, menús y pies de página. |
| Mantenimiento | Los cambios repetidos pueden requerir editar muchos archivos. | Un cambio en una plantilla puede aplicarse a muchas páginas al regenerar el sitio. |
| Dificultad | Adecuado para aprender HTML y crear páginas sencillas. | Requiere aprender el generador y su configuración. |
| Rendimiento | Puede ser muy alto si las páginas están bien creadas. | También puede ser muy alto porque genera archivos estáticos. |
| Casos de uso | Páginas pequeñas y sencillas. | Blogs, documentación, portfolios y sitios con contenido repetido. |

**Conclusión:** escribir HTML manualmente puede ser suficiente para una web pequeña con pocas páginas. Un SSG resulta más útil cuando hay muchas páginas o elementos repetidos, porque automatiza la generación y facilita el mantenimiento.

## 6. Vídeo explicativo sobre SSG

[CSR vs SSR vs SSG explained in 90 seconds](https://youtu.be/1qgJjnSXJqg)

## 7. Elementos de Markdown utilizados

En este documento se utilizan diferentes elementos de la sintaxis Markdown:

- **Negrita**
- *Cursiva*
- Listas
- Tablas
- Enlaces
- Citas
- Bloques de código
- Títulos de distintos niveles
- Imágenes
