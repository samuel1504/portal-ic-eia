# Portal Ingeniería Civil EIA (piloto)

MVP exploratorio construido por la representación estudiantil de Ingeniería
Civil en la EIA (período 2026–2027). No es una plataforma con backend: es un
sitio estático, pensado para validar si vale la pena invertir en algo más
robusto para un programa de ~130 estudiantes.

## Qué incluye este borrador

- Vitrina de proyectos de estudiantes
- Semilleros de investigación
- Prácticas profesionales
- Documentos académicos (reglamentos, formatos, guías, banco de fórmulas)
- Acercamiento a la vida profesional (charlas, encuentros con egresados)
- Un llamado a la acción para que estudiantes propongan contenido o feedback

Todo el contenido de proyectos, semilleros, prácticas y documentos es
**de ejemplo** (marcado como "Ejemplo" en el sitio) — se reemplaza por
información real antes de compartir el sitio ampliamente.

## Cómo verlo localmente

Es HTML/CSS/JS puro, sin dependencias ni build. Basta con abrir
`index.html` en un navegador, o servirlo con cualquier servidor estático:

```bash
python3 -m http.server 8000
```

## Publicación

Pensado para GitHub Pages (rama `main`, carpeta raíz).

## Siguientes pasos si el piloto se valida

1. Reemplazar el contenido de ejemplo por datos reales (semilleros, empresas
   con convenio, documentos oficiales).
2. Conectar un formulario real para que estudiantes envíen proyectos e ideas
   (por ejemplo, Google Forms o Tally, embebido).
3. Si el flujo lo justifica, evaluar backend + autenticación para que los
   estudiantes suban proyectos directamente.
