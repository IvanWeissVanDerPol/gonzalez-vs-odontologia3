# 12 · Evidencia Original (INMUTABLE)

**Toda la evidencia original del caso Gabi c/ Odontología 3 S.A.** Esta carpeta es INMUTABLE — los archivos aquí son la fuente de verdad para el caso. Cualquier modificación debe ir en una carpeta separada (ej: `02-hechos/`).

## Contenido

| Subcarpeta | Qué hay | Período |
|---|---|---|
| `audios/` | 38 audios originales (.opus) del chat Gabi ↔ Carlos (abogado) | Julio 2026 (4 días antes del cese + durante) |
| `audios/...transcripciones-corregidas/` | Transcripciones Whisper corregidas manualmente de los 38 audios | Julio 2026 |
| `audios/...transcripciones-whisper/` | Transcripciones Whisper originales (sin corregir) | Julio 2026 |
| `cartas-escaneadas/` | 2 cartas originales firmadas por Roque | Marzo 2025 + junio 2026 |
| `whatsapp-roque/` | **Chat completo WhatsApp Gabi ↔ Dr. Roque Ramirez** (8 años) | Junio 2018 → junio 2026 |
| `whatsapp-viviana/` | **Chat completo WhatsApp Gabi ↔ Viviana (Coordinadora)** (2.5 años) | Diciembre 2023 → julio 2026 |
| `_chat.txt` | Chat completo con el abogado Carlos | Julio 2026 |
| `dncp-adjudicaciones-odontologia3.md` | Adjudicaciones scrapeadas de la DNCP (73 contratos, ₲147B) | Histórico + sept 2026 |
| `MANIFEST-SHA256.txt` | Hashes SHA-256 de todos los archivos del repo (cadena de custodia) | Sept 2026 |

## Total de archivos de evidencia

- **38 audios del chat con Carlos** (julio 2026)
- **36 audios del chat con Roque** (2019-2022)
- **31 audios del chat con Viviana** (2023-2024)
- **67 fotos/stickers/videos**
- **3 archivos de chat exportados**
- **2 cartas escaneadas**
- **Total: ~180 archivos** en esta carpeta

## Cadena de custodia

Cada archivo tiene su hash SHA-256 en `MANIFEST-SHA256.txt`. Si se modifica algo, el hash cambia y se detecta inmediatamente.

Para verificar la integridad:

```bash
sha256sum --check 12-evidencia/MANIFEST-SHA256.txt
```

## Por qué hay DOS chats de WhatsApp con la clínica

1. **Chat Gabi ↔ Roque (8 años, 552 mensajes)** — prueba de la relación laboral personal-profesional íntima
2. **Chat Gabi ↔ Viviana (2.5 años, 1241 mensajes)** — prueba de la coordinación cotidiana con la Coordinadora General

**Ambos chats son críticos** porque refutan la tesis de "prestación de servicios independiente":
- Una relación de 8 años con tono familiar ≠ relación comercial esporádica
- Una relación cotidiana con la Coordinadora ≠ autonomía profesional

## Hallazgos críticos en los chats

### Chat Roque

- **Mensajes diarios de coordinación** — turnos, pacientes, fichas
- **Tono informal/familiar** — Roque usa "Gabriela", Gabi le dice "donRa"
- **Decisiones unilaterales de Roque** — "no hagas nada más", "avisame cuando esta"
- **Continuidad hasta junio 2026** — el día que le enviaron la carta del 18/06/2026

### Chat Viviana

- **Coordinación operativa diaria** — turnos, reagendamientos
- **Tono de colegas** — "maena vivi sabes todo de memoria"
- **Mensajes del 13/07/2026 y 18/07/2026** — días inmediatamente después del cese (14/07/2026)
- **Indicios de coordinación post-cese** — entrega de llaves, reagendamiento de pacientes

## Para Carlos

Estos chats son **la prueba más fuerte** de la relación laboral continua y personal:
- **8 años** de chat con Roque = no es "prestación de servicios"
- **2.5 años** de chat con Viviana = Gabi reportaba a la Coordinadora
- **Mensajes del 18/07/2026** con Viviana = la relación continuaba después del cese formal

Recomendamos:
1. **Solicitar pericia informática** de los archivos _chat.txt (verificar autenticidad)
2. **Transcribir audios clave** que mencionen horarios, sanciones, IPS, vacaciones
3. **Citar mensajes verbatim** en la demanda y en la audiencia
4. **Considerar sumar a Viviana como testigo** (no era hostil al final)

## Privacidad

Todos los archivos son privados y están protegidos por patrocinio legal.
NO publicar ni compartir fuera del expediente de Carlos.
