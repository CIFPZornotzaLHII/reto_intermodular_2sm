# Reto · Proyecto intermodular · SMR (2.º de SMR)

**CIFP Zornotza LHII · curso 2026-27 · módulo 1713 Proyecto intermodular · 50 h · grado medio**

> Este repositorio es el enunciado del reto. Lo que construyáis se publica en la web de proyectos del centro:
> [`CIFPZornotzaLHII/proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares).

## Qué es el proyecto intermodular

Es el módulo que une todo lo demás: en vez de aprender una cosa por módulo, cogéis una necesidad real y la
resolvéis usando lo que sabéis de varios módulos a la vez. Se evalúa con los resultados de aprendizaje (RA) del
módulo, que son estos:

| RA | Qué tenéis que demostrar |
|---|---|
| RA1 | Caracteriza las empresas del sector: organización, departamentos, demanda, recursos y relación con los ODS. |
| RA2 | Propone una solución a una necesidad real del sector y desarrolla un pequeño proyecto: viabilidad, presupuesto, documentación de diseño, calidad y presentación pública. |
| RA3 | Planifica la ejecución: secuencia de actividades, recursos, permisos, riesgos e imprevistos. |
| RA4 | Hace el seguimiento de la ejecución: comprueba la calidad, detecta desviaciones, las corrige y lo documenta. |
| RA5 | Comunica la información de forma clara, ordenada y estructurada, con herramientas TIC y terminología técnica en otros idiomas. |

## El reto

Un cliente real o realista (una pyme, una asociación, un departamento del centro, una familia) tiene un problema de
sistemas o redes. Vuestro grupo lo analiza, propone una solución, la planifica, **la monta** (en Proxmox, en el
aula o en equipos reales), hace el seguimiento de la ejecución y la presenta. Al final tiene que existir algo que
funcione y que se pueda enseñar en 5 minutos: una red, un servidor, un servicio, un procedimiento automatizado.

Lo que diferencia un proyecto de SMR de una práctica de clase: hay un cliente con una necesidad, un presupuesto,
un plan con fechas, riesgos previstos, y una ejecución con desviaciones registradas y resueltas.

## Qué tiene que entregar cada grupo

- **Landing page** de presentación del proyecto con las seis secciones que se evalúan: necesidad, solución, planificación, demo, seguimiento y control, equipo. Se publica en la web del centro (plantilla en el repo de la web).
- **Tarjeta** en la web de proyectos: la carpeta `proyectos/<ciclo>/<tu-proyecto>/` con `proyecto.json` (título, resumen, equipo, portada, vídeo, repo). La etiqueta de grado la pone la web.
- **Vídeo de presentación de 5 minutos** en el que se ve al equipo hablando y la pantalla, en este orden: solución, planificación, mini demo, seguimiento y control. Se enlaza (YouTube o Drive del centro), no se sube al repo.
- **Documento de planificación** y **registro de seguimiento** (plantillas en `plantillas/`), enlazados desde la landing.
- **Algo ejecutado de verdad**: la maqueta, la instalación, la configuración o el servicio tiene que existir y funcionar en la demo. Un documento solo no vale: el RA4 pide seguir una ejecución.

### Cómo se publica

1. Fork de [`CIFPZornotzaLHII/proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares) y clonarlo.
2. Copiar `proyectos/_plantilla/` a `proyectos/2SM/<nombre-del-proyecto>/` y rellenar `proyecto.json` y `index.html`.
3. Abrir una **pull request** que solo toque esa carpeta. El robot comprueba las reglas; el profesor la acepta y el servidor se actualiza solo.
4. El vídeo puede llegar en una segunda pull request cuando esté grabado.

Guía paso a paso: [`proyectos/LEEME.md`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/blob/main/proyectos/LEEME.md).

## Fases y horas (50 h del módulo)

| Fase | Horas | Qué se hace | Entregable / hito |
|---|---|---|---|
| 0 · Arranque | 2 | Equipos, lectura del reto, elección de idea (de `IDEAS.md` o propia, aprobada por el profesor) | Equipo e idea registrados |
| 1 · Análisis | 6 | Necesidad real, cliente o sector, cómo se hace ahora, alternativas (RA1: caracterizar la empresa) | Ficha de análisis (sección 1 de la planificación) |
| 2 · Diseño y planificación | 8 | Alcance, requisitos, diseño de la solución, tareas con estimación, riesgos, recursos y presupuesto | **Hito 1**: planificación aprobada |
| 3 · Ejecución | 22 | Montar, instalar y configurar la solución. Registro de seguimiento semanal | **Hito 2**: revisión intermedia con demo parcial |
| 4 · Cierre | 8 | Landing, vídeo, pull request, registro de seguimiento final | Proyecto publicado en la web |
| 5 · Defensa | 4 | Presentación ante el equipo docente: vídeo (5 min) + preguntas (5 min) | Defensa |

Las 50 h son las del módulo. La parte técnica se apoya en lo que ya sabéis hacer de los otros módulos; en estas horas se analiza, planifica, ejecuta con seguimiento, documenta, publica y defiende.
Las fechas concretas de cada hito las fija el profesor al inicio del curso y se anotan en `CALENDARIO.md`.

## Evaluación

La nota sale de la rúbrica de [`EVALUACION.md`](EVALUACION.md): planificación, ejecución, seguimiento y control, publicación (landing y tarjeta) y vídeo + defensa. Cada RA está asociado a uno o varios entregables, así que si falta un entregable, falta un RA.

## Ideas

Veinte ideas de partida, pensadas con las tecnologías que trabajáis en el ciclo, en [`IDEAS.md`](IDEAS.md). Podéis
proponer otra: la condición es que tenga un cliente o necesidad identificable y que se pueda montar en el tiempo del módulo.

## Plantillas

- [`plantillas/planificacion.md`](plantillas/planificacion.md): documento de planificación (análisis, alcance, tareas, riesgos, presupuesto).
- [`plantillas/seguimiento.md`](plantillas/seguimiento.md): registro semanal de seguimiento y control.
- [`plantillas/guion-video.md`](plantillas/guion-video.md): guion del vídeo de 5 minutos.

## Normas

- **Equipos** de 2 personas (3 si el profesor lo autoriza). Cada persona tiene tareas asignadas y visibles en la planificación: en la defensa se pregunta a cada uno por lo suyo.
- **Honestidad en el seguimiento.** Un plan que "salió perfecto" sin desviaciones es sospechoso. Se valora detectar el problema, decidir y dejarlo escrito.
- **Inteligencia artificial.** Se puede usar para investigar, redactar y programar, con dos condiciones: se indica dónde se ha usado y tenéis que ser capaces de explicar y modificar lo que entreguéis. En la defensa se comprueba.
- **Plagio.** Copiar un proyecto ajeno (o entregar algo que no entendéis) suspende el módulo.
- **Vídeos y ficheros grandes** no se suben al repositorio: se enlazan.
- **Idioma.** Landing, vídeo y defensa en el idioma del grupo (castellano o euskera); la terminología técnica en inglés se usa con naturalidad (RA de comunicación).

## Calendario

Fechas de cada hito en [`CALENDARIO.md`](CALENDARIO.md) (las fija el profesor al inicio del curso).
