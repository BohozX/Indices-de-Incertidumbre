# Índices de Incertidumbre

Publicación automática de metadata de noticias de Bolivia.

Cada 3 horas, al minuto 23 (hora de Bolivia), un colector recorre diez
medios bolivianos y actualiza aquí dos archivos:

| Archivo | Contenido |
|---|---|
| `noticias_ultimos_7_dias_publico.csv` | Metadata de los últimos 7 días: `article_id, fuente, fecha, hora, titulo, url` |
| `estado_ultima_corrida.png` | Estado de la última ejecución: cobertura, duración y resultado por fuente |

## Medios

Unitel · Red Uno · El Deber / Diez · La Razón · Los Tiempos · ANF ·
Visión 360 · Opinión · ERBOL · El Diario

## Alcance

Este repositorio publica **únicamente metadata**: titular, medio, fecha,
hora y enlace. No reproduce el cuerpo de las noticias, que pertenece a
cada medio; para leer una nota hay que seguir su enlace original.

La lógica de extracción y el histórico completo no forman parte de este
repositorio.
