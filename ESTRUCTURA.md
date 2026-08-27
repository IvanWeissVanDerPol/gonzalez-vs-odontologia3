# Estructura del Repositorio

> *Mapa completo de carpetas y archivos.*

## Estructura General

```
gonzalez-vs-odontologia3/
├── README.md                          ← entrada principal
├── ESTRUCTURA.md                      ← este archivo
│
├── 01-entrada/                        ← entrada y resumen (4 files)
│   ├── 00-resumen-ejecutivo.md        (resumen 1 página)
│   ├── 22-indice.md                   (índice general)
│   ├── 56-analisis-40-roles.md        (análisis multiperspectiva)
│   └── 79-resumen-integral.md         (resumen ejecutivo integral)
│
├── 02-hechos/                         ← hechos y prueba (4 files)
│   ├── 01-hechos-y-cronologia.md      (cronología + hechos)
│   ├── 04-pruebas.md                  (inventario probatorio)
│   ├── 12-mapa-evidencia.md           (cada hecho ↔ fuente)
│   └── 63-datos-reales-pendientes.md  (datos que Carlos debe obtener)
│
├── 03-legal/                          ← argumentación jurídica (8 files)
│   ├── 02-tesis-juridica.md           (teoría legal)
│   ├── 13-jurisprudencia.md           (jurisprudencia CSJ + OIT)
│   ├── 16-borrador-demanda.md         (borrador de demanda)
│   ├── 66-bloque-constitucionalidad.md (Art. 137 CN + tratados)
│   ├── 74-analisis-jurisprudencia-comparada.md (AR/BR/CL/ES)
│   ├── 75-doctrina-laboral-paraguaya.md (doctrina nacional)
│   └── 78-analisis-prueba.md          (estrategia probatoria)
│
├── 04-estrategia/                     ← estrategia procesal (12 files)
│   ├── 05-estrategia-procesal.md      (plan paso a paso)
│   ├── 06-prescripcion-y-plazos.md    (322 días restantes)
│   ├── 09-riesgos-y-contratargumentos.md (defensa anticipada)
│   ├── 10-checklist-de-acuerdo.md     (negociación)
│   ├── 30-analisis-adversarial.md     (estrategia de Rooney)
│   ├── 62-investigacion-profund.md    (investigación profunda)
│   ├── 67-analisis-juez-asuncion.md   (perfil del juez)
│   ├── 69-cronograma-realista.md      (timeline con fechas)
│   ├── 73-escenarios-negativos.md     (12 peores casos)
│   ├── 76-estrategia-conciliacion-profundizada.md (negociación detallada)
│   └── 77-analisis-plazos-procesales.md (todos los plazos)
│
├── 05-cuantificacion/                  ← números y dinero (3 files)
│   ├── 03-cuantificacion.md           (memoria de cálculo)
│   ├── 18-modelo-financiero.md        (VPN y escenarios)
│   └── 68-presupuesto-total-caso.md   (presupuesto detallado)
│
├── 06-personas/                       ← personas y redes (6 files)
│   ├── 11-comunicaciones-y-negociacion.md (tácticas)
│   ├── 14-perfiles-psicologicos.md    (Big Five + DISC)
│   ├── 31-analisis-red-social.md      (mapa de contactos)
│   ├── 55-cuestionario-para-gabi.md   (cuestionario original)
│   ├── 71-checklist-diario-gabi.md    (checklist semanal)
│   └── 72-analisis-redes-asia.md      (redes profesionales)
│
├── 07-comunicacion/                   ← medios y prensa (2 files)
│   ├── 17-plan-medios.md               (plan de comunicación)
│   └── 19-plan-comunicaciones.md       (manual táctico canal × canal)
│
├── 08-analisis-especializado/          ← análisis especializados (9 files)
│   ├── 15-solvencia.md                (patrimonio de la demandada)
│   ├── 23-analisis-tecnico-odontologico.md (especialidades de Gabi)
│   ├── 24-analisis-penal.md           (tipos penales aplicables)
│   ├── 25-analisis-previsional.md     (IPS y jubilación)
│   ├── 26-analisis-tributario.md      (IRP, IVA)
│   ├── 27-analisis-administrativo.md  (MTESS, SET, etc.)
│   ├── 29-analisis-comparado.md       (doctrina comparada)
│   └── 32-analisis-proyecto.md        (consultorio propio)
│
├── 09-areas-investigacion/            ← investigación y bibliografía (5 files)
│   ├── 07-seguridad-social-y-tributos.md (IPS/SET)
│   ├── 08-200-areas-de-investigacion.md (200 áreas)
│   ├── 34-bibliografia-glosario.md    (doctrina + glosario)
│   ├── 64-analisis-licitaciones-publicas.md (hallazgo crítico)
│   └── 65-analisis-jurisprudencia-internacional.md (CEDH, OIT)
│
├── 10-riesgos-personales/             ← riesgos para Gabi (2 files)
│   ├── 28-analisis-riesgos-gabi.md    (matriz de riesgos)
│   └── 33-seguridad-personal.md        (seguridad personal)
│
├── 11-arquitectura-caso/              ← infraestructura operativa (1 file)
│   └── 20-plan-upgrade.md              (backup, alertas, etc.)
│
└── 12-evidencia/                      ← evidencia original (INMUTABLE)
    ├── README.md                       (cadena de custodia)
    ├── MANIFEST-SHA256.txt             (hash de los archivos)
    ├── _chat.txt                       (chat completo Gabi-Carlos)
    ├── audios/                         (38 archivos .opus)
    │   └── 00000028-AUDIO-2026-07-10-19-11-07.opus
    │   └── ...
    ├── cartas-escaneadas/             (2 archivos .jpg)
    │   ├── 00000020-PHOTO-2026-07-10-19-08-51.jpg
    │   └── 00000044-PHOTO-2026-07-10-19-19-07.jpg
    ├── transcripciones-whisper/        (38 .txt - Whisper raw)
    │   └── 00000028-AUDIO-2026-07-10-19-11-07.txt
    │   └── ...
    └── transcripciones-corregidas/     (38 .txt - corregidas)
        └── 00000028-AUDIO-2026-07-10-19-11-07.txt
        └── ...
```

## Conteo por Carpeta

| Carpeta | Archivos .md |
| |---|
| `01-entrada/` | 4 |
| `02-hechos/` | 4 |
| `03-legal/` | 7 |
| `04-estrategia/` | 12 |
| `05-cuantificacion/` | 3 |
| `06-personas/` | 6 |
| `07-comunicacion/` | 2 |
| `08-analisis-especializado/` | 8 |
| `09-areas-investigacion/` | 5 |
| `10-riesgos-personales/` | 2 |
| `11-arquitectura-caso/` | 1 |
| `12-evidencia/` | 41 (audios + cartas + transcripciones) |
| **TOTAL** | **54 docs + 117 archivos de evidencia** |

## Convenciones de Nomenclatura

- **00-XX:** Documentos de entrada (resumen ejecutivo, índice).
- **01-XX:** Hechos y prueba.
- **02-XX:** Tesis jurídica (legacy numbering).
- **03-XX:** Estrategia procesal.
- **04-XX:** (no se usa, los docs están en 02-12)
- **05-XX:** Cuantificación.
- **06-XX:** Personas y perfiles.
- **07-XX:** Comunicación.
- **08-XX:** Análisis especializado.
- **09-XX:** Investigación.
- **10-XX:** Riesgos personales.
- **11-XX:** Arquitectura.
- **12-XX:** Evidencia (inmutable).
- **13-XX:** Templates procesales (legacy).

## Conteo por Tipo de Documento

- **Análisis jurídico:** 8 docs.
- **Estrategia procesal:** 12 docs.
- **Hechos y prueba:** 4 docs.
- **Personas y perfiles:** 6 docs.
- **Análisis especializado:** 8 docs.
- **Investigación:** 5 docs.
- **Cuantificación:** 3 docs.
- **Comunicación:** 2 docs.
- **Riesgos:** 2 docs.
- **Arquitectura:** 1 doc.
- **Entrada y resumen:** 4 docs.

**Total docs de análisis:** 54 archivos .md.

## Cómo Usar Este Repositorio

### Por audiencia

**Carlos (abogado):**
1. Empezar por `01-entrada/00-resumen-ejecutivo.md`.
2. `02-hechos/01-hechos-y-cronologia.md` y `02-hechos/12-mapa-evidencia.md`.
3. `03-legal/02-tesis-juridica.md` y `03-legal/13-jurisprudencia.md`.
4. `03-legal/16-borrador-demanda.md` para el escrito inicial.
5. `03-legal/75-doctrina-laboral-paraguaya.md` para fundamentos.
6. `04-estrategia/05-estrategia-procesal.md` para el plan.
7. `04-estrategia/77-analisis-plazos-procesales.md` para los plazos.

**Gabi (cliente):**
1. `01-entrada/00-resumen-ejecutivo.md`.
2. `06-personas/55-cuestionario-para-gabi.md` para responder preguntas.
3. `06-personas/71-checklist-diario-gabi.md` para el día a día.
4. `10-riesgos-personales/33-seguridad-personal.md` para cuidarse.
5. `01-entrada/79-resumen-integral.md` para el resumen completo.

**Tercero revisor:**
1. `01-entrada/00-resumen-ejecutivo.md`.
2. `03-legal/02-tesis-juridica.md` y `03-legal/16-borrador-demanda.md`.
3. `02-hechos/12-mapa-evidencia.md` para verificar cada afirmación.
4. `12-evidencia/audios/` y `12-evidencia/transcripciones-corregidas/` para verificar la prueba.

## Búsqueda Rápida

- **Por tema:** ver carpetas 02-12.
- **Por urgencia:** ver `04-estrategia/`.
- **Por persona:** ver `06-personas/`.
- **Por monto:** ver `05-cuantificacion/`.
- **Por riesgo:** ver `10-riesgos-personales/`.

---

*Última actualización: ver git log del repositorio.*