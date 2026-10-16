# Datos del curso

Esta carpeta combina datos sintéticos para ejercicios de programación y tres archivos de fuentes externas para lectura y análisis exploratorio en la clase 04.

## `raw/`

- `muestras_geologia.csv`: 180 muestras con coordenadas y variables litológicas, geoquímicas y físicas.
- `parcelas_biologia.csv`: 180 parcelas con coordenadas, hábitat y variables ambientales/ecológicas.
- `observaciones_especies.csv`: ocurrencias puntuales de cuatro especies ficticias/de referencia didáctica.

Los tres CSV sintéticos anteriores incluyen algunos `NA` y valores atípicos controlados para ejercicios de calidad de datos.

### Archivos de fuentes externas · clase 04

- `Earthquakes in Colombia (from 2000).csv`: catálogo de [USGS](https://earthquake.usgs.gov/earthquakes/search/) · [API](https://earthquake.usgs.gov/fdsnws/event/1/1). Incluye eventos de países vecinos; el nombre no garantiza una selección exclusiva de Colombia. Profundidad en km y magnitud con su tipo reportado.
- `Datos hidrometeorológicos Medellín.csv`: serie diaria de [NASA POWER](https://power.larc.nasa.gov/data-access-viewer/) · [documentación de la API](https://power.larc.nasa.gov/docs/services/api/temporal/daily/), para 6.2446, −75.5451, de 2000-01-01 a 2026-09-30 según su encabezado. Tiene 12 líneas de metadatos antes de la tabla y usa `-999` para ausentes. `T2M` es temperatura a 2 m (°C) y `PRECTOTCORR`, precipitación corregida (mm/día).
- `DB Pinguinos.csv`: [Palmer Penguins](https://github.com/allisonhorst/palmerpenguins), con categorías de especie, isla y sexo, cuatro medidas corporales y año de muestreo. Los campos vacíos son ausentes.

Estos archivos no son los datos sintéticos del curso. Sus condiciones de uso y atribución deben consultarse en las fuentes enlazadas.

`curso_R_data.zip` contiene los datos sintéticos originales. Para la clase 04 usa los tres CSV externos disponibles en `data/raw/`.

## `spatial/`

- `limite_area_estudio.geojson`
- `unidades_geologicas.geojson`
- `habitats.geojson`
- `cauces.geojson`
- `dem_sintetico.tif`

La extensión usa coordenadas semejantes al Valle de Aburrá solo para que la escala sea familiar. No debe interpretarse como cartografía real.
