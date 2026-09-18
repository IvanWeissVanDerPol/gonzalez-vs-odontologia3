# 66 · Informe: Expediente PJ "O3 S.A. c/ Res. 760/2018 DNCP" + trazabilidad contrataciones.gov.py

**Fecha:** 2026-09-18 · **Fuente primaria:** Poder Judicial (pj.gov.py) + contrataciones.gov.py · **Artefactos:** 4 (SHA-256 en `MANIFEST.txt` de `12-evidencia/expediente-pj-2026-09-18/`)

---

## 1. La causa existe y estuvo VIVA en apelación al 26/09/2022

**Carátula exacta:** *"Odontología 3 S.A. C/ Res. Nro. 760 del 05/03/2018 Dict. por la Dirección Nacional de Contrataciones Públicas"* — **causa N° 4** de la lista oficial de causas pendientes de la **Secretaría Judicial IV** (Tribunal de Apelación en lo Civil, Comercial y Laboral de Asunción), PDF de 10 páginas al 26/09/2022.

**Sala:** Dr. Ramírez Candia · Dra. Carolina Llanes · Dr. Benítez Riera (preopinante a confirmar en el expediente físico; la extracción de columnas del PDF interleavea).

**Lectura procesal:** para estar en apelación en 2022, la sentencia de primera instancia (Juzgado en lo Civil y Comercial, turno contencioso-administrativo) ya existía. O3 demandó a la DNCP y llevó el caso a tribunales. No es un amago: es litigio institucional real y sostenido (2018 → ≥2022).

## 2. La causa YA NO está pendiente al 20/03/2026 → apelación RESUELTA entre 2022 y 2026

Lista oficial de la misma Secretaría Judicial IV al 20/03/2026 (7 págs.): **cero menciones de "Odontología"** y ninguna causa contra la DNCP. Dos posibilidades:
- **Sentencia de Tribunal dictada** (confirmó o revocó la 1ª instancia) → expediente archivado, copiable por carátula.
- **Elevada en casación a la CSJ** (Sala Civil) → consultable por carátula en la CSJ.

**Desconocemos el desenlace. Ambos escenarios son útiles — pero exigen lecturas distintas:**

| Desenlace | Uso para el caso |
|---|---|
| **Res. 760 CONFIRMADA** (DNCP ganó) | Sanción firme a O3 por contratación pública irregular → munición institucional de primer nivel para presión y para el relato "empleado visible en una empresa sancionada por el Estado". |
| **Res. 760 REVOCADA** (O3 ganó) | O3 logró convencer a un tribunal de que la DNCP obró mal → (a) anticipa su defensa "somos perseguidos"; (b) revisar la sentencia para conocer la teoría del caso de O3 y sus abogados (quiénes son, qué argumentos usan); (c) ajustar la avenida institucional DNCP. |

## 3. ACCIÓN CARLOS (agregar a 15-colaboracion-carlos)

1. **Pedir copia certificada del expediente** por carátula *"Odontología 3 S.A. C/ Res. Nro. 760 del 05/03/2018 dict. por la DNCP"* en Secretaría Judicial IV (Tribunal de Apelación en lo Civil, Comercial y Laboral, Asunción). Si está en casación, pedir número de expediente CSJ.
2. **Objetivo del pedido:** sentencia del Tribunal (fallo + fondos) → identifica al estudio de abogados de O3 en materia contenciosa y su argumentario.
3. **Costo:** gestión de secretaría (~1 semana). **Prioridad:** alta — es el único expediente judicial donde O3 ya es parte y todo es público para su abogado.

## 4. Contrataciones.gov.py — O3 sigue facturando al Estado (2021-2024)

- **Ficha de proveedor** "Odontología 3 Tres S.A." (RUC 80010293): HTML archivado (shell SPA; datos citados por el buscador). Dirección registrada: **Mcal. Estigarribia 1414 c/ Primera Junta** — **misma manzana que Santé (Estigarribia 1458)**: refuerza la unidad económica/velo.
- **Llamado MOPC ID 444961** "Servicio de seguro odontológico" (2024): página del proceso archivada; existe resolución de adjudicación vinculada (enlace `resumen-adjudicacion` en el HTML). Estado final del llamado: pendiente de extraer vía API SPA.
- **Contratos citados en prensa/fichas:** SENACSA 2021 (~G. 1.625M), CAH (~G. 2.400M) → facturación estatal adicional más allá del MOPC.
- **Prensa 2023 (Última Hora):** José Manuel (VP de O3) denuncia públicamente retraso de pagos del MOPC → **prueba de rol operativo y de gestión de cobros de JM después de 2019**, directamente útil para el dual targeting (patrimonio JM: Scultura/Tecnodent).

## 5. Precedente adverso identificado y preparado para contraste (España)

**STS 33/2023 (rec. 3291/2020, 17/01/2023)** — franquicia de Vitaldent: odontólogos TRADE **no laborales** porque fijaban libremente días/horarios, sin retribución mínima, pudiendo trabajar en otras clínicas, sin dirección médica.

**Por qué NO nos mata (y nos prepara):** el propio fallo fija el test. Gabi cumple **turnos asignados por el sistema central** ("urgencias al llamado, 365 días"), cobra fijo, no elige pacientes, y la red le impone agenda — exactamente las notas que la STS exige para laboralidad. Acción: incorporar al doc 65 (jurisprudencia internacional) como "preparación de contraste O3".

## 6. Estado de la investigación (delta sobre la mesa redonda I1-I10)

| Cola | Estado hoy |
|---|---|
| I1 Expediente PJ 760/2018 | **⚡ AVANCE MAYOR**: causa localizada en apelación 2022, resuelta ≤2026; copia certificada → Carlos |
| I6 Sentencia sala | Preparación de contraste hecha (STS 33/2023 mapeada) |
| I3/I5 (estatutos IGJ, sistema de turnos) | Sin cambios — requieren gestión presencial |
| Roster/timestamps (I7-I10) | Sin cambios — cron mensual agendado (18 de cada mes, requiere gateway activo) |

## 7. Trazabilidad de artefactos

| Artefacto | SHA-256 (primeros 12) | Qué prueba |
|---|---|---|
| `expediente-pj-ID1-874-secretaria-judicial-iv-2022-09-26.pdf` | `8959bdbe0527` | Causa N° 4 pendiente en apelación al 26/09/2022, Sala Ramírez Candia/Llanes/Benítez Riera |
| `pj-secretaria-iv-lista-causas-pendientes-2026-03-20.pdf` | (ver MANIFEST) | Misma secretaría al 20/03/2026 SIN la causa O3 → apelación resuelta entre ambas fechas |
| `contrataciones-proveedor-o3.html` | `8c335aaec1b1` | Ficha proveedor RUC 80010293 (dirección Estigarribia 1414) |
| `contrataciones-convocatoria-444961-mopc-2024.html` | `3fbc7c5d8e86` | Llamado MOPC "seguro odontológico" 2024 con O3 en escena |

*Nota metodológica: los HTML de contrataciones.gov.py son shells SPA — los datos citados provienen de los snippets indexados por el buscador sobre esas páginas; a futuro archivar también el JSON de la API interna (`/datos/api/`).*
