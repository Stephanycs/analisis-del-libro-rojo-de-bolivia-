# Analisis mamiferos amenazados Bolivia Libro Rojo 2026
# Mamíferos Amenazados de Bolivia 
## Análisis del Libro Rojo de Vertebrados 2026

## Descripción
Análisis exploratorio de 20 especies de mamíferos amenazados
en Bolivia, basado en el Libro Rojo de los Vertebrados de
Bolivia: Volumen V. Mamíferos (2026), publicado por el
Ministerio de Planificación del Desarrollo y Medio Ambiente.

## Hallazgos principales
1. El 90% de los mamíferos analizados están amenazados
   (CR+EN+VU). Solo 2 de 20 tienen categorías menos críticas.

2. La Amazonia boliviana está en crisis severa — concentra
   12 especies amenazadas incluyendo las 2 únicas endémicas:
   el Bufeo (EN) y el Manechi colorado (VU).

3. Las áreas protegidas no son suficientes — 5 especies
   CR/EN siguen en peligro dentro de ellas.

4. 6 especies empeoraron su categoría desde 2009,
   especialmente en la Amazonia.

## Especies más críticas
| Especie | Nombre común | Categoría | Ecorregión |
|---|---|---|---|
| Chinchilla chinchilla | Chinchilla | CR | Puna |
| Leopardus jacobita | Gato andino | CR | Puna |
| Inia boliviensis | Bufeo | EN | Amazonia |
| Pteronura brasiliensis | Londra | EN | Amazonia |
| Ateles chamek | Marimono | EN | Amazonia |

## Herramientas
- Python (Google Colab)
- pandas · matplotlib
- SQL (SQLiteOnline)
- Fuente: Libro Rojo Vertebrados Bolivia Vol. V (2026)

## Estructura del análisis
1. Extracción de datos del PDF oficial
2. Exploración y limpieza del dataset
3. Análisis de categorías y cambios 2009 vs 2026
4. Análisis por ecorregión y orden taxonómico
5. Efectividad de áreas protegidas
6. Informe con reflexión final
7. Consultas SQL con CASE WHEN y GROUP BY

## Autora
Stephany Carrasco Sardon — Medellín, Colombia
