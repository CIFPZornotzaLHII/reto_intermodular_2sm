<p align="center"><img src="img/logo-zornotza.png" alt="CIFP Zornotza LHII" width="460"></p>

<a id="castellano"></a>

# Reto · Proyecto intermodular · SMR (2.º de SMR)

**CIFP Zornotza LHII · curso 2026-27 · módulo 1713 Proyecto intermodular · 50 h · grado medio**

**Euskaraz:** [irakurri behean ↓](#euskaraz)

> Este repositorio es el enunciado del reto. Lo que construyáis se publica en la web de proyectos del centro:
> [`CIFPZornotzaLHII/proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares).

## Índice

- [Qué es el proyecto intermodular](#qué-es-el-proyecto-intermodular)
- [El reto](#el-reto)
- [Qué tiene que entregar cada grupo](#qué-tiene-que-entregar-cada-grupo)
  - [Cómo se publica](#cómo-se-publica)
- [Fases y horas (50 h del módulo)](#fases-y-horas-50-h-del-módulo)
- [Evaluación](#evaluación)
- [Ideas](#ideas)
- [Plantillas](#plantillas)
- [Normas](#normas)
- [Calendario](#calendario)
- [Repositorios y enlaces](#repositorios-y-enlaces)
- [Euskaraz](#euskaraz)

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
- **Documento de planificación** y **registro de seguimiento** (plantillas en [`plantillas/`](plantillas/)), enlazados desde la landing.
- **Algo ejecutado de verdad**: la maqueta, la instalación, la configuración o el servicio tiene que existir y funcionar en la demo. Un documento solo no vale: el RA4 pide seguir una ejecución.

### Cómo se publica

1. Fork de [`CIFPZornotzaLHII/proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares) y clonarlo.
2. Copiar [`proyectos/_plantilla/`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/tree/main/proyectos/_plantilla) a `proyectos/2SM/<nombre-del-proyecto>/` y rellenar `proyecto.json` y `index.html`.
3. Abrir una **pull request** que solo toque esa carpeta. El robot comprueba las reglas; el profesor la acepta y el servidor se actualiza solo.
4. El vídeo puede llegar en una segunda pull request cuando esté grabado.

Guía paso a paso: [`proyectos/LEEME.md`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/blob/main/proyectos/LEEME.md).

## Fases y horas (50 h del módulo)

| Fase | Horas | Qué se hace | Entregable / hito |
|---|---|---|---|
| 0 · Arranque | 2 | Equipos, lectura del reto, elección de idea (de [`IDEAS.md`](IDEAS.md) o propia, aprobada por el profesor) | Equipo e idea registrados |
| 1 · Análisis | 6 | Necesidad real, cliente o sector, cómo se hace ahora, alternativas (RA1: caracterizar la empresa) | Ficha de análisis (sección 1 de la planificación) |
| 2 · Diseño y planificación | 8 | Alcance, requisitos, diseño de la solución, tareas con estimación, riesgos, recursos y presupuesto | **Hito 1**: planificación aprobada |
| 3 · Ejecución | 22 | Montar, instalar y configurar la solución. Registro de seguimiento semanal | **Hito 2**: revisión intermedia con demo parcial |
| 4 · Cierre | 8 | Landing, vídeo, pull request, registro de seguimiento final | Proyecto publicado en la web |
| 5 · Defensa | 4 | Presentación ante el equipo docente: vídeo (5 min) + preguntas (5 min) | Defensa |

Las 50 h son las del módulo. La parte técnica se apoya en lo que ya sabéis hacer de los otros módulos; en estas horas se analiza, planifica, ejecuta con seguimiento, documenta, publica y defiende.
Las fechas concretas de cada hito las fija el profesor al inicio del curso y se anotan en [`CALENDARIO.md`](CALENDARIO.md).

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

## Repositorios y enlaces

| Enlace | Qué hay |
|---|---|
| [`reto_intermodular_2sm`](https://github.com/CIFPZornotzaLHII/reto_intermodular_2sm) | Reto de SMR (2SM): **este repositorio** |
| [`reto_intermodular_wg`](https://github.com/CIFPZornotzaLHII/reto_intermodular_wg) | Reto de DAW (WG) |
| [`reto_intermodular_pg`](https://github.com/CIFPZornotzaLHII/reto_intermodular_pg) | Reto de DAM (PG) |
| [`proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares) | La web de proyectos del centro, donde cada grupo publica el suyo |
| [`proyectos/LEEME.md`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/blob/main/proyectos/LEEME.md) | Guía paso a paso para publicar el proyecto en la web |
| [`proyectos/_plantilla/`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/tree/main/proyectos/_plantilla) | Plantilla de la carpeta del proyecto (tarjeta y landing) |
| [`proyectos/2SM/`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/tree/main/proyectos/2SM) | Los proyectos de SMR publicados en la web |
| [`CALENDARIO.md`](CALENDARIO.md) · [`EVALUACION.md`](EVALUACION.md) · [`IDEAS.md`](IDEAS.md) · [`plantillas/`](plantillas/) | Fechas, rúbrica, ideas y plantillas de este reto |

---

<a id="euskaraz"></a>

# Erronka · Proiektu intermodularra · SMR (SMRko 2. maila)

**CIFP Zornotza LHII · 2026-27 ikasturtea · 1713 modulua, Proiektu intermodularra · 50 h · erdi maila**

**Castellano:** [leer arriba ↑](#castellano)

> Errepositorio hau erronkaren enuntziatua da. Eraikitzen duzuena ikastetxeko proiektuen webgunean argitaratzen da:
> [`CIFPZornotzaLHII/proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares).
> Erronkaren gainerako fitxategiak (egutegia, ebaluazioa, ideiak eta txantiloiak) gaztelaniaz daude.

## Aurkibidea

- [Zer da proiektu intermodularra](#zer-da-proiektu-intermodularra)
- [Erronka](#erronka)
- [Talde bakoitzak zer entregatu behar duen](#talde-bakoitzak-zer-entregatu-behar-duen)
  - [Nola argitaratzen da](#nola-argitaratzen-da)
- [Faseak eta orduak (moduluaren 50 h)](#faseak-eta-orduak-moduluaren-50-h)
- [Ebaluazioa](#ebaluazioa)
- [Ideiak](#ideiak)
- [Txantiloiak](#txantiloiak)
- [Arauak](#arauak)
- [Egutegia](#egutegia)
- [Errepositorioak eta estekak](#errepositorioak-eta-estekak)

## Zer da proiektu intermodularra

Gainerako guztia lotzen duen modulua da: modulu bakoitzean gauza bat ikasi beharrean, benetako behar bat hartu eta
hainbat modulutan dakizuena aldi berean erabiliz konpontzen duzue. Moduluaren ikaskuntza-emaitzekin (IE) ebaluatzen
da, hauekin:

| IE | Zer erakutsi behar duzuen |
|---|---|
| IE1 | Sektoreko enpresak ezaugarritzen ditu: antolaketa, sailak, eskaria, baliabideak eta GJHekin (Garapen Jasangarrirako Helburuak) duten lotura. |
| IE2 | Sektoreko benetako behar bati irtenbide bat proposatzen dio eta proiektu txiki bat garatzen du: bideragarritasuna, aurrekontua, diseinuaren dokumentazioa, kalitatea eta aurkezpen publikoa. |
| IE3 | Exekuzioa planifikatzen du: jardueren sekuentzia, baliabideak, baimenak, arriskuak eta ustekabeak. |
| IE4 | Exekuzioaren jarraipena egiten du: kalitatea egiaztatzen du, desbideratzeak hautematen ditu, zuzentzen ditu eta dokumentatzen du. |
| IE5 | Informazioa argi, ordenatuta eta egituratuta komunikatzen du, IKT tresnekin eta beste hizkuntza batzuetako terminologia teknikoarekin. |

## Erronka

Benetako bezero batek edo errealista batek (enpresa txiki batek, elkarte batek, ikastetxeko sail batek, familia
batek) sistemen edo sareen arazo bat du. Zuen taldeak aztertu egiten du, irtenbide bat proposatzen du, planifikatzen
du, **muntatu egiten du** (Proxmoxen, ikasgelan edo benetako ekipoetan), exekuzioaren jarraipena egiten du eta
aurkeztu egiten du. Amaieran, funtzionatzen duen eta 5 minututan erakus daitekeen zerbait egon behar da: sare bat,
zerbitzari bat, zerbitzu bat, prozedura automatizatu bat.

SMRko proiektu bat klaseko praktika batetik bereizten duena: behar bat duen bezero bat dago, aurrekontu bat, datak
dituen plan bat, aurreikusitako arriskuak, eta exekuzio bat, desbideratzeak erregistratuta eta konponduta dituena.

## Talde bakoitzak zer entregatu behar duen

- **Landing page** bat proiektua aurkezteko, ebaluatzen diren sei atalekin: beharra, irtenbidea, plangintza, demoa, jarraipena eta kontrola, taldea. Ikastetxeko webgunean argitaratzen da (txantiloia webaren errepositorioan dago).
- **Txartela** proiektuen webgunean: `proyectos/<zikloa>/<zuen-proiektua>/` karpeta, `proyecto.json` fitxategiarekin (izenburua, laburpena, taldea, azala, bideoa, errepositorioa). Mailaren etiketa webak jartzen du.
- **5 minutuko aurkezpen-bideoa**, taldea hizketan eta pantaila ikusten direla, ordena honetan: irtenbidea, plangintza, mini demoa, jarraipena eta kontrola. Estekatu egiten da (YouTube edo ikastetxeko Drivea), ez da errepositoriora igotzen.
- **Plangintza-dokumentua** eta **jarraipen-erregistroa** (txantiloiak [`plantillas/`](plantillas/) karpetan), landingetik estekatuta.
- **Benetan exekutatutako zerbait**: maketak, instalazioak, konfigurazioak edo zerbitzuak existitu eta funtzionatu egin behar du demoan. Dokumentu bat bakarrik ez da nahikoa: IE4k exekuzio baten jarraipena eskatzen du.

### Nola argitaratzen da

1. Egin [`CIFPZornotzaLHII/proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares) errepositorioaren fork-a eta klonatu.
2. Kopiatu [`proyectos/_plantilla/`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/tree/main/proyectos/_plantilla) `proyectos/2SM/<proiektuaren-izena>/` karpetara, eta bete `proyecto.json` eta `index.html`.
3. Ireki karpeta hori bakarrik ukitzen duen **pull request** bat. Robotak arauak egiaztatzen ditu; irakasleak onartzen du eta zerbitzaria bere kabuz eguneratzen da.
4. Bideoa bigarren pull request batean irits daiteke, grabatuta dagoenean.

Urratsez urratseko gida (gaztelaniaz): [`proyectos/LEEME.md`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/blob/main/proyectos/LEEME.md).

## Faseak eta orduak (moduluaren 50 h)

| Fasea | Orduak | Zer egiten da | Entregagarria / mugarria |
|---|---|---|---|
| 0 · Abiaraztea | 2 | Taldeak, erronka irakurtzea, ideia aukeratzea ([`IDEAS.md`](IDEAS.md) fitxategitik edo propioa, irakasleak onartuta) | Taldea eta ideia erregistratuta |
| 1 · Analisia | 6 | Benetako beharra, bezeroa edo sektorea, orain nola egiten den, alternatibak (IE1: enpresa ezaugarritzea) | Analisi-fitxa (plangintzaren 1. atala) |
| 2 · Diseinua eta plangintza | 8 | Irismena, eskakizunak, irtenbidearen diseinua, zereginak estimazioarekin, arriskuak, baliabideak eta aurrekontua | **1. mugarria**: plangintza onartuta |
| 3 · Exekuzioa | 22 | Irtenbidea muntatu, instalatu eta konfiguratu. Asteko jarraipen-erregistroa | **2. mugarria**: tarteko berrikuspena, demo partzialarekin |
| 4 · Itxiera | 8 | Landinga, bideoa, pull requesta, azken jarraipen-erregistroa | Proiektua webean argitaratuta |
| 5 · Defentsa | 4 | Irakasle-taldearen aurrean aurkeztea: bideoa (5 min) + galderak (5 min) | Defentsa |

50 orduak moduluarenak dira. Alde teknikoa beste moduluetan dagoeneko egiten dakizuenean oinarritzen da; ordu hauetan aztertu, planifikatu, jarraipenarekin exekutatu, dokumentatu, argitaratu eta defendatu egiten da.
Mugarri bakoitzaren data zehatzak irakasleak finkatzen ditu ikasturtearen hasieran, eta [`CALENDARIO.md`](CALENDARIO.md) fitxategian idazten dira.

## Ebaluazioa

Nota [`EVALUACION.md`](EVALUACION.md) fitxategiko errubrikatik ateratzen da: plangintza, exekuzioa, jarraipena eta kontrola, argitalpena (landinga eta txartela) eta bideoa + defentsa. IE bakoitza entregagarri bati edo batzuei lotuta dago; beraz, entregagarri bat falta bada, IE bat falta da.

## Ideiak

Hasierako hogei ideia, zikloan lantzen dituzuen teknologiekin pentsatuta, [`IDEAS.md`](IDEAS.md) fitxategian. Beste
bat proposa dezakezue: baldintza da bezero edo behar identifikagarri bat izatea eta moduluaren denboran muntatu ahal izatea.

## Txantiloiak

- [`plantillas/planificacion.md`](plantillas/planificacion.md): plangintza-dokumentua (analisia, irismena, zereginak, arriskuak, aurrekontua).
- [`plantillas/seguimiento.md`](plantillas/seguimiento.md): asteko jarraipen- eta kontrol-erregistroa.
- [`plantillas/guion-video.md`](plantillas/guion-video.md): 5 minutuko bideoaren gidoia.

## Arauak

- **Taldeak**: 2 pertsona (3, irakasleak baimentzen badu). Pertsona bakoitzak zeregin esleituak ditu, plangintzan ikusgai: defentsan bakoitzari berea galdetzen zaio.
- **Zintzotasuna jarraipenean.** Desbideratzerik gabe "primeran atera den" plana susmagarria da. Arazoa hautematea, erabakitzea eta idatziz uztea baloratzen da.
- **Adimen artifiziala.** Ikertzeko, idazteko eta programatzeko erabil daiteke, bi baldintzarekin: non erabili den adierazten da, eta entregatzen duzuena azaltzeko eta aldatzeko gai izan behar duzue. Defentsan egiaztatzen da.
- **Plagioa.** Beste baten proiektua kopiatzeak (edo ulertzen ez duzuen zerbait entregatzeak) modulua ez gainditzea dakar.
- **Bideoak eta fitxategi handiak** ez dira errepositoriora igotzen: estekatu egiten dira.
- **Hizkuntza.** Landinga, bideoa eta defentsa taldearen hizkuntzan (gaztelaniaz edo euskaraz); ingelesezko terminologia teknikoa naturaltasunez erabiltzen da (komunikazioaren IE).

## Egutegia

Mugarri bakoitzaren datak [`CALENDARIO.md`](CALENDARIO.md) fitxategian daude (irakasleak finkatzen ditu ikasturtearen hasieran).

## Errepositorioak eta estekak

| Esteka | Zer dago |
|---|---|
| [`reto_intermodular_2sm`](https://github.com/CIFPZornotzaLHII/reto_intermodular_2sm) | SMRko erronka (2SM): **errepositorio hau** |
| [`reto_intermodular_wg`](https://github.com/CIFPZornotzaLHII/reto_intermodular_wg) | DAWko erronka (WG) |
| [`reto_intermodular_pg`](https://github.com/CIFPZornotzaLHII/reto_intermodular_pg) | DAMeko erronka (PG) |
| [`proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares) | Ikastetxeko proiektuen webgunea, talde bakoitzak berea argitaratzen duen tokia |
| [`proyectos/LEEME.md`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/blob/main/proyectos/LEEME.md) | Proiektua webean argitaratzeko urratsez urratseko gida |
| [`proyectos/_plantilla/`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/tree/main/proyectos/_plantilla) | Proiektuaren karpetaren txantiloia (txartela eta landinga) |
| [`proyectos/2SM/`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/tree/main/proyectos/2SM) | Webean argitaratutako SMRko proiektuak |
| [`CALENDARIO.md`](CALENDARIO.md) · [`EVALUACION.md`](EVALUACION.md) · [`IDEAS.md`](IDEAS.md) · [`plantillas/`](plantillas/) | Erronka honen datak, errubrika, ideiak eta txantiloiak |
