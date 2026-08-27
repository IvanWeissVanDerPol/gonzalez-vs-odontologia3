# 12 · Evidencia Original

> **Carpeta inmutable.** Los archivos aquí NO deben modificarse. Cualquier alteración rompe la cadena de custodia.

## Contenido

| Carpeta / archivo | Qué es | Cantidad |
|---|---|---|
| `MANIFEST-SHA256.txt` | Hash SHA-256 de los archivos | 1 |
| `_chat.txt` | Chat completo de WhatsApp entre Gabi y Carlos | 1 |
| `audios/` | Audios originales del chat (.opus) | 38 |
| `cartas-escaneadas/` | Cartas escaneadas enviadas por la demandada | 2 |
| `transcripciones-whisper/` | Transcripciones automáticas Whisper | 38 |
| `transcripciones-corregidas/` | Transcripciones Whisper corregidas manualmente | 38 |
| `README.md` | Este archivo | 1 |

## Cadena de Custodia

Todos los archivos tienen un hash SHA-256 calculado al momento de la descarga del Drive original.

- Algoritmo: SHA-256.
- Última verificación: ver `git log` del repositorio.

Para verificar la integridad:

```bash
shasum -a 256 -c MANIFEST-SHA256.txt
```

## Tipos de archivo

### `audios/` (38 archivos)

Audios originales del chat de WhatsApp entre Gabi y Carlos, en formato `.opus`. Contienen las conversaciones clave del caso.

- Fechas: 10/07/2026 – 17/08/2026.
- Duración total: 22:52 minutos (1372 segundos).
- Tamaño promedio por audio: 100–300 KB.

### `cartas-escaneadas/` (2 archivos)

Fotografías de las dos cartas enviadas por la demandada a Gabi:

- `00000020-PHOTO-2026-07-10-19-08-51.jpg`: Carta del 26/03/2025 (primer apercibimiento).
- `00000044-PHOTO-2026-07-10-19-19-07.jpg`: Carta del 18/06/2026 (segundo apercibimiento con amenaza).

### `transcripciones-whisper/` (38 archivos)

Transcripciones automáticas con Whisper (modelo `small`, idioma español). Contienen errores de reconocimiento (nombres propios, jerga paraguaya).

### `transcripciones-corregidas/` (38 archivos)

Versión corregida manualmente de las transcripciones Whisper. Correcciones aplicadas:

- Nombres propios: "odontología", "Roque", "Roque Ramírez Nizza", "masón", "licenciado", etc.
- Jerga paraguaya: "hont...", "loquería 3", etc.
- Muletillas y fonemas mal transcritos.

### `_chat.txt`

Chat completo de WhatsApp entre Gabi y su abogado patrocinante (Dr. Carlos). 1 archivo de texto con todo el historial.

## Cómo NO usar esta carpeta

- ❌ NO modificar los archivos originales.
- ❌ NO agregar archivos aquí sin recalcular el hash.
- ❌ NO eliminar archivos.
- ❌ NO compartir fuera del equipo legal sin autorización.

## Cómo SÍ usar esta carpeta

- ✅ Verificar la integridad con el hash.
- ✅ Referenciar los archivos en la demanda.
- ✅ Hacer backup cifrado externo.
- ✅ Presentar como prueba en el juicio (los originales son las cartas escaneadas y los audios).

## Conexión con otras carpetas

Esta carpeta es transversal al caso: los archivos de aquí son referenciados desde los análisis, los templates y los escritos judiciales.

- **Legal** (`../03-legal/`) — usa los audios y cartas como prueba.
- **Hechos** (`../02-hechos/`) — mapea cada hecho a un archivo de esta carpeta.
- **Estrategia** (`../04-estrategia/`) — define el orden de presentación de las pruebas.
- **Cuantificación** (`../05-cuantificacion/`) — usa el contrato para calcular la antigüedad.
- **Análisis especializado** (`../08-analisis-especializado/`) — usa las cartas para análisis técnico.

---

*Documento de evidencia. Los archivos de esta carpeta NO deben modificarse.*

# Fin del documento
