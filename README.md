# Stockmarket

Herramienta personal de investigación de acciones con Claude. No ejecuta operaciones ni da asesoría financiera profesional.

## Cómo se usa

Abre una sesión de Claude Code con este repo y escribe el ticker, por ejemplo:

> Analiza NVDA, horizonte meses/años.

Las reglas del análisis (fuentes, escenarios, clasificación, decisión sobre la posición y formato) están en [`CLAUDE.md`](CLAUDE.md).

## Privacidad

Este repo es público. Los datos de tu cartera van en `cartera/`, que git ignora. Los análisis guardados en `analisis/` no llevan cantidades ni posiciones.
