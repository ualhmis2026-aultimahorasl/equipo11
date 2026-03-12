# Despliegue del Blog en GitHub Pages

**Fecha:** 12 marzo 2026  
**Autor:** Víctor Ruz Hernández  

## Introducción

GitHub Pages es un servicio gratuito ofrecido por GitHub que permite publicar sitios web estáticos directamente desde un repositorio. Es una herramienta muy útil para desplegar proyectos web sin necesidad de configurar servidores ni infraestructura adicional.

En nuestro proyecto utilizamos GitHub Pages para publicar el blog del equipo desarrollado para la asignatura Herramientas y Métodos en Ingeniería del Software.

## Crear el repositorio

El primer paso consiste en crear un repositorio en GitHub donde se almacenarán todos los archivos del blog, incluyendo la página principal, las páginas de los miembros del equipo y las entradas del blog.

Una vez creado el repositorio, se suben los archivos del proyecto utilizando Git o directamente desde la interfaz web de GitHub.

## Activar GitHub Pages

Para publicar el sitio web debemos activar GitHub Pages desde la configuración del repositorio.

Los pasos son:

1. Ir a Settings en el repositorio.
2. Acceder a la sección Pages.
3. En Source seleccionar:
   - Deploy from a branch
   - Branch: main
   - Folder: /root
4. Guardar los cambios.

## Publicación del sitio

Después de guardar la configuración, GitHub genera automáticamente el sitio web. Tras unos segundos el proyecto estará disponible públicamente.

La URL generada suele tener el siguiente formato:

    https://organizacion.github.io/repositorio

En nuestro caso el blog del equipo se encuentra disponible en:

    https://ualhmis2026-aultimahorasl.github.io/RuzRamirez

## Ventajas de GitHub Pages

Algunas ventajas de utilizar GitHub Pages son:

- Publicación rápida y sencilla
- Integración directa con repositorios Git
- Servicio completamente gratuito
- Ideal para proyectos web estáticos

## Conclusión

GitHub Pages es una solución muy práctica para publicar sitios web estáticos. Permite a los desarrolladores compartir proyectos fácilmente y resulta especialmente útil en entornos educativos y proyectos colaborativos.

---

[Volver al blog](../index.html)
