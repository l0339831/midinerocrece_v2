# CSAT Dashboard – UX Research
Visualiza el flujo de comentarios CSAT hacia decisiones de UX (Sankey), Pareto de categorías y barras apiladas por severidad. Carga datos desde `/data` (JSON/CSV) con fallbacks.

## Estructura
- `index.html` (dashboard con theme switch y tabs)
- `/data/sankey.json` (commentsTotal, flows[])
- `/data/pareto.csv` (categoria,conteo)
- `/data/stacked.json` (labels, alta, media, baja)

## Tecnologías utilizadas
- **HTML5**
- **JavaScript (ES6)**
- **Chart.js v4+**
- **chartjs-chart-sankey** (para diagramas de flujo)

## 📈 Próximos pasos
- Incorporar datos reales de escalamiento de proyectos.
- Integrar la fuente de datos desde un CSV o API de CSAT para actualización automática.


---
**Autor:** [Lean UX]
**Fecha:** Q1 2025
**Licencia:** MIT