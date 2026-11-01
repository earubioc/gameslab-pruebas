# Pruebas de mecánica (repositorio público)

Este repositorio es público. Contiene únicamente pruebas jugables de mecánica para un juego móvil, en la carpeta `sitio/`, y lo mínimo para publicarlas.

## Lo que sí puede estar aquí

- `sitio/`: las pruebas (HTML de un solo archivo cada una), la página de inicio y la fuente tipográfica con su licencia.
- `README.md`, `CLAUDE.md`, `.gitignore`.
- `.github/workflows/pages.yml`: publica `sitio/` con GitHub Pages.

## Lo que nunca debe entrar aquí

- Memoria del proyecto, investigaciones, decisiones, historial, hojas de ruta, cifras de negocio o de mercado.
- Enlaces privados, nombres de repositorios privados, correos, nombres de cuentas distintos del propietario del repositorio.
- Claves, tokens, llaves de firma, archivos `.env`. Ver `.gitignore`.

Todo eso vive en un repositorio privado aparte. Si una tarea necesita contexto del proyecto, se trabaja allí, no aquí.

## Cómo se genera este repositorio

Los archivos de `sitio/` no se editan a mano: se generan desde el repositorio privado, que es la fuente de verdad. Un cambio hecho solo aquí se perderá en la próxima publicación.

## Reglas de trabajo

- No usar guion largo (ni em dash ni en dash) en los textos.
- Sin analítica, sin cuentas, sin servidor. Las pruebas guardan solo ajustes de sensación en `localStorage` del navegador.
- Sin dependencias de terceros en tiempo de ejecución: la fuente tipográfica se sirve desde `sitio/fonts/`.
