# 04 · Pruebas

> *Inventario probatorio, cadena de custodia, prueba anticipada a producir.*

---

## 1. Prueba disponible (incorporada)

### 1.1. Documental

| Doc | Descripción | Valor probatorio | Hash |
|---|---|---|---|
| `documentos/00000020-PHOTO-2026-07-10-19-08-51.jpg` | Carta 18/06/2026, suscrita por Dr. Roque como "Auditor Odontólogo" | **Alto** | 32696630… |
| `documentos/00000044-PHOTO-2026-07-10-19-19-07.jpg` | Carta 26/03/2025, suscrita por Dr. Roque como "Director – Presidente/Director General" | **Muy alto** | 02693733… |

**Cadena de custodia:**
1. Descargado de Google Drive (enlace compartido) el 26/08/2026.
2. Extraído del ZIP con `python -c "import zipfile; zipfile.ZipFile(...).extractall(...)"`.
3. Copiado al directorio `documentos/` del repositorio.
4. Hasheado en SHA-256 (ver `evidencia/SHA256SUMS.txt`).

**Cadena completa documentada en `evidencia/SHA256SUMS.txt`** — útil para acreditar integridad ante el juzgado.

### 1.2. Audiovisual

| Doc | Descripción | Valor probatorio |
|---|---|---|
| `evidencia/00000028-...opus` (y 37 más) | 38 notas de voz del chat, en formato original .opus | **Muy alto** |

**Cadena de custodia:**
1. Descargadas del ZIP extraído de Google Drive.
2. Convertidas a WAV 16kHz mono (`/tmp/gdrive_wav/`).
3. Transcritas con Whisper small (`/transcripciones/*.txt`).
4. Originales .opus preservados en `evidencia/`.

**Hash SHA-256** de cada archivo disponible en `evidencia/SHA256SUMS.txt`.

### 1.3. Transcripciones

| Doc | Descripción |
|---|---|
| `transcripciones/00000028-...txt` (y 37 más) | Transcripción verbatim de cada audio, generada con Whisper small (es) |

**Ventajas de la transcripción:**
- Facilita la lectura por parte del juzgado (los audios .opus no son directamente reproducibles por el sistema judicial sin conversión).
- Permite citar textualmente en la demanda.
- Genera un **registro escrito** con marca temporal.

**Limitaciones de la transcripción automatizada:**
- Errores fonéticos en nombres propios y jerga odontológica (ver Apéndice A).
- No diferencia hablantes si la voz es la misma persona (es el caso aquí: todos los audios son de Gabi).

### 1.4. Confesional

**La propia Gabi es la mejor testigo.** Todos los hechos relevantes del expediente provienen de su propia voz. La confesional de Gabi **ratifica** la laboralidad.

### 1.5. Testimonial disponible (potencial)

| Testigo | Tema | Posición actual | Disponibilidad |
|---|---|---|---|
| Manuel Amelio (ex-esposo) | Ingreso por gestión personal de Roque; masonería | Divorciado de Gabi; "no quiere firmar nada" (audio 73); "le conoce a Roque y la masonería" | **Media-baja.** Gabi quiere mantenerlo al margen. |
| Otros odontólogos de la clínica | Si los hay, mismo régimen de contrato de PS | A identificar | **A verificar.** |
| El "licenciado" de RR.HH. | La declaración "no pagamos nada" (audio 43) | Identidad desconocida | **A identificar.** |
| La Coordinadora General | Quién impartía las directivas | Identidad desconocida | **A identificar.** |

---

## 2. Prueba anticipada a producir

### 2.1. Antes de la demanda (urgente)

#### a) Certificado de inscripción en IPS de Gabi

**Solicitar al IPS** (sede central o regional) si **Gabriella María González Pane, CI [a completar]**, figura como asegurada activa, inactiva, o nunca inscripta.

- **Resultado probable:** nunca inscripta. Esto es **prueba de oro** de la relación laboral encubierta.

**Documento a obtener:** Constancia expedida por el Departamento de Aportes y Cotizaciones del IPS.

#### b) Certificado de RUC de Odontología 3 S.A.

**Solicitar a la SET** (Subsecretaría de Estado de Tributación):
- RUC de Odontología 3 S.A.
- Representante legal vigente (¿es el Dr. Roque Ramírez Nizza?).
- Última DDJJ de IVA y de IRP.
- Domicilio fiscal.

#### c) Estatutos y poderes del Dr. Roque Ramírez Nizza

**Solicitar al Registro Público de Comercio:**
- Estatutos de Odontología 3 S.A.
- Última asamblea de accionistas.
- Poderes vigentes del Dr. Roque Ramírez Nizza como Director / Presidente.

> **Objetivo:** acreditar que el firmante de las cartas estaba o no habilitado para representar a la sociedad. Si **no estaba habilitado**, las cartas podrían ser nulas (lo que paradójicamente beneficiaría a Gabi porque evidencia la informalidad del vínculo).

#### d) Antecedentes del Viceministerio del Trabajo

**Solicitar al Viceministerio del Trabajo** si Odontología 3 S.A. fue inspeccionada alguna vez, y si tiene o tuvo sanciones administrativas.

#### e) Libreta de trabajo / constancia de aportes

**Solicitar al IPS** si existe libreta de trabajo de Gabi. Si no existe, refuerza la no-inscripción.

### 2.2. Después de la demanda

#### a) Oficios al IPS

Que el IPS remita:
- Copia del legajo del empleador Odontología 3 S.A.
- Constancia de si Gabi fue incluida alguna vez en planillas.
- Constancia de si la empresa tiene deuda previsional.

#### b) Oficios a la SET

Que la SET remita:
- DDJJ de IRP e IVA de Odontología 3 S.A. de los últimos 5 años.
- Comprobantes de retención en la fuente (si los hubo) sobre los pagos a Gabi.

> **Si la SET informa que Odontología 3 S.A. retuvo IRP a Gabi**, esto acredita el vínculo laboral (la retención solo se aplica a dependientes). Si **no retuvo**, es porque la relación era formalmente "independiente" — lo que refuerza la tesis de simulación.

#### c) Oficios al Viceministerio del Trabajo

Que el Viceministerio remita:
- Inspecciones previas a Odontología 3 S.A.
- Habilitación del consultorio (¿cumple las normas de higiene y seguridad?).
- Denuncias previas de trabajadores.

#### d) Testigos

**Tómese declaración testimonial** de:
1. **Otros profesionales** de la clínica que estén en la misma situación.
2. **Pacientes** que puedan atestiguar la continuidad y regularidad de la atención de Gabi.
3. **Personal administrativo** de la clínica que conozca la rutina de horarios.
4. **Manuel Amelio**, si Gabi lo autoriza (probabilidad baja, audio 73).

#### e) Pericia contable

Sobre los libros de la clínica (Art. 122 CT — libro de sueldos y jornales, libros contables). Verificar:
- Pagos realizados a Gabi.
- Retenciones fiscales y previsionales.
- Porcentaje o monto fijo.

#### f) Reconocimiento judicial

Del consultorio y del sistema de turnos (si Gabi todavía conserva acceso por algún canal).

#### g) Prueba informática

- **Pericia sobre el celular de Gabi**: extracción forense de los mensajes de WhatsApp con la clínica (con hash MD5/SHA-256 de cada mensaje).
- **Pericia sobre los audios**: confirmación de fecha, hora y duración (ya parcialmente realizada por Whisper con timestamps).
- **Verificación de la cadena de custodia** de los archivos del expediente.

---

## 3. Valoración probatoria del material

### 3.1. ¿Son válidos los audios como prueba?

**Sí.** Conforme a la **Ley N° 7.163/2024** (modernización procesal) y a la **jurisprudencia de la CSJ**, las comunicaciones electrónicas tienen pleno valor probatorio siempre que se acredite:
1. Autenticidad (que provienen del dispositivo de la persona que los emitió).
2. Integridad (que no han sido alterados).
3. Pertinencia (que se refieren a los hechos del juicio).

**Estrategia procesal:**
- Acompañar la exportación del chat en formato `.txt` (incluye metadatos: fecha, hora, autor).
- Acompañar las transcripciones de los audios con indicación del modelo y configuración de Whisper.
- Solicitar **pericia informática forense** sobre el celular de Gabi para autenticar origen.

### 3.2. ¿Las fotos de los documentos son válidas?

**Sí**, con confirmación posterior. La CSJ acepta fotografías de documentos siempre que:
- Sean legibles.
- Se acompañen del original o copia autenticada (en este caso, **es el original** que Gabi tiene).
- Se acredite la cadena de custodia.

**Acción:** solicitar a Gabi que conserve los originales (las versiones en papel que le llegaron, no las fotos) y que las aporte al juicio en original.

### 3.3. ¿Vale la transcripción de Whisper como prueba?

**Sustancialmente sí, con reservas.** Whisper es un modelo de transcripción con tasa de error del ~5–10% para español rioplatense. La transcripción debe ir acompañada del audio original.

**Estrategia:** presentar el audio + la transcripción como documentos distintos, indicando que la transcripción es **auxiliar** pero el audio es la prueba principal.

---

## 4. Estrategia probatoria sugerida

### 4.1. Ofrecimiento de prueba en la demanda

Ofrecer:

1. **Documental:** las dos cartas escaneadas + el contrato (si se obtiene).
2. **Audiovisual:** los 38 audios originales + las 38 transcripciones.
3. **Informes:** oficios al IPS, SET, Viceministerio del Trabajo, Registro Público.
4. **Confesional:** absolución de posiciones al representante legal de Odontología 3 S.A.
5. **Testimonial:** 3–5 testigos (otros profesionales, pacientes, personal administrativo).
6. **Pericial:** pericia contable sobre los libros de la clínica.
7. **Reconocimiento judicial:** del consultorio.
8. **Prueba anticipada:** si hay riesgo de que la demandada oculte los libros.

### 4.2. Hechos a probar con cada medio

| Hecho | Medio probatorio |
|---|---|
| Antigüedad (12,5 años) | Testigos, confesional, libros de la clínica. |
| Horario fijo | Carta 26/03/2025 + testigos. |
| Poder disciplinario | Cartas 26/03/2025 y 18/06/2026 + audio 30 + testigos. |
| Continuidad obligatoria | Audio 82 + testigos. |
| Decisión unilateral | Carta 18/06/2026. |
| No pago de prestaciones | Audio 43 + pericia contable + oficio IPS. |
| No inscripción en IPS | Oficio IPS + SET. |
| Reducción de ingresos | Testigos + pericia contable. |
| Representación del firmante | Estatutos y poderes (Registro Público). |

---

## 5. Cadena de custodia — diagrama

```
[Conversación WhatsApp Gabi ↔ Carlos]
              │
              │ (a) Gabi exporta el chat → archivo ZIP
              ▼
[Archivo ZIP de Drive]  ← origen (descargado el 26/08/2026)
              │
              │ (b) Hermes descarga vía curl
              ▼
[/tmp/gdrive_file]
              │
              │ (c) Python zipfile.extractall
              ▼
[/tmp/gdrive_extracted/]  ← 39 archivos (2 fotos + 38 audios + 1 txt)
              │
              │ (d) SHA-256 hash de cada archivo
              ▼
[evidencia/SHA256SUMS.txt]
              │
              │ (e) Copia a repo
              ▼
[/opt/data/scratchpad/gonzalez-vs-odontologia3/evidencia/]
              │
              │ (f) ffmpeg → wav 16kHz mono
              ▼
[/tmp/gdrive_wav/]
              │
              │ (g) Whisper small (es) → texto
              ▼
[transcripciones/*.txt]
```

Cada paso es reversible (con los archivos intermedios en `/tmp`).

---

## 6. Riesgos probatorios

| Riesgo | Mitigación |
|---|---|
| Gabi perdió la copia firmada del contrato | Pedirlo al IPS o en la demanda como prueba informativa. |
| La demandada no tiene libros o están adulterados | Presunción a favor del trabajador (Art. 65 CT, Art. 14 Ley 842/63). |
| Los audios son impugnados por manipulación | Pericia informática, hash, cadena de custodia. |
| Manuel no quiere declarar | No es indispensable; el resto de la prueba es suficiente. |
| La SET informa que SÍ retuvo IRP a Gabi | Eso **reforzaría** la tesis de laboralidad (la retención solo aplica a dependientes). |

---

## 7. Apéndice A — Errores conocidos de Whisper en las transcripciones

Whisper small para español rioplatense confunde sistemáticamente:

| Audio | Transcripción errónea probable | Corrección |
|---|---|---|
| "odontología" | "ontología" | Conservar "odontología" (es la grafía correcta del nombre) |
| "Carlos" | "carlos" (correcto) | OK |
| "licenciado" | "licensiado" / "licen…puta" | "licenciado" |
| "Roque" | "Rock" / "Roq" | "Roque" |
| "masón" / "masonería" | "amasonería" / "amazonería" | "masonería" |
| "Manuel" | "Manuel" (generalmente correcto) | OK |
| "Gabi" | "Gabi" (generalmente correcto) | OK |
| "preaviso" | "pre-aviso" / "preabiso" | "preaviso" |
| "aguinaldo" | "aguinaldo" (generalmente correcto) | OK |
| "indemnización" | "indemnización" / "inminización" | "indemnización" |
| "despacho" / "despido" | "despacho" / "destiempo" / "despido" | contexto-dependiente |
| "honorarios" | "honorario" | "honorarios" |
| "Guaraníes" | "guaraní" / "guaranías" | "guaraníes" |
| "abogada" / "abogado" | "abogada" / "abogada" | OK |
| "WhatsApp" | "wap" / "what's up" / "wasap" | "WhatsApp" |
| "RUC" | "RUC" (generalmente correcto) | OK |
| "cédula" | "cédula" (generalmente correcto) | OK |
| "Auditor" | "auditor" (generalmente correcto) | OK |

**Acción recomendada:** revisar manualmente las transcripciones antes de usarlas en el escrito de demanda. Las versiones corregidas deberían guardarse como `transcripciones_corregidas/`.

---

## 8. Próximo paso concreto

**Esta semana:** Gabi debe (i) guardar los originales en papel de las cartas (no solo las fotos), (ii) localizar cualquier copia del contrato o recibos que conserve, (iii) autorizar a Carlos a iniciar los oficios al IPS y a la SET.

Ver [`../04-estrategia/05-estrategia-procesal.md`](../04-estrategia/05-estrategia-procesal.md).
