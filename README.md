# Madrid — laboratorio de rutas temáticas

Repositorio de investigación y diseño para un futuro portafolio de rutas temáticas a pie por la Comunidad de Madrid.

## Estado actual

**Fase 2: búsqueda de puntos de interés turístico en la Comunidad de Madrid.**

La [lista de interés turístico](points/fase-2-interes-turistico.md) reúne 70 puntos en 29 municipios, con 42 candidatos fuera de la capital.

### Fase 1 completada

El catálogo reúne 38 temas investigados. Los cuatro bloques documentan 222 registros de candidatos en 32 municipios. La cifra incluye ubicaciones con varias lecturas temáticas.

| Bloque temático | Registros |
|---|---:|
| [MAD-001 a MAD-007](themes/scouting/fase-1-mad-001-007.md) | 38 |
| [MAD-008 a MAD-014](themes/scouting/fase-1-mad-008-014.md) | 46 |
| [MAD-015 a MAD-028](themes/scouting/fase-1-mad-015-028.md) | 81 |
| [MAD-029 a MAD-038](themes/scouting/fase-1-mad-029-038.md) | 57 |

La búsqueda independiente por geografía corresponde a la fase 3.

## Qué hereda de París

El proyecto conserva lo que funcionó en `andresmejiaro/Paris` y corrige lo que el terreno demostró que fallaba:

- tema y experiencia antes que kilómetros o número de rutas;
- búsqueda temática amplia antes de dibujar geometría;
- recompensa presencial y materialidad, no solo una historia verdadera;
- distribución de recompensas a lo largo del paseo;
- final fuerte que responda a la apertura;
- navegación y relato como productos separados;
- coordenadas, accesos, baños, refugio, comida con asiento y escapes de transporte como parte de la calidad;
- auditoría de campo capaz de corregir el modelo, no solo la ejecución.

La retrospectiva completa está en [`docs/01_lecciones_de_paris.md`](docs/01_lecciones_de_paris.md).

## Estructura

- `docs/`: principios, proceso y criterios.
- `themes/`: banco de temas y catálogo estructurado.
- `points/`: puntos candidatos de la búsqueda por interés turístico.
- `templates/`: fichas para investigar sin saltar prematuramente a una ruta.
- `evidence/`: reglas para fuentes y evidencia.
- `decisions/`: decisiones de alcance y cambios de criterio.
- `schemas/`: contrato de datos para las semillas temáticas.

## Regla de fase

La búsqueda registra candidatos con sus fuentes y su materialidad. Un tema solo puede pasar a investigación profunda cuando tenga una promesa distintiva y señales suficientes de material visible o experimentable. La selección de paradas, la geometría, los guiones y la navegación pertenecen al diseño posterior.
