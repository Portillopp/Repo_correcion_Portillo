
# CMS - Sistemas de Gestión de Contenidos

## 1. ¿Qué es un CMS?

Un **CMS (Content Management System)** es una aplicación que permite crear, editar, organizar y publicar contenido en un sitio web sin necesidad de programarlo todo desde cero.

CMS significa *Content Management System*, que en español se traduce como *Sistema de Gestión de Contenidos*.

Su principal utilidad es permitir que personas con pocos conocimientos técnicos puedan gestionar una página web de forma sencilla y centralizada. Desde un panel de administración se pueden gestionar textos, imágenes, páginas, entradas de blog, categorías y otros contenidos.

> Un CMS facilita la creación y administración de una página web mediante un panel de gestión.

### ¿Para qué sirve?

Un CMS permite, entre otras cosas:

- Crear y editar páginas web.
- Publicar entradas y artículos.
- Añadir imágenes y otros archivos multimedia.
- Organizar el contenido mediante categorías y etiquetas.
- Gestionar usuarios y permisos.
- Modificar el diseño mediante plantillas o temas.
- Añadir funcionalidades mediante plugins o extensiones.

![Imagen ilustrativa de un sistema de gestión de contenidos](imagenes/cms.png)

## 2. ¿Cómo funciona un CMS?

Los contenidos de un CMS se crean y administran normalmente desde un **panel de administración o backend**. En este panel se pueden utilizar editores visuales, conocidos como **WYSIWYG**, para añadir y modificar textos, imágenes y otros elementos sin escribir directamente código HTML.

Muchos CMS almacenan la información en una **base de datos**. Cuando un visitante entra en la página, el servidor obtiene la información necesaria y genera la página web. El funcionamiento exacto depende del CMS utilizado.

El funcionamiento básico de un CMS dinámico puede representarse así:

```text
Administrador
      ↓
Panel de administración
      ↓
     CMS
      ↓
Base de datos
      ↓
Servidor web
      ↓
Página web para el visitante
```

## 3. Ventajas y desventajas de un CMS

### Ventajas

- **Facilidad de uso:** permite publicar y modificar contenido sin conocimientos avanzados de programación.
- **Gestión de usuarios:** permite que varias personas trabajen con diferentes roles y permisos.
- **Plantillas y temas:** facilita cambiar el diseño de una página web.
- **Plugins y extensiones:** permite añadir funcionalidades sin programarlas desde cero.
- **Actualización rápida:** los cambios en el contenido pueden publicarse fácilmente.
- **Gestión centralizada:** el contenido se administra desde un único panel.

### Desventajas

- **Mantenimiento:** necesita actualizaciones, copias de seguridad y mantenimiento periódico.
- **Seguridad:** los componentes desactualizados pueden introducir vulnerabilidades.
- **Rendimiento:** puede ser más lento que un sitio estático si no está bien optimizado.
- **Base de datos y servidor:** muchos CMS necesitan una base de datos y un entorno de ejecución.
- **Complejidad:** instalar demasiados plugins puede hacer que el sitio sea más pesado y difícil de mantener.

## 4. Tipos de gestores de contenidos

Los CMS se pueden clasificar según su propósito y su arquitectura.

### Según su propósito

- **CMS generalistas:** permiten crear diferentes tipos de sitios web. Ejemplos: WordPress y Joomla.
- **CMS de comercio electrónico:** están orientados a las tiendas online. Ejemplos: Shopify y PrestaShop.
- **CMS empresariales:** permiten gestionar grandes cantidades de contenido y usuarios. Ejemplos: Adobe Experience Manager y Sitecore.
- **CMS headless:** separan la gestión del contenido de la parte visual y permiten acceder a él mediante una API. Ejemplos: Contentful y Strapi.

### Según su arquitectura

#### CMS tradicional o monolítico

La gestión del contenido y la presentación de la página web están integradas en el mismo sistema.

Un ejemplo es WordPress en su funcionamiento tradicional.

#### CMS headless

La parte que gestiona el contenido está separada de la parte visual. El contenido puede enviarse a diferentes aplicaciones mediante una API.

Ejemplos: Contentful y Strapi.

#### CMS híbrido

Combina características de los CMS tradicionales y headless. Puede utilizarse de forma tradicional y también ofrecer acceso al contenido mediante una API.

WordPress, por ejemplo, dispone de una REST API que permite utilizar su contenido desde otras aplicaciones.

## 5. Ejemplos y ranking de los CMS más utilizados

Algunos CMS conocidos son WordPress, Shopify, Wix, Squarespace y Joomla. Se utilizan para crear distintos tipos de páginas web.

### Top 5 según cuota de mercado

La siguiente tabla recoge datos de W3Techs consultados el **8 de octubre de 2026**. La cuota de mercado indica el porcentaje entre los sitios web en los que W3Techs identifica un CMS. No es el porcentaje sobre todas las páginas web existentes.

| Posición | CMS | Cuota de mercado | Uso principal |
|---|---|---:|---|
| 1 | WordPress | 58,6 % | Blogs y páginas corporativas |
| 2 | Shopify | 7,8 % | Tiendas online |
| 3 | Wix | 6,1 % | Creación visual de páginas web |
| 4 | Squarespace | 3,6 % | Páginas profesionales y portfolios |
| 5 | Joomla | 1,6 % | Páginas web y portales |

**Fuente:** [W3Techs - Usage statistics of content management systems](https://w3techs.com/technologies/overview/content_management). Fecha de consulta: 28 de octubre de 2026; cifras correspondientes al 8 de octubre de 2026.

Estos porcentajes son estimaciones de uso tecnológico, no una valoración de calidad, seguridad o facilidad de uso. Además, pueden cambiar con el tiempo.

### WordPress

WordPress es uno de los CMS más conocidos y utilizados. Permite crear blogs, páginas corporativas, tiendas online y otros sitios web.

Una de sus principales ventajas es la gran cantidad de temas y plugins disponibles para ampliar sus funcionalidades.

## 6. CMS dinámico frente a SSG

Un CMS dinámico y un generador de sitios estáticos (SSG) permiten crear sitios web, pero funcionan de manera diferente.

| Característica | CMS dinámico | SSG |
|---|---|---|
| Contenido | Se gestiona desde un panel de administración. | Normalmente se escribe en archivos Markdown u otros formatos. |
| Base de datos | Muchos CMS utilizan una base de datos. | No suele necesitar una base de datos para servir las páginas generadas. |
| Generación del HTML | Puede generarse cuando se solicita una página. | Se genera durante el proceso de construcción o *build*. |
| Panel de administración | Habitualmente sí. | No suele incluirlo de forma predeterminada. |
| Rendimiento | Depende del servidor y de la optimización. | Puede ser muy alto al servir archivos estáticos. |
| Seguridad | Requiere mantener actualizado el CMS y sus componentes. | La publicación de archivos estáticos reduce ciertos riesgos en el servidor. |
| Actualización | El contenido puede publicarse directamente desde el panel. | Normalmente hay que volver a generar y publicar el sitio. |
| Ejemplos | WordPress y Joomla. | Jekyll, Hugo y Astro. |

La elección depende del proyecto: un CMS resulta cómodo para gestionar contenido desde una interfaz, mientras que un SSG puede ser adecuado para webs rápidas cuyo contenido se gestiona mediante archivos y procesos de construcción.

## 7. Vídeo explicativo sobre CMS

[Qué es un CMS y para qué sirve](https://youtu.be/sSh5AAmItN0)

## 8. Enlace al documento sobre SSG

[Ver documento sobre SSG](ssg.md)

## 9. Elementos de Markdown utilizados

En este documento se utilizan diferentes elementos de Markdown:

- **Negrita**
- *Cursiva*
- Listas
- Tablas
- Enlaces
- Citas
- Bloques de código
- Títulos de distintos niveles
- Imágenes
