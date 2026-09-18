# 03 · Cuantificación del Crédito Laboral

> *Memoria de cálculo detallada por rubro. Todos los valores son estimaciones sujetas a verificación probatoria.*

---

## 1. Parámetros básicos

### 1.1. Salario base

**Método Carlos (audio 58):** *"Voy a hacer el cálculo de acuerdo a tu historial de promedio de pago… un año, de un año sacar ese promedio anual y de ahí sacamos el promedio mensual que vas a reclamar."*

**Aplicación:** promedio de los últimos 12 meses de ingresos.

| Mes (estimado) | Ingreso declarado |
|---|---|
| ago/2025 | Gs. 5.000.000 |
| sep/2025 | Gs. 5.000.000 |
| oct/2025 | Gs. 4.500.000 |
| nov/2025 | Gs. 4.500.000 |
| dic/2025 | Gs. 5.000.000 (aguinaldo?) |
| ene/2026 | Gs. 4.000.000 |
| feb/2026 | Gs. 4.000.000 |
| mar/2026 | Gs. 4.000.000 |
| abr/2026 | Gs. 4.000.000 |
| may/2026 | Gs. 4.000.000 |
| jun/2026 | Gs. 4.000.000 |
| jul/2026 | Gs. 2.000.000 (parcial hasta 14/07) |
| **TOTAL** | **Gs. 50.000.000** |
| **PROMEDIO MENSUAL** | **Gs. 4.166.667** |

> Carlos mencionó en audio 59: *"promedio de 4 millones, ponerle que es poquísimo"*, y en audio 62: *"5 millones como máximo, como máximo"*. Tomamos como base **Gs. 4.500.000** mensuales (estimación intermedia prudente) **incluyendo el componente Asismed** que se pagaba como fijo hasta 2025.

**Salario diario base = Gs. 4.500.000 / 30 = Gs. 150.000.**

> **Componente ASISMED (NUEVO — cuestionario v2 §5.1.7, audio 36):** Asismed (seguro médico privado) contrataba a la clínica con un **pago fijo mensual** por la atención de sus asegurados. Este fijo se repartía entre los odontólogos del plantel. En 2025 Asismed cambió las condiciones (de fijo a variable), y eso explica la caída de ingresos de Gabi de ~5M → ~4M. **Implicación cuantitativa:** durante los años de fijo Asismed, el salario real de Gabi era mayor al promedio simple; durante 2025-2026 la caída del fijo impactó directamente su ingreso. Ver análisis específico en [`./19-analisis-asismed.md`](./19-analisis-asismed.md).

### 1.2. Antigüedad

**Cómputo:** desde 2014 hasta 14/07/2026 = **12 años y 6 meses** (fracción >6 meses = se computa como año entero para indemnización).

---

## 2. Rubros reclamables

### 2.1. Indemnización por antigüedad (Art. 91 CT)

> *"En caso de terminación del contrato por tiempo indeterminado, el trabajador tendrá derecho a una indemnización equivalente a quince días de salario por cada año de servicio o fracción superior a seis meses."*

**Cálculo:**
- 15 días × 13 años (fracción >6m se computa como año) = **195 días**.
- 195 días × Gs. 150.000 = **Gs. 29.250.000**.

> ⚠️ **Nota:** Este rubro es exigible si la relación se califica como contrato de trabajo por tiempo indeterminado. Bajo el argumento subsidiario (estabilidad absoluta), este rubro puede ser **absorbido por la indemnización por despido ilícito** (ver 2.3).

### 2.2. Preaviso omitido (Art. 86 CT)

> *"El empleador que despida al trabajador sin preaviso o con uno menor al legal, debe indemnizarlo..."*

**Cálculo:**
- Trabajador con más de 10 años = **60 días de preaviso** (Art. 86 inc. c CT, modificado por Ley 496/95).
- 60 días × Gs. 150.000 = **Gs. 9.000.000**.

### 2.3. Indemnización por despido sin justa causa / Estabilidad absoluta (Art. 94 CT)

Esta es la indemnización principal.

**Doctrina mayoritaria de la CSJ:** la indemnización por despido de un trabajador con estabilidad absoluta es equivalente al **salario de los últimos 5 años** (calculado sobre el promedio mensual), o a la **reincorporación**.

**Cálculo (estimación alta):**
- 60 meses (5 años) × Gs. 4.500.000 = **Gs. 270.000.000**.

**Cálculo (estimación baja — Art. 91 + adicional):**
- Si se rechaza la reincorporación: Gs. 29.250.000 (antigüedad) + una indemnización adicional por despido ilícito equivalente a **6 meses de salario** (criterio extendido) = Gs. 29.250.000 + Gs. 27.000.000 = **Gs. 56.250.000**.

**Cálculo (estimación intermedia — 3 años):**
- 36 meses × Gs. 4.500.000 = **Gs. 162.000.000**.

> **Rango:** Gs. 56.250.000 – Gs. 270.000.000. Para negociación, base **Gs. 162.000.000**.

### 2.4. Aguinaldo proporcional (Ley 1.534/99)

> *"El aguinaldo es la remuneración equivalente a la doceava parte de las remuneraciones devengadas durante el año calendario..."*

**Cálculo (proporcional 6 meses y medio de 2026, hasta el 14/07):**
- Mejor remuneración mensual 2026 = Gs. 4.500.000.
- 1/12 × 6.5 = 0.5417 aguinaldo anualizado.
- **Gs. 2.437.500**.

**Si se reclama también el proporcional del año 2014 al 2025 (si no fue pagado):**
- 12 años × Gs. 4.500.000/12 = Gs. 4.500.000/año × 12 = **Gs. 54.000.000** (si nunca pagó).

> **Rango:** Gs. 2.437.500 – Gs. 56.437.500. Para negociación, base **Gs. 30.000.000**.

### 2.5. Vacaciones proporcionales (Art. 218 CT)

> *"El trabajador tiene derecho a un período de vacaciones remuneradas después de cada año de servicio..."*
> 30 días corridos por año, fraccionables.

**Cálculo (proporcional 6 meses y medio de 2026):**
- 30 días × (6.5/12) = 16.25 días.
- 16.25 × Gs. 150.000 = **Gs. 2.437.500**.

**Si se reclaman años anteriores no gozados:** 12 años × 30 días = 360 días × Gs. 150.000 = **Gs. 54.000.000** (improbable que se conceda todo, pero es la base máxima).

> **Para negociación, base Gs. 5.000.000 (proporcional 2026 + última vacación pendiente).**

### 2.6. Salario vacacional (Art. 218 in fine CT)

> *"El trabajador percibirá un salario adicional por concepto de salario vacacional equivalente al 50% del salario correspondiente a las vacaciones."*

**Cálculo:**
- 50% × Gs. 2.437.500 = **Gs. 1.218.750**.

> Para 12 años atrasados, base máxima: **Gs. 27.000.000**. Para negociación, base **Gs. 3.000.000**.

### 2.7. Aportes al IPS no realizados (estimación)

**Cálculo:**
- Aporte obrero + patronal = ~25,5% del salario.
- Salario base anual = Gs. 54.000.000.
- Aportes anuales no realizados = Gs. 13.770.000.
- Por 12 años = **Gs. 165.240.000** (estimación muy alta si la demandada no pagó nunca).
- Por el último año solamente = **Gs. 13.770.000**.

> Para negociación, base **Gs. 13.770.000** (último año) o demanda por la totalidad si la prueba lo confirma.

**Consecuencia sobre Gabi:**
- Si la clínica no aportó, Gabi **no tiene jubilación futura**, **no tiene cobertura de salud** y **no tiene cobertura de riesgos del trabajo**.
- Esto es un **daño previsional autónomo** que la CSJ ha reconocido en algunos precedentes.

### 2.8. Multas por infracciones al CT

| Multa | Base legal | Estimación |
|---|---|---|
| Por no inscripción en IPS | Art. 283 CT | 5 jornales × cada mes × 12 años ≈ **Gs. 27.000.000** (estimación alta) |
| Por no pago en tiempo | Art. 244 CT (intereses) | Variable |
| Por no entrega de certificado de trabajo | Art. 96 CT | 3 meses de salario ≈ **Gs. 13.500.000** |
| Por no entregar constancia de aportes | Art. 122 CT | Variable |
| Por no tener libro de asistencia | Art. 121 CT | Multa fija |

> Para negociación, base **Gs. 5.000.000 – 15.000.000** (la judicatura suele reducir estas multas).

### 2.9. Daño moral y daño punitivo (jurisprudencia reciente)

**Doctrina:** la CSJ ha reconocido **daño moral** en casos de fraude laboral en sentencias de los últimos 5 años. El quantum varía entre Gs. 5.000.000 y Gs. 100.000.000 según la gravedad y los daños acreditados.

**Aplicación al caso (actualizado tras cuestionario v2 §16):**
- **12 años de fraude continuado.**
- **Imposibilidad de acceder a la jubilación** (sin aportes al IPS).
- **Negativa expresa** de cualquier indemnización (audio 43).
- **Impacto en el proyecto profesional** de Gabi (audio 75).
- **Deterioro de salud acreditado y contemporáneo al caso** — ver [`../03-legal/23-dano-moral-y-salud.md`](../03-legal/23-dano-moral-y-salud.md):
  - Infección urinaria aguda (agosto 2026, primera vez en su vida — cuestionario v2 §16.2.2).
  - Quiste renal izquierdo 30 mm (Bosniak II probable).
  - Quiste pancreático 6 mm (incidentaloma).
  - Plaquetas elevadas (575 K/mm³) — probable trombocitosis reactiva al estrés.
  - Dislipidemia (LDL 165, No-HDL 180).
  - Vitamina D insuficiente (29,35 ng/mL).
  - HOMA-IR 2,94 borderline.
  - Insomnio, ansiedad, deterioro de concentración y apetito (cuestionario v2 §11.1).
  - Internación y enfermedad prolongada al 12/09/2026.
  - Recomendación médica documentada de "bajar el cambio" (cuestionario v2 §16.2.5).

> Para demanda, reclamar **Gs. 50.000.000** como daño moral (incrementado desde los Gs. 30M originales en función del deterioro de salud acreditado; rango posible: Gs. 30.000.000 – Gs. 80.000.000).

---

## 3. Resumen de cuantificación

| Rubro | Bajo | Medio | Alto |
|---|---|---|---|
| Indemnización antigüedad (Art. 91) | Gs. 29.250.000 | Gs. 29.250.000 | Gs. 29.250.000 |
| Preaviso (Art. 86) | Gs. 9.000.000 | Gs. 9.000.000 | Gs. 9.000.000 |
| Estabilidad absoluta (Art. 94) | Gs. 56.250.000 | Gs. 162.000.000 | Gs. 270.000.000 |
| Aguinaldo proporcional | Gs. 2.437.500 | Gs. 30.000.000 | Gs. 56.437.500 |
| Vacaciones proporcionales | Gs. 2.437.500 | Gs. 5.000.000 | Gs. 54.000.000 |
| Salario vacacional | Gs. 1.218.750 | Gs. 3.000.000 | Gs. 27.000.000 |
| Aportes IPS | Gs. 13.770.000 | Gs. 50.000.000 | Gs. 165.240.000 |
| Multas CT | Gs. 5.000.000 | Gs. 10.000.000 | Gs. 40.000.000 |
| Daño moral | Gs. 5.000.000 | Gs. 15.000.000 | Gs. 30.000.000 |
| Daño moral (actualizado con salud) | 30.000.000 | 50.000.000 | 80.000.000 |
| **TOTAL** | **Gs. 149.363.750** | **Gs. 348.250.000** | **Gs. 730.927.500** |

**Hipótesis recomendada para la demanda:** **Gs. 300–350M** (parte media-alta, ajustada por daño moral).

**Hipótesis recomendada para negociación (ACTUALIZADA — cuestionario v2 §9.3):** **Gs. 150–200M mínimo** (Gabi declaró explícitamente: "200M" como techo de negociación aceptable y "150–200M" como mínimo en escenario de reconocimiento simbólico). **Piso duro: Gs. 150M** — Carlos debe rechazar cualquier oferta inferior sin consultar a Gabi.

---

## 4. Honorarios del abogado patrocinante

### 4.1. Sistema paraguayo

En el fuero laboral paraguayo, los honorarios se regulan con base en el **tanto por ciento del monto del juicio** (Art. 689 CPC, aplicación supletoria).

**Porcentajes usuales en Paraguay:**
- Mínimo deontológico del Colegio de Abogados: 10–15%.
- Acuerdo privado entre abogado y cliente: típicamente 20–30% del monto recuperado.

> **Audio 98 (Gabi):** *"ponerle que yo pierda la demanda. ¿Cómo se hace para regular los honorarios? ¿Me regulan a mí? ¿O en este caso la odontología 13 se hace cargo de todos los gastos de la...?"*
>
> **Audio 99 (Carlos):** *"Ahí, manualmente puedes regular. Sí, así es."*
>
> Conclusión: Gabi puede **regular honorarios a la demandada** si gana, lo que efectivamente transfiere el costo.

**Estimación:**
- Si gana y se regulariza al 15%: Gabi paga al abogado ~Gs. 37–45M sobre Gs. 250–300M recuperados.
- Si se aplica el monto transaccional de Gs. 100–150M: honorarios de Gs. 15–22M.
- **Si pierde**, Gabi paga sus propios honorarios y los regulados a su abogado (~Gs. 5–15M).

### 4.2. Costas del proceso

- Tasa judicial: exonerada en el fuero laboral para el trabajador.
- Peritajes: a cargo de la demandada si se condenan en costas.
- Publicaciones: a cargo de la parte que perdió.

---

## 5. Cuantificación final con honorarios

**Si gana (Gs. 250M recuperados, honorarios 15%):**
- Recuperación neta de Gabi: Gs. 250M − Gs. 37.5M (honorarios) = **Gs. 212.5M**.

**Si transa en Gs. 150M (honorarios 15%):**
- Recuperación neta: Gs. 127.5M.

**Si pierde:**
- Costo de Gabi: Gs. 5–15M (honorarios propios).

---

## 6. Análisis costo-beneficio

| Escenario | Resultado bruto | Costo estimado | Resultado neto | Probabilidad |
|---|---|---|---|---|
| Conciliación exitosa | Gs. 50–100M | Gs. 7–15M (honorarios) | Gs. 35–85M | 25% |
| Acuerdo post-demanda | Gs. 60–150M | Gs. 9–22M | Gs. 51–128M | 15% |
| Sentencia favorable | Gs. 90–270M | Gs. 13–40M | Gs. 50–230M | 50% |
| Sentencia desfavorable | Gs. 0 | Gs. 5–15M | −Gs. 5–15M | 5% |
| Allanamiento parcial | Gs. 100–180M | Gs. 15–27M | Gs. 85–153M | 10% |

**Esperanza matemática del recupero:**
- 0,25 × 60 + 0,15 × 90 + 0,50 × 180 + 0,05 × 0 + 0,10 × 140 = 15 + 13,5 + 90 + 0 + 14 = **Gs. 132.5M** (esperanza bruta).
- Esperanza neta (descontando honorarios ~15%): **~Gs. 112.6M**.

> **Conclusión:** el valor esperado del litigio es **muy positivo** en comparación con el costo de no hacer nada (Gs. 0).

---

## 7. Riesgos de subvaloración o sobrevaloración

### Subvaloración

- Si la CSJ aplica la **reincorporación** (Art. 96 CT) en lugar de indemnización sustitutiva, Gabi recuperaría solo salarios caídos hasta sentencia (~Gs. 4.5M × 24 meses = Gs. 108M), pero mantendría el puesto y los aportes.
- Si la CSJ rechaza la multa del Art. 283 CT, se pierden Gs. 27M.

### Sobrevaloración

- El aguinaldo de 12 años atrás puede prescribir individualmente.
- Los aportes al IPS pueden ser acreditados retroactivamente sin condena indemnizatoria (solo pago).
- La demandada puede ofrecer acuerdo por debajo del valor esperado.

---

## 8. Recomendación final al abogado

Presentar demanda por **Gs. 300.000.000** (parte alta del rango), pidiendo:

1. **Reincorporación** al puesto de trabajo, con salarios caídos desde el 14/07/2026 hasta la efectiva reincorporación.
2. **Subsidiariamente**, indemnización sustitutiva equivalente a **5 años de salario** (Gs. 270.000.000).
3. **Todas las prestaciones laborales** adeudadas (aguinaldo, vacaciones, vacaciones fraccionadas, salario vacacional).
4. **Aportes al IPS** desde 2014 con más intereses.
5. **Multas e intereses** por las infracciones al CT.
6. **Daño moral** de **Gs. 50.000.000** (actualizado por salud).
7. **Costas** del juicio.

> **Base de negociación en audiencia de conciliación: Gs. 150–200M** (ACTUALIZADO — cuestionario v2 §9.3).
> **Piso duro: Gs. 150M.** Si la demandada ofrece menos, **no aceptar sin consultar a Gabi**.
> Gabi declaró que **no acepta acuerdo en cuotas** (cuestionario v2 §9.3.6) y que **no puede esperar mucho** (cuestionario v2 §9.3.5) — está en "defaull" económico al 12/09/2026. Esto **endurezce la posición negociadora**: Carlos debe presionar por pago contado o a muy corto plazo.

> **Análisis de sensibilidad adicional (NUEVO):**

| Escenario | Cuantía demandada | Cuantía recuperada (est.) | Comentario |
|---|---|---|---|
| Conciliación temprana (alta presión probatoria) | Gs. 300M demandados | Gs. 180–220M | Optimal given financial pressure on Gabi |
| Conciliación extendida | Gs. 300M demandados | Gs. 150–180M | Carlos debe evitar este escenario |
| Sentencia favorable 1ª instancia | Gs. 300M demandados | Gs. 200–270M | Demora 12–24 meses — riesgo de insolvencia |
| Sentencia desfavorable | Gs. 300M demandados | Gs. 0 + Gs. 5–15M en costas | 5% probabilidad |
| Acción colectiva (50+ colegas) | Gs. 300M × N demandantes | Multiplicador 5–10x | Cambia radicalmente la presión sobre la demandada |

---

## 9. ⚠️ Cuantificación penal paralela (NUEVO 18/09/2026)

⚠️ Si se activa la vía penal (Art. 196 CP retención indebida + Art. 187 CP estafa procesal + Art. 192 CP lesión de confianza), hay una **cuantificación penal adicional**.

### 9.1. Cuantificación civil en querella penal

| Concepto | Monto |
|---|---|
| Daño material (aportes no ingresados al IPS, 12 años) | **₲ 195.000.000** |
| Daño moral (ver [`../03-legal/23-dano-moral-y-salud.md`](../03-legal/23-dano-moral-y-salud.md)) | ₲ 30.000.000 – 80.000.000 |
| Lucro cesante (12 meses sin ingresos, base ₲ 4.500.000 × 12) | **₲ 54.000.000** |
| **Subtotal cuantificación civil penal** | **₲ 279M – 329M** |

### 9.2. Penalidades adicionales

| Concepto | Monto |
|---|---|
| Multa Art. 283 CT (no inscripción IPS, 5 jornales mínimos × cada mes × 12 años) | ₲ 27.000.000 |
| Decomiso del beneficio indebido (Art. 197 CP) | Variable |
| **TOTAL en querella penal** | **₲ 306M – 356M** |

### 9.3. Anclaje procesal penal

| Concepto | Anclaje (mínimo) | Anclaje (recomendado) |
|---|---|---|
| Embargo preventivo penal | ₲ 2.000.000.000 | **₲ 4.000.000.000** (4x quantum) |
| Prohibición de salida del país de los 5 querellados | (a discreción del juez) | (a discreción) |
| Caución real de los querellados | ₲ 500.000.000 c/u | (a discreción) |

### 9.4. Cálculo consolidado ⚠️ (LABORAL + PENAL)

| Vía | Quantum | Status |
|---|---|---|
| **Demanda laboral** (cuantía Gs. 300M) | ₲ 300M | Gabi vs. O3 S.A. + 5 cabezas |
| **Querella penal** (civil ₲ 300M + decomiso) | ₲ 300–360M | Gabi vs. Roque + 4 cabezas |
| **Embargo preventivo laboral** | ₲ 2.000M – 4.000M | 6 entidades + 4 personas físicas |
| **Embargo preventivo penal** | ₲ 2.000M – 4.000M | (mismo, pero vía penal) |
| **Total combinado recuperable** | **₲ 1.000M – 1.500M** | Estimación real con honorarios + descuentos |

> **⚠️ Conclusión crítica:** Las dos vías juntas (laboral + penal) NO multiplican el recupero. Pero **sí fortalecen la posición negociadora** de Gabi al obligar a Roque a litigar en dos fueros simultáneamente con un riesgo combinado de **embargo ₲4.000M + prisión preventiva + inhabilidad DNCP (perdería ₲147B en contratos públicos)**.

### 9.5. Recuperabilidad efectiva del patrimonio del grupo (estimación revisada)

⚠️ **El patrimonio del grupo es suficiente para cubrir la condena consolidada.** Ver [`../08-analisis-especializado/15-solvencia.md`](../08-analisis-especializado/15-solvencia.md) §9 actualizado.

---

*Documento cuantitativo. Carlos debe verificar todos los números con pericia contable y corroborar con Gabi. La cuantificación penal es estimativa y está sujeta a la inflación del proceso.*

---

*Ver [`../02-hechos/04-pruebas.md`](../02-hechos/04-pruebas.md) para el plan de producción de prueba, y [`../04-estrategia/05-estrategia-procesal.md`](../04-estrategia/05-estrategia-procesal.md) para el plan procesal paso a paso.*
