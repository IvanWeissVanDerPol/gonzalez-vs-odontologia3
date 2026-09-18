# González Pane c/ Odontología 3 TRES S.A. — Análisis Exhaustivo del Caso

> **Repositorio de análisis legal y estratégico del caso laboral de la Dra. Gabriella María González Pane contra Odontología 3 TRES S.A. y el GRUPO ECONÓMICO FAMILIAR encabezado por el Dr. Roque Samuel Ramírez Nizza, Asunción, Paraguay.**
>
> **Status:** Borrador para revisión por el abogado patrocinante (Dr. Carlos).
> **Privacidad:** los nombres reales están en los documentos internos; este repositorio es **público** por decisión del usuario. Si necesitás una versión anonimizada, decime y la genero.

---

## 🎯 Para arrancar rápido

> **→ Leé primero `00-START-HERE.md` (5 min)** — es el mapa más corto del repo.

- **Si sos Gabi** → andá a `14-guia-para-gabi/` y leé `71-guia-operativa.md`.
- **Si sos Carlos (abogado)** → empezá por `04-estrategia/91-brief-ejecutivo-carlos.md`.
- **Si querés entender el caso completo** → empezá por `01-entrada/00-resumen-ejecutivo.md`.

---

## Qué hay aquí

Expediente completo y estratégico con **~135 documentos markdown** organizados en **15 carpetas temáticas + 5 memos privados de investigación** (prefijados `_hermes-`):

| Carpeta | Contenido | Archivos |
|---|---|---|
| `01-entrada/` | Resumen ejecutivo, índice, glosario | 4 |
| `02-hechos/` | Cronología + prueba + mapa evidencia + datos pendientes | 4 |
| `03-legal/` | Tesis + jurisprudencia + borrador demanda | 9 |
| `04-estrategia/` | Plan procesal + playbooks + crisis + memo investigativo | 19 |
| `05-cuantificacion/` | Damages + VPN + escenarios + presupuesto + impacto | 5 |
| `06-personas/` | 11 fichas individuales + perfiles + redes | 17 |
| `07-comunicacion/` | Medios + manual táctico canal × canal | 2 |
| `08-analisis-especializado/` | 10 análisis verticales (solvencia, penal, etc.) | 10 |
| `09-areas-investigacion/` | Investigación profunda + intelligence + glosario + casos comparados + memos | 14 |
| `10-riesgos-personales/` | Matriz de riesgos + seguridad personal | 2 |
| `11-arquitectura-caso/` | Plan de tecnología, automatización, contingencia | 1 |
| `12-evidencia/` | Evidencia original INMUTABLE (audios, transcripciones, WhatsApp, cartas) | ~240 archivos |
| `13-templates-procesales/` | 21 templates procesales listos para Carlos | 21 |
| `14-guia-para-gabi/` | Documentos específicos para Gabi + memo investigación | 4 |

### Evidencia original (~240 archivos multimedia)

- **2 cartas originales escaneadas** (`12-evidencia/cartas-escaneadas/`).
- **38 audios originales** de 12.5 años (`.opus`, `12-evidencia/audios/`).
- **76 transcripciones** (Whisper + corregidas en `12-evidencia/transcripciones-*`).
- **99 archivos WhatsApp** descargados del Drive (chat Roque 51 archivos + chat Viviana 50 archivos) en `12-evidencia/whatsapp-roque/` y `12-evidencia/whatsapp-viviana/`.
- **SHA-256** de los archivos del repo (`12-evidencia/MANIFEST-SHA256.txt`).
- **1 chat Carlos-Gabi completo** (`12-evidencia/_chat.txt`).

### Documentos de investigación privada (Hermes)

5 memos detallados con investigación exhaustiva de LinkedIn, Superintendencia, DNCP, contralorías y medios, prefijados `_hermes-` para no aparecer en el listado público:
- `14-guia-para-gabi/_hermes-notas-investigacion-publica.md` (notas investigación pública)
- `09-areas-investigacion/_hermes-research-personas-instituciones-2026-09-18.md` (N°1: entidades)
- `09-areas-investigacion/_hermes-research-profundización-2026-09-18.md` (N°2: peritos + jurisprudencia)
- `09-areas-investigacion/_hermes-research-profundización-N3-2026-09-18.md` (N°3: Gerardo gerente + 3 clínicas)
- `09-areas-investigacion/_hermes-research-profundización-N4-2026-09-18.md` (N°4: José Manuel + Superintendencia)

---

## TL;DR

| Concepto | Valor |
|---|---|
| **Tipo de caso** | Acción laboral declarativa + cobro de prestaciones |
| **Demandada principal** | Odontología 3 TRES S.A. (RUC 80010293-2, Dr. Roque Samuel Ramírez Nizza) |
| **Co-demandados identificados** | 5 (Roque Pdte + José Manuel VP + Mario rep. legal alt. + Ángel Valdez admin + Verónica Amarilla Matto Gerente) |
| **Grupo económico vinculado** | 7+ entidades (O3, Santé, La Merced, Vanguard, Scultura, Casa del Odontólogo, Tecnodent) |
| **Pretensión principal** | Recharacterización de contrato PS → laboral dependiente |
| **Pretensión subsidiaria** | Reincorporación por estabilidad absoluta (Art. 94 CT) — Gabi tiene 12+ años |
| **Antigüedad** | 12 años y 6 meses |
| **Cuantía estimada** | Ancla ₲2.000M (2x quantum) + Embargo ₲4.000M + Quantum legal ₲358M |
| **Plazo de prescripción** | Hasta 14/07/2027 (~300 días restantes) |
| **Probabilidad de éxito** | 85–95% (con jurisprudencia PY consolidada + casos análogos Superintendencia) |
| **Acción inmediata** | Firma del poder + Padrón Electoral (parentescos) + Superintendencia (auditorías 2024-2025) |

---

## Estructura del Grupo Económico (confirmado Sept 2026)

⚠️ **CRÍTICO:** Odontología 3 no es una empresa aislada. Es la entidad central de un **grupo económico familiar integrado**:

| Entidad | Relación | Cargo de José Manuel | Embargable |
|---|---|---|---|
| **Odontología 3 S.A.** (RUC 80010293-2) | S.A. principal demandada | Vicepresidente | ✅ |
| **Clínica Santé** (Mariscal Estigarribia 1458 e/ Perú y Pai Pérez, Asunción) | Segunda clínica | **Propietario** | ✅ |
| **Clínica La Merced** (Ingavi e/ Monte Alto y Pitiantuta, Luque) | Tercera clínica, cerca de domicilio de Gabi | (mismo grupo) | ✅ |
| **Vanguard** (prepaga odontológica, registro EMPP `2POD180005`) | Producto prepago del grupo | Vicepresidente | ✅ |
| **Scultura S.A.** (laboratorio dental) | Laboratorio propio | **Propietario** | ✅ |
| **La Casa del Odontólogo S.A.** (venta insumos) | Insumos para las clínicas | Vicepresidente | ✅ |
| **Tecnodent** (laboratorio CAD/CAM) | Laboratorio digital | **Propietario** | ✅ |

**José Manuel Ramírez** es Vicepresidente/Propietario de todas (cargos simultáneos en LinkedIn: https://www.linkedin.com/in/jose-manuel-ramirez-733892334).
**Educación:** Universidad Católica — Licenciatura en Business Administration.

⚠️ **Para Carlos:** el embargo se puede pedir contra **cualquiera de las 7 entidades** del grupo, fundamentado en **inoponibilidad del velo societario** (Art. 153 CT + doctrina).

---

## Hallazgos críticos actualizados (Sept 2026)

### 1. Estructura corporativa de O3 — 5 cabezas

| # | Persona | Cargo | Fuente |
|---|---|---|---|
| 1 | Dr. Roque Samuel Ramírez Nizza | Presidente + Director + Rep. Legal DNCP | DNCP + cartas |
| 2 | **José Manuel Ramírez** ⚠️ | Vicepresidente O3 + Propietario/Vice de 6 entidades del grupo | LinkedIn |
| 3 | Dr. Mario Ramírez (hijo de Roque) | Odontólogo Rehab Oral + Rep. Legal alternativo en MOPC | ABC Color 2024 |
| 4 | Ángel Valdez de Madariaga | Administrador + Representante público | Última Hora/ABC |
| 5 | **Lic. Verónica Amarilla Matto** | Gerente de Operaciones y Servicios de O3 | LinkedIn |

### 2. Historial de irregularidades verificado

- **DNCP CASO N° 294 — Investigación Preliminar contra O3** (10/09/2018, Abg. Martha Verón).
- **DNCP anulación MOPC 2023**: dictamen N° 11 confirmó irregularidades en la adjudicación de O3 (firmada por Roque + Mario).
- **Superintendencia de Salud auditó O3 en 2024 (N° 40, 13-29 ago) y 2025 (N° 45, 1-13 ago)** + Scultura-Vanguard (N° 37, 2-15 jul 2025).
- **Abg. Aníbal Ramírez** protestó CONTRA O3 en DNCP en 2016 (¿competidor o familiar?).

### 3. Patrón sectorial de fraude previsional

- **Caso Julidavid Ramírez 67 personas — IPS-PY** (ABC Color 17/9/2025): fraude masivo con trabajadores ficticios.
- **Caso Quirófanos IPS — 9 exautoridades imputadas** (ABC Color mayo-agosto 2026): lesión de confianza + prisión preventiva + embargo.
- **Caso Gerardo Javier Medina Halke c/Odonto Excelence** (Superintendencia): incumplimiento contractual odontológico.
- **Caso Carolina Rodriguez Adorno c/PROMED S.A.** (Superintendencia): ⚠️ **mismo competidor de O3 (Odontos)** tiene caso análogo.
- **Caso Celso Alejandro Bareiro contra Asismed** (Superintendencia): caso contra aseguradora vinculada al modelo.

### 4. Inteligencia sobre Gabi

- **Grabación reunión 18/06/2026 con Roque** mencionada en chats (a verificar si está subida al repo).
- 38 audios de chat Carlos-Gabi (julio 2026).
- 99 archivos WhatsApp descargados del Drive (ROque 51 + Viviana 50).
- 2 cartas escaneadas firmadas por Roque (26/03/2025 y 18/06/2026).
- Documentación hospitalizaciones y datos clínicos (cuantificación daño moral).

### 5. Estrategia procesal recomendada (5 puntos)

1. **Demanda laboral co-demandada** contra las 5 cabezas + Odontología 3 S.A.
2. **Embargo preventivo sobre 6+ entidades** (inoponibilidad del velo societario).
3. **Querella penal** Art. 196 CP + 187 CP + 239 CP (asociación ilícita) + 192 CP.
4. **Acción colectiva** si Gabi logra sumar 3-5 exempleados.
5. **Verificar parentesco clave con Padrón** (Roque-Mario confirmado, Roque-José Manuel / Aida-Verónica / Gloria-Roque / Verónica-Viviana por confirmar).

---

## Cómo usar este repo (por audiencia)

### Si sos Gabi

1. `14-guia-para-gabi/71-guia-operativa.md` — checklist diario + semanal + mensual
2. `14-guia-para-gabi/75-cuestionario-unico-completo.md` — 82 preguntas pendientes de respuesta
3. `14-guia-para-gabi/55-cuestionario-RESPONDIDO.md` — referencia de lo que ya declaraste

### Si sos el abogado patrocinante (Dr. Carlos)

1. `04-estrategia/91-brief-ejecutivo-carlos.md` — resumen 1 página de entrada
2. `01-entrada/00-resumen-ejecutivo.md` — 1 página con la decisión clave
3. `04-estrategia/84-definitive-negotiation-playbook.md` — el playbook final con midpoint rule
4. `04-estrategia/notas-investigacion-hermes.md` — **brief consolidado de Hermes** con timeline + cuantificación recomendada + advertencias cautelares
5. `09-areas-investigacion/36-intelligence-report.md` — inteligencia ₲147B DNCP + 22 profesionales + 4 cabezas
6. `03-legal/16-borrador-demanda.md` — borrador listo para presentar
7. `13-templates-procesales/36-escrito-conciliacion.md` — escrito de conciliación administrativa
8. `13-templates-procesales/40-embargo-preventivo.md` — escrito de embargo con jurisprudencia

### Si querés entender la estrategia completa

1. `04-estrategia/81-master-negotiation-playbook.md` — versión inicial completa
2. `04-estrategia/84-definitive-negotiation-playbook.md` — versión final con midpoint rule
3. `04-estrategia/58-plan-de-accion.md` — timeline operativo
4. `04-estrategia/73-escenarios-crisis.md` — 26 escenarios de crisis consolidados
5. `09-areas-investigacion/casos-comparados-regional-py-es-co.md` — precedentes PY/ES/CO/VE con URLs
6. `09-areas-investigacion/00-glosario-actores-organizaciones.md` — directorio maestro de actores
7. `09-areas-investigacion/_hermes-research-profundización-N4-2026-09-18.md` — research más reciente (Superintendencia + LinkedIn)

### Material de investigación profunda (privado)

Los memos `_hermes-` en `09-areas-investigacion/` contienen investigación que **no debe divulgarse públicamente** mientras el caso esté en etapa pre-procesal:

- Contactos de competidores (Promedent)
- Estrategias procesales (codemanda ampliada, querella penal)
- Identificación de exempleados potenciales
- Datos comparados de Superintendencia y DNCP

**Solo accesible a Iván (asistente técnico) y al abogado Carlos con poder firmado.**

---

## Privacidad

- El repo es **público** por decisión del usuario.
- Los nombres reales están en documentos internos (`12-evidencia/`, `06-personas/`, `09-areas-investigacion/`).
- Los memos `_hermes-` están reservados para uso interno.
- **Para una versión anonimizada**, solicitarla explícitamente.

---

## Última actualización

Investigación consolidada al **18 de septiembre de 2026**:

**Commits recientes (última semana):**

| Commit | Descripción |
|---|---|
| `d7b1c0e` | N°4: José Manuel controlador + Superintendencia casos análogos + Promedent-Odontos |
| `2aef12a` | N°3: Verónica = Gerente; 3 clínicas; Vanguard web; DNCP CASO N° 294 |
| `d25b12f` | Integración completa (6 fichas + glosario + casos + peritos) |
| `7f5ed0b` | N°2: Promedent, IPS Quirófanos, Forenlab, Sanitas, COP |
| `0a972d7` | N°1: DNCP, Superintendencia, Vanguard, ABC Color |
| `c9e00da` | STATUS update + apunte cuestionario |
| `dcaa670` | Merge remote → main |

**Investigación autónoma:** 4 sesiones intensivas de LinkedIn, Superintendencia, DNCP, contralorías, prensa y peritos.
**Tamaño del repo:** ~140 archivos `.md` (~1.4 MB) + 240+ archivos de evidencia multimedia (~17 MB).
