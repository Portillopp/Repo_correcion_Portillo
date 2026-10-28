# CMS - Sistemas de Gestión de Contenidos

## 1. ¿Qué es un CMS?

Un **CMS (Content Management System)** es una aplicación web que permite **crear, editar, organizar y publicar contenido** en un sitio web sin necesidad de programar todo desde cero.

CMS significa *Content Management System*, que en español se traduce como *Sistema de Gestión de Contenidos*.

Su principal utilidad es permitir que personas con pocos conocimientos técnicos puedan gestionar una página web de forma **sencilla y centralizada**. Desde un panel de administración se pueden gestionar textos, imágenes, páginas, entradas de blog, categorías y otros contenidos.

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

## 2. ¿Cómo funciona un CMS?

Los contenidos de un CMS se crean y administran normalmente desde un **panel de administración o backend**. En este panel, el usuario puede utilizar editores visuales, conocidos como **WYSIWYG**, para añadir y modificar textos, imágenes y otros elementos sin escribir directamente código HTML.

El CMS almacena normalmente la información en una **base de datos**. Cuando un visitante entra en la página, el servidor consulta la información necesaria y genera la página web de forma dinámica.

El funcionamiento básico puede representarse así:

```text
Usuario
   ↓
Panel de administración
   ↓
CMS
   ↓
Base de datos
   ↓
Servidor
   ↓
Página web
   ↓
Visitante
```

## 3. Ventajas y desventajas de un CMS

### Ventajas

Los CMS ofrecen varias ventajas a la hora de crear y administrar un sitio web:

- **Facilidad de uso:** permiten publicar y modificar contenido sin necesidad de tener conocimientos avanzados de programación.
- **Gestión de usuarios:** permiten que varias personas trabajen en una misma página web con diferentes roles y permisos.
- **Plantillas y temas:** permiten cambiar el diseño de una página web de forma sencilla.
- **Plugins y extensiones:** permiten añadir nuevas funcionalidades sin tener que programarlas desde cero.
- **Actualización rápida:** los cambios realizados en el contenido pueden publicarse rápidamente.
- **Gestión centralizada:** todo el contenido se puede administrar desde un único panel de control.

### Desventajas

A pesar de sus ventajas, los CMS también presentan algunos inconvenientes:

- **Mantenimiento:** necesitan actualizaciones, copias de seguridad y mantenimiento periódico.
- **Seguridad:** pueden ser más vulnerables si existen plugins, temas o componentes desactualizados.
- **Rendimiento:** pueden ser más lentos que un sitio web estático, especialmente si no están bien optimizados.
- **Base de datos:** normalmente necesitan una base de datos y un servidor capaz de ejecutar el CMS.
- **Funciones innecesarias:** instalar demasiados plugins o extensiones puede hacer que el sitio sea más complejo y pesado.

## 4. Tipos de gestores de contenidos

Los CMS se pueden clasificar de diferentes formas. Una de ellas es según su **propósito** y otra según su **arquitectura**.

### Según su propósito

- **CMS generalistas:** permiten crear y gestionar todo tipo de sitios web. Algunos ejemplos son **WordPress** y **Joomla**.
- **CMS de comercio electrónico:** están orientados a la creación y gestión de tiendas online. Algunos ejemplos son **Shopify**, **WooCommerce** y **PrestaShop**.
- **CMS empresariales:** están diseñados para grandes organizaciones que necesitan gestionar grandes cantidades de contenido y usuarios. Algunos ejemplos son **Adobe Experience Manager** y **Sitecore**.
- **CMS Headless:** separan la gestión del contenido de la parte visual de la página web y permiten acceder al contenido mediante una API. Algunos ejemplos son **Contentful** y **Strapi**.

### Según su arquitectura

#### CMS tradicional o monolítico

En este tipo de CMS, la gestión del contenido y la presentación de la página web están integradas en el mismo sistema.

Un ejemplo de este tipo es **WordPress** en su funcionamiento tradicional.

#### CMS Headless

En un CMS Headless, la parte encargada de gestionar el contenido está separada de la parte visual de la página web. El contenido se puede enviar a diferentes aplicaciones mediante una **API**.

Algunos ejemplos son **Contentful** y **Strapi**.

#### CMS híbrido

Un CMS híbrido combina características de los CMS tradicionales y de los CMS Headless. Permite utilizar el sistema de forma tradicional y también acceder al contenido mediante una API.

Un ejemplo es **WordPress**, que puede utilizar su **REST API** para enviar contenido a otras aplicaciones.

## 5. Ejemplos de CMS más utilizados

Existen muchos gestores de contenidos diferentes. Algunos de los más conocidos son:

| CMS | Tipo | Características principales |
|---|---|---|
| **WordPress** | Generalista | Fácil de utilizar y con gran cantidad de temas y plugins. |
| **Joomla** | Generalista | Permite crear diferentes tipos de sitios web y ofrece muchas opciones de configuración. |
| **Shopify** | Comercio electrónico | Está especializado en la creación y gestión de tiendas online. |
| **PrestaShop** | Comercio electrónico | Permite crear y administrar tiendas online de forma flexible. |
| **Wix** | Generalista | Permite crear páginas web mediante un editor visual. |

### WordPress

**WordPress** es uno de los CMS más conocidos y utilizados. Permite crear blogs, páginas corporativas, tiendas online y muchos otros tipos de sitios web.

Una de sus principales ventajas es la gran cantidad de **temas y plugins** disponibles para ampliar sus funcionalidades.

## 6. CMS dinámico frente a SSG

Un CMS dinámico y un generador de sitios estáticos (SSG) permiten crear sitios web, pero funcionan de manera diferente.

| Característica | CMS dinámico | SSG |
|---|---|---|
| Contenido | Se gestiona desde un panel de administración. | Se suele escribir en archivos Markdown. |
| Base de datos | Normalmente utiliza una base de datos. | No necesita una base de datos para generar las páginas. |
| Generación del HTML | Se genera cuando el usuario visita la página. | Se genera durante el proceso de construcción o *build*. |
| Panel de administración | Sí. | No normalmente. |
| Rendimiento | Puede ser menor si no está bien optimizado. | Normalmente es alto. |
| Seguridad | Puede tener más riesgos debido a la base de datos, plugins y servidor. | Suele ofrecer mayor seguridad al publicar archivos estáticos. |
| Actualización | Los cambios pueden publicarse directamente. | Es necesario volver a generar el sitio antes de publicarlo. |
| Ejemplos | WordPress y Joomla. | Jekyll, Hugo y Astro. |

## 7. Vídeo explicativo sobre CMS

[Qué es un CMS y para qué sirve (Explicado en 2 minutos)](https://youtu.be/sSh5AAmItN0)

## 8. Enlace al documento sobre SSG

[Ver documento sobre SSG](ssg.md)