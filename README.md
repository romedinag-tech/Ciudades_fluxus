# Ciudades y tendencias de Chile — tema Fluxus

Variante con la **identidad visual de Fluxus Ingeniería** (dark navy + cyan, tipografía Inter)
del mismo sitio. Plataforma web única (estática, sin backend) que reúne el **análisis de uso
de suelo y población** de las ciudades de Chile con las **proyecciones de tendencias**
demográficas y de uso de suelo (horizontes 2030 / 2035).

El re-skin se aplica con `fluxus.css` (cargado sobre el CSS base) + mapas con tiles oscuros
(CARTO dark) + Chart.js en colores claros. El contenido y los datos son idénticos al sitio base.

## Pestañas

Resumen · Oferta de servicios por habitante · Dinámica de crecimiento · Comparar ciudades ·
Ranking · **Tendencias demográficas** (envejecimiento por zona 65+/<15, peak poblacional) ·
**Tendencias de uso de suelo** (m² por uso a nivel de zona, escenarios).

Las pestañas de *Tendencias* se integran como secciones nativas y quedan **ancladas al menú
global de ciudades**: al seleccionar una comuna o área metropolitana, ambas se actualizan.

## Aviso

Es un **ejercicio estadístico provisional**. Las proyecciones **no incorporan los
instrumentos de planificación territorial (planes reguladores)**, ni constituyen un
pronóstico oficial.

## Deploy (GitHub Pages)

Servir la raíz del repositorio. Local: `python -m http.server` en la raíz.

Rodrigo Medina González · Universidad de Concepción.
