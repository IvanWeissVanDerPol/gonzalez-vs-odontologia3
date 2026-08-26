# 18 · Modelo Financiero del Caso

> *Análisis cuantitativo de escenarios con valor presente neto (VPN). Compara el recupero esperado con el costo del litigio y el costo de oportunidad.*

---

## 1. Parámetros financieros

### 1.1. Variables

| Variable | Valor | Fuente |
|---|---|---|
| Salario base mensual promedio | Gs. 4.500.000 | Audio 59, 62 |
| Tasa de inflación anual Paraguay | ~3,5% | BCP (estimación) |
| Tasa de descuento real | 8% | Estimación conservadora |
| Honorarios abogado (% recupero) | 15% | Estimación conservadora |
| Costos periciales | Gs. 5–15M | Estimación |
| Tasa de retorno proyecto Gabi | 12% anual | Estimación optimista |
| Horizonte de recupero | 12–24 meses | Estimación proceso |

### 1.2. Datos base

- **Demanda estimada:** Gs. 300.000.000 (parte alta).
- **Recupero esperado por escenario:**
  - Conciliación: Gs. 80.000.000 (centro del rango).
  - Acuerdo post-demanda: Gs. 130.000.000.
  - Sentencia favorable: Gs. 200.000.000 (centro del rango).
  - Sentencia desfavorable: Gs. 0 (menos honorarios perdidos).

### 1.3. Costos fijos del litigio

| Concepto | Estimación |
|---|---|
| Honorarios abogado (si pierde) | Gs. 5–15M |
| Honorarios abogado (si gana, % recupero) | 15% del recupero |
| Pericia contable | Gs. 5–10M |
| Pericia informática | Gs. 3–8M |
| Tasa de justicia | Exonerada (trabajador) |
| Costos de notificación | Gs. 1–3M |
| Otros (traslados, fotocopias) | Gs. 1–2M |
| **TOTAL costos fijos estimados** | **Gs. 15–40M** |

---

## 2. Análisis por escenario

### 2.1. Escenario 1 — Conciliación administrativa (probabilidad 25%)

**Datos:**
- Tiempo: 1–3 meses.
- Recupero bruto: Gs. 80M.
- Costos: Gs. 7M (15% honorarios).
- Recupero neto inmediato: **Gs. 73M**.

**VPN comparado con "no hacer nada":**
- VPN hoy: Gs. 73M.
- VPN en 12 meses (tasa 8%): Gs. 73M / 1.08 = **Gs. 67.6M**.
- VPN en 24 meses: Gs. 73M / 1.17 = **Gs. 62.4M**.

**Conclusión:** si la conciliación ofrece Gs. 80M ahora, vale más que esperar 12 meses para llegar a Gs. 87M (que es el equivalente).

### 2.2. Escenario 2 — Acuerdo post-demanda (probabilidad 15%)

**Datos:**
- Tiempo: 6–18 meses.
- Recupero bruto: Gs. 130M.
- Costos: Gs. 19.5M (15% honorarios) + Gs. 5M (pericia) = Gs. 24.5M.
- Recupero neto: **Gs. 105.5M**.

**VPN en 12 meses:** Gs. 105.5M / 1.08 = **Gs. 97.7M**.

### 2.3. Escenario 3 — Sentencia favorable (probabilidad 50%)

**Datos:**
- Tiempo: 12–24 meses.
- Recupero bruto: Gs. 200M.
- Costos: Gs. 30M (15% honorarios) + Gs. 15M (pericias) = Gs. 45M.
- Recupero neto: **Gs. 155M**.

**VPN en 24 meses:** Gs. 155M / 1.17 = **Gs. 132.5M**.

### 2.4. Escenario 4 — Sentencia desfavorable (probabilidad 5%)

**Datos:**
- Tiempo: 12–18 meses.
- Recupero: Gs. 0.
- Costos: Gs. 15M (honorarios mínimos) + Gs. 5M (pericia) = Gs. 20M.
- Pérdida neta: **−Gs. 20M**.

**VPN:** −Gs. 20M / 1.13 = **−Gs. 17.7M**.

### 2.5. Escenario 5 — Allanamiento parcial (probabilidad 10%)

**Datos:**
- Tiempo: 6–12 meses.
- Recupero bruto: Gs. 140M.
- Costos: Gs. 21M (15%) + Gs. 5M = Gs. 26M.
- Recupero neto: **Gs. 114M**.

---

## 3. Esperanza matemática ponderada

### 3.1. Cálculo

| Escenario | Prob. | Recupero neto (VPN) |
|---|---|---|
| Conciliación | 25% | Gs. 73.0M |
| Acuerdo post-demanda | 15% | Gs. 97.7M |
| Sentencia favorable | 50% | Gs. 132.5M |
| Sentencia desfavorable | 5% | −Gs. 17.7M |
| Allanamiento parcial | 10% | Gs. 114.0M |
| **Esperanza matemática** | — | **Gs. 110.7M** |

### 3.2. Interpretación

El **valor esperado del litigio es Gs. 110.7M** netos para Gabi.

Esto representa **el valor actual neto** de tomar acción vs. no hacer nada.

---

## 4. Análisis costo-beneficio

### 4.1. Costos

- **Costos fijos totales** (peor caso): Gs. 40M.
- **Costos fijos totales** (caso típico): Gs. 20M.
- **Honorarios abogado**: 15% del recupero.

### 4.2. Beneficios

- **Esperanza matemática del recupero:** Gs. 110.7M.
- **Beneficio neto esperado:** Gs. 110.7M − Gs. 20M (costos típicos) = **Gs. 90.7M**.

### 4.3. ROI

- **Inversión típica:** Gs. 20M.
- **Beneficio esperado:** Gs. 90.7M.
- **ROI:** 354%.

> **Conclusión financiera:** el caso tiene un **retorno esperado muy alto** comparado con su costo.

---

## 5. Análisis de sensibilidad

### 5.1. Variables críticas

**¿Qué pasa si la probabilidad de sentencia favorable baja del 50% al 30%?**

Recalcular esperanza:
- (25% × 73) + (15% × 97.7) + (30% × 132.5) + (20% × −17.7) + (10% × 114) = 18.25 + 14.66 + 39.75 − 3.54 + 11.4 = **Gs. 80.5M**.

Sigue siendo positivo.

**¿Qué pasa si la conciliación fracasa y la demandada no paga nada?**

- Escenario se convierte en "todo vía judicial".
- VPN total cae a Gs. 90M.

**¿Qué pasa si Gabi no tiene éxito en ninguna instancia?**

- Pérdida: Gs. 17.7M (todavía manejable).

---

## 6. Análisis del proyecto propio de Gabi

### 6.1. Si Gabi reinvierte el recupero en su proyecto

**Hipótesis:** Gabi usa el dinero para financiar su proyecto propio (consultorio independiente).

**Asumiendo:**
- Inversión inicial: Gs. 100M.
- Tasa de retorno: 12% anual.
- Horizonte: 10 años.

**VPN del proyecto:**
- Gs. 100M invertidos hoy.
- Ingresos anuales esperados: Gs. 12M (después del primer año).
- VPN a 10 años: **Gs. 30.6M positivos** (al 8% de descuento).

> **Conclusión:** Gabi tiene un proyecto alternativo que justifica economicamente la búsqueda del recupero.

---

## 7. Comparación con la alternativa "no hacer nada"

### 7.1. Si Gabi no demanda

- **Costo:** Gs. 0 inmediato.
- **Beneficio:** Gs. 0.
- **Pérdida de oportunidad:** Gs. 90.7M (esperanza matemática).
- **Pérdida adicional:** 12 años de aportes al IPS no regularizados.

### 7.2. Conclusión

> **Hacer algo es financieramente superior a no hacer nada** en una esperanza de Gs. 90.7M, con un riesgo máximo de Gs. 17.7M.

---

## 8. Análisis del peor caso (downside)

### 8.1. Si todo sale mal

- Gabi pierde el juicio (5% de probabilidad).
- Costos hundidos: Gs. 17.7M.
- Efecto sobre su proyecto: puede financiarlo con sus propios ingresos o con crédito.
- Efecto emocional: frustración, pero el costo es manejable.

### 8.2. Mitigación

- Carlos puede trabajar con honorarios escalonados (parte fija + parte variable).
- Carlos puede pactar con Gabi que **no cobra** si pierde (en algunos casos se hace).
- Reducir el alcance de la pericia si los costos son prohibitivos.

---

## 9. Recomendación financiera

**Para Gabi:** el caso tiene un valor esperado de Gs. 90.7M netos con un riesgo máximo de Gs. 17.7M. La relación riesgo-retorno es **muy favorable**.

**Para Carlos:** si cobra 15% del recupero, su ingreso esperado es Gs. 16.6M. Si cobra honorario fijo, debería ser al menos Gs. 10M para hacer viable el caso.

**Plan de financiamiento recomendado:**
- Honorarios escalonados: Gs. 5M al inicio + 15% del recupero.
- Costos procesales: a cargo de Gabi con cargo al recupero.

---

## 10. Tabla resumen

| Concepto | Valor |
|---|---|
| **Recupero bruto esperado** | Gs. 130.7M |
| **Esperanza matemática neta** | Gs. 110.7M |
| **Costo típico del litigio** | Gs. 20M |
| **Beneficio neto esperado** | Gs. 90.7M |
| **ROI esperado** | 354% |
| **Riesgo máximo (pérdida)** | Gs. 17.7M |
| **Probabilidad de recupero positivo** | 95% |

---

*Documento cuantitativo. Carlos debe ajustar las variables según la evolución real del caso.*
