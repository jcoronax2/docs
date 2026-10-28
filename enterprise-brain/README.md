# Enterprise Brain · Arquitectura

Demo conceptual del **COE Arquitecturas Ágiles** (Julio César Corona): un grafo de conocimiento que responde preguntas de arquitectura recorriendo relaciones (dominio → capacidad → sistema → patrón → ADR → control/riesgo) y mostrando la ruta y la evidencia de cada respuesta.

Incluye 3 preguntas guionadas con recorrido multi-hop animado, mapa de impacto, vistas de negocio/técnica, línea de tiempo de ADRs, respuesta trazable con confianza y evidencia, casos de uso y el pipeline (Fuentes → Ingesta → Grafo Neo4j · GraphOS → Recuperación híbrida → Agente → Respuesta trazable).

## Abrir localmente

Es un único `index.html` estático (HTML + CSS + JS vanilla, sin build ni dependencias). Ábralo directamente en el navegador, o sirva la carpeta:

```bash
python3 -m http.server 8000   # luego http://localhost:8000
```

En GitHub Pages: publique la rama/carpeta que contiene `index.html`.

## Aviso

Los nodos, ADRs, sistemas, relaciones, consultas Cypher y respuestas son **datos de muestra ilustrativos**. Este sitio es una demo personal; **no es un producto, portal ni sitio oficial de Davivienda** ni de ninguna otra entidad.
