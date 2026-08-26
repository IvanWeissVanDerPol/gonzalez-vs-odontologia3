# ESTRUCTURA DEL REPOSITORIO

> *Mapa completo de carpetas y archivos. Para una navegación rápida por audiencia, ver `README.md`.*

---

## Vista por carpeta

```
gonzalez-vs-odontologia3/
│
├── README.md                          ← entrada principal del repo
├── ESTRUCTURA.md                      ← este archivo (índice completo)
│
├── 01-entrada/                        ← qué leer primero
│   ├── README.md
│   ├── 01-entrada/00-resumen-ejecutivo.md        (resumen 1 página)
│   └── 01-entrada/22-indice.md                   (índice general + glosario)
│
├── 02-hechos/                         ← qué pasó + prueba
│   ├── README.md
│   ├── 02-hechos/01-hechos-y-cronologia.md
│   ├── 02-hechos/04-pruebas.md
│   └── 02-hechos/12-mapa-evidencia.md
│
├── 03-legal/                          ← argumentación jurídica
│   ├── README.md
│   ├── 03-legal/02-tesis-juridica.md
│   ├── 03-legal/13-jurisprudencia.md
│   ├── 03-legal/16-borrador-demanda.md
│   └── 03-legal/21-brief-legal.md
│
├── 04-estrategia/                     ← estrategia procesal
│   ├── README.md
│   ├── 04-estrategia/05-estrategia-procesal.md
│   ├── 04-estrategia/06-prescripcion-y-plazos.md
│   ├── 04-estrategia/09-riesgos-y-contratargumentos.md
│   ├── 04-estrategia/10-checklist-de-acuerdo.md
│   └── 04-estrategia/30-analisis-adversarial.md
│
├── 05-cuantificacion/                 ← cuánto se pide
│   ├── README.md
│   ├── 05-cuantificacion/03-cuantificacion.md
│   └── 05-cuantificacion/18-modelo-financiero.md
│
├── 06-personas/                       ← quién es quién
│   ├── README.md
│   ├── 06-personas/11-comunicaciones-y-negociacion.md
│   ├── 06-personas/14-perfiles-psicologicos.md
│   └── 06-personas/31-analisis-red-social.md
│
├── 07-comunicacion/                   ← cómo se comunica
│   ├── README.md
│   ├── 07-comunicacion/17-plan-medios.md
│   └── 07-comunicacion/19-plan-comunicaciones.md
│
├── 08-analisis-especializado/         ← análisis verticales
│   ├── README.md
│   ├── 08-analisis-especializado/15-solvencia.md
│   ├── 08-analisis-especializado/23-analisis-tecnico-odontologico.md
│   ├── 08-analisis-especializado/24-analisis-penal.md
│   ├── 08-analisis-especializado/25-analisis-previsional.md
│   ├── 08-analisis-especializado/26-analisis-tributario.md
│   ├── 08-analisis-especializado/27-analisis-administrativo.md
│   ├── 08-analisis-especializado/29-analisis-comparado.md
│   └── 08-analisis-especializado/32-analisis-proyecto.md
│
├── 09-areas-investigacion/            ← qué hay que investigar
│   ├── README.md
│   ├── 09-areas-investigacion/07-seguridad-social-y-tributos.md
│   ├── 09-areas-investigacion/08-200-areas-de-investigacion.md
│   └── 09-areas-investigacion/34-bibliografia-glosario.md
│
├── 10-riesgos-personales/             ← qué puede salir mal para Gabi
│   ├── README.md
│   ├── 10-riesgos-personales/28-analisis-riesgos-gabi.md
│   └── 10-riesgos-personales/33-seguridad-personal.md
│
├── 11-arquitectura-caso/              ← infraestructura operativa
│   ├── README.md
│   └── 20-plan-upgrade.md
│
├── 12-evidencia/                      ← evidencia original (inmutable)
│   ├── README.md                      ← cadena de custodia
│   ├── MANIFEST-SHA256.txt            ← hash de los 153 archivos
│   ├── _chat.txt                      ← chat completo Gabi-Carlos
│   ├── audios/                        ← 38 audios originales .opus
│   ├── cartas-escaneadas/             ← 2 cartas (escaneadas)
│   ├── transcripciones-whisper/       ← 38 transcripciones Whisper
│   └── transcripciones-corregidas/    ← 38 transcripciones corregidas
│
└── 13-templates-procesales/           ← formularios listos para usar
    ├── README.md                      ← índice de templates
    ├── 35-poder-para-juicios.md       ← poder para Carlos
    ├── 36-escrito-conciliacion.md     ← reclamo ante Viceministerio
    ├── 37-oficios.md                  ← 8 oficios (IPS, SET, etc.)
    ├── 38-cartas-documento.md         ← 6 cartas documento
    └── 39-interrogatorios.md          ← preguntas para confesional/testifical
```

---

## Conteo

| Carpeta | Archivos |
|---|---|
| `01-entrada/` | 2 docs + README |
| `02-hechos/` | 3 docs + README |
| `03-legal/` | 4 docs + README |
| `04-estrategia/` | 5 docs + README |
| `05-cuantificacion/` | 2 docs + README |
| `06-personas/` | 3 docs + README |
| `07-comunicacion/` | 2 docs + README |
| `08-analisis-especializado/` | 8 docs + README |
| `09-areas-investigacion/` | 3 docs + README |
| `10-riesgos-personales/` | 2 docs + README |
| `11-arquitectura-caso/` | 1 doc + README |
| `12-evidencia/` | 153 archivos (manifiesto + 38 audios + 2 cartas + 76 transcripciones + chat + README) |
| `13-templates-procesales/` | 5 docs + README |
| **TOTAL** | **40 docs + 117 archivos de evidencia + 13 READMEs + 2 manifests** |

---

## Numeración de documentos

Los documentos conservan su numeración original (00–34) para mantener trazabilidad con el chat y los audios. **La numeración NO coincide con la carpeta donde residen** porque la reorganización ocurrió después de la escritura.

| # | Doc | Carpeta |
|---|---|---|
| 00 | resumen-ejecutivo | `01-entrada/` |
| 01 | hechos-y-cronologia | `02-hechos/` |
| 02 | tesis-juridica | `03-legal/` |
| 03 | cuantificacion | `05-cuantificacion/` |
| 04 | pruebas | `02-hechos/` |
| 05 | estrategia-procesal | `04-estrategia/` |
| 06 | prescripcion-y-plazos | `04-estrategia/` |
| 07 | seguridad-social-y-tributos | `09-areas-investigacion/` |
| 08 | 200-areas-de-investigacion | `09-areas-investigacion/` |
| 09 | riesgos-y-contratargumentos | `04-estrategia/` |
| 10 | checklist-de-acuerdo | `04-estrategia/` |
| 11 | comunicaciones-y-negociacion | `06-personas/` |
| 12 | mapa-evidencia | `02-hechos/` |
| 13 | jurisprudencia | `03-legal/` |
| 14 | perfiles-psicologicos | `06-personas/` |
| 15 | solvencia | `08-analisis-especializado/` |
| 16 | borrador-demanda | `03-legal/` |
| 17 | plan-medios | `07-comunicacion/` |
| 18 | modelo-financiero | `05-cuantificacion/` |
| 19 | plan-comunicaciones | `07-comunicacion/` |
| 20 | plan-upgrade | `11-arquitectura-caso/` |
| 21 | brief-legal | `03-legal/` |
| 22 | indice | `01-entrada/` |
| 23 | analisis-tecnico-odontologico | `08-analisis-especializado/` |
| 24 | analisis-penal | `08-analisis-especializado/` |
| 25 | analisis-previsional | `08-analisis-especializado/` |
| 26 | analisis-tributario | `08-analisis-especializado/` |
| 27 | analisis-administrativo | `08-analisis-especializado/` |
| 28 | analisis-riesgos-gabi | `10-riesgos-personales/` |
| 29 | analisis-comparado | `08-analisis-especializado/` |
| 30 | analisis-adversarial | `04-estrategia/` |
| 31 | analisis-red-social | `06-personas/` |
| 32 | analisis-proyecto | `08-analisis-especializado/` |
| 33 | seguridad-personal | `10-riesgos-personales/` |
| 34 | bibliografia-glosario | `09-areas-investigacion/` |
| 35 | poder-para-juicios | `13-templates-procesales/` |
| 36 | escrito-conciliacion | `13-templates-procesales/` |
| 37 | oficios | `13-templates-procesales/` |
| 38 | cartas-documento | `13-templates-procesales/` |
| 39 | interrogatorios | `13-templates-procesales/` |

---

## Flujo de lectura recomendado

```
[01-entrada/00-resumen-ejecutivo.md]
        ↓
[02-hechos/01-hechos-y-cronologia.md]   ← entender el caso
        ↓
[02-hechos/12-mapa-evidencia.md]         ← ver de dónde sale cada hecho
        ↓
[03-legal/02-tesis-juridica.md]         ← entender el argumento legal
        ↓
[03-legal/16-borrador-demanda.md]       ← ver la demanda formal
        ↓
[04-estrategia/05-estrategia-procesal.md] ← entender el plan procesal
        ↓
[04-estrategia/06-prescripcion-y-plazos.md] ← saber qué plazos vencen
        ↓
[05-cuantificacion/03-cuantificacion.md] ← ver cuánto se pide
        ↓
[05-cuantificacion/18-modelo-financiero.md] ← entender el VPN
        ↓
[06-personas/14-perfiles-psicologicos.md] ← entender las partes
        ↓
[08-analisis-especializado/] (a demanda)
[09-areas-investigacion/] (a demanda)
[10-riesgos-personales/] (a demanda)
[11-arquitectura-caso/20-plan-upgrade.md] ← ver la infraestructura
        ↓
[12-evidencia/] ← evidencia original (inmutable)
```

---

*Este archivo es un índice maestro. Se actualizará si se agregan nuevas carpetas o documentos.*
