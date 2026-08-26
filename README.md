# González Pane c/ Odontología 3 S.A. — Análisis Exhaustive del Caso

> **Repositorio de análisis legal y estratégico del caso laboral de la Dra. Gabriella María González Pane contra Odontología 3 S.A. y el Dr. Roque S. Ramírez Nizza, Asunción, Paraguay.**

> **Status:** Borrador para revisión por el abogado patrocinante (Dr. Carlos).
> **Última actualización:** ver `git log` del repositorio.
> **Privacidad:** los nombres reales están en los documentos internos; este repositorio es **público** por decisión de la persona que lo subió. Si necesitás una versión anonimizada, decime y la genero.

---

## Qué hay aquí

Este repo es un **expediente completo y estratégico** del caso. Incluye:

- **22 documentos markdown** con el análisis jurídico, estratégico, táctico, comunicacional, psicológico, financiero y tecnológico.
- **2 cartas originales escaneadas** (en `documentos/`) — prueba documental principal.
- **38 audios originales** (`.opus`, en `evidencia/`) — la prueba más importante del caso.
- **38 transcripciones** (en `transcripciones/` y `transcripciones_corregidas/`) — realizadas con Whisper y corregidas manualmente.
- **1 chat completo** (`transcripciones/_chat.txt`) — la conversación entre Gabi y su abogado.
- **Hash SHA-256** de todos los archivos (`evidencia/SHA256SUMS.txt`) — cadena de custodia digital.

---

## Estructura

```
.
├── README.md                                       ← este archivo
├── 00-resumen-ejecutivo.md                         ← 1 página con la decisión
├── 01-hechos-y-cronologia.md                       ← timeline + hechos
├── 02-tesis-juridica.md                            ← argumentación legal
├── 03-cuantificacion.md                            ← damages (Gs. 124M–681M)
├── 04-pruebas.md                                   ← inventario probatorio
├── 05-estrategia-procesal.md                       ← plan procesal
├── 06-prescripcion-y-plazos.md                     ← calendar (322 días restantes)
├── 07-seguridad-social-y-tributos.md               ← IPS, SET, MTESS
├── 08-200-areas-de-investigacion.md                ← 200 áreas A–J
├── 09-riesgos-y-contratargumentos.md               ← risk matrix
├── 10-checklist-de-acuerdo.md                      ← settlement checklist
├── 11-comunicaciones-y-negociacion.md              ← negotiation + profiles
├── 12-mapa-evidencia.md                            ← cada hecho ↔ su fuente
├── 13-jurisprudencia.md                            ← precedentes CSJ
├── 14-perfiles-psicologicos.md                     ← Big Five + DISC
├── 15-solvencia.md                                 ← patrimonio demandada
├── 16-borrador-demanda.md                          ← demanda para Carlos
├── 17-plan-medios.md                               ← plan de comunicación externa
├── 18-modelo-financiero.md                         ← VPN + escenarios
├── 19-plan-comunicaciones.md                       ← manual táctico canal × canal
├── 20-plan-upgrade.md                              ← tech, automation, monitoring
├── 21-brief-legal.md                               ← brief con citas
├── 22-indice.md                                    ← mapa general + glosario
├── evidencia/
│   ├── SHA256SUMS.txt                              ← cadena de custodia
│   ├── *.opus (38 archivos)                        ← audios originales
├── documentos/
│   ├── *.jpg (2 archivos)                          ← cartas escaneadas
├── transcripciones/
│   ├── _chat.txt                                   ← chat completo Gabi–Carlos
│   ├── *.txt (38 archivos)                         ← Whisper sin corregir
├── transcripciones_corregidas/
│   ├── *.txt (38 archivos)                         ← Whisper + corrección manual
```

---

## TL;DR

| Concepto | Valor |
|---|---|
| **Tipo de caso** | Acción laboral declarativa + cobro de prestaciones |
| **Demandada** | Odontología 3 S.A. (Dr. Roque S. Ramírez Nizza) |
| **Pretensión principal** | Recharacterización de contrato PS → laboral dependiente |
| **Pretensión subsidiaria** | Reincorporación por estabilidad absoluta (Art. 94 CT) |
| **Antigüedad** | 12 años y 6 meses |
| **Cuantía estimada** | Gs. 300–400M (centro del rango) |
| **Plazo de prescripción** | Hasta 14/07/2027 (322 días restantes al 17/08/2026) |
| **Probabilidad de éxito** | 85–95% (estimación del abogado patrocinante) |
| **VPN esperado del litigio** | Gs. 90.7M netos (354% ROI) |
| **Acción inmediata** | Firma del poder + inicio de oficios al IPS y SET |

---

## Cómo usar este repo

**Si sos el abogado patrocinante (Dr. Carlos):**

1. Empezá por `00-resumen-ejecutivo.md` (1 página).
2. Después `01-hechos-y-cronologia.md` (timeline).
3. Después `16-borrador-demanda.md` (borrador listo para presentar).
4. Después `13-jurisprudencia.md` (citas que faltan verificar).
5. Después `04-pruebas.md` (qué probar y cómo).
6. Después `05-estrategia-procesal.md` (plan procesal paso a paso).

**Si sos la cliente (Dra. Gabi):**

1. `00-resumen-ejecutivo.md`.
2. `01-hechos-y-cronologia.md` para entender tu propio caso.
3. `19-plan-comunicaciones.md` para saber qué decir en cada canal.
4. `20-plan-upgrade.md` para las acciones inmediatas (backup, alertas, etc.).

**Si sos un tercero revisor:**

1. `21-brief-legal.md` (brief formal con citas).
2. `12-mapa-evidencia.md` (cada afirmación con su fuente).
3. `transcripciones_corregidas/` para verificar la prueba testimonial.

---

## Advertencias importantes

1. **Este análisis es preliminar.** Carlos debe verificar las citas jurisprudenciales en el Buscador de Sentencias de la CSJ antes de presentar cualquier escrito.
2. **Las cifras son estimaciones.** Están sujetas a revisión pericial y a la evolución procesal.
3. **Los perfiles psicológicos son orientativos**, no diagnósticos clínicos.
4. **La estrategia puede cambiar** según la evolución del caso y la conducta de la contraparte.

---

## Cómo contribuir

Este repo es un borrador. Si querés agregar análisis, correcciones o jurisprudencia:

1. Fork el repo.
2. Crear una branch con tu cambio.
3. PR contra `main`.
4. Mensaje de PR con resumen del cambio.

---

## Licencia y uso

Documento interno del caso. **No distribuir** sin autorización de la actora o de su abogado patrocinante.

---

## Privacidad

Los nombres reales de las partes están incluidos en este repositorio **por decisión explícita** del usuario que lo subió. Si en algún momento se decide privatizar, el repo puede pasar a **private** desde Settings en GitHub. Si se decide anonimizar, los nombres pueden ser reemplazados por seudónimos en todos los `.md` con un script de `sed`.

Para ver la versión "más limpia" (sin nombres), considerar hacer un branch `anonimizado` en el futuro.

---

## Contacto

Para preguntas sobre el caso, contactar al abogado patrocinante.
Para preguntas sobre el repo, abrir un Issue.

---

*Última revisión: ver `git log`.*
