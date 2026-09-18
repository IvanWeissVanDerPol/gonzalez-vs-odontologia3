# Sesiones N°93-95 — Preservación de fotos del roster (servidor O3), swap de foto "Gabriella" en junio 2025, infraestructura digital del grupo

**Fecha:** 2026-09-18 (continuación autónoma, mismo día)
**Evidencia:** `12-evidencia/capturas-web-2026-09-18/fotos-roster/` — 12 PNG descargados del servidor propio de O3 (HTTP 200), SHA-256 en `MANIFEST-capturas-2026-09-18.txt`.

---

## 1. Fotos descargadas del servidor de O3 (mapeo a testigos)

Archivo original del CMS de O3 (`wp-content/uploads/2019/08-09/`) → el nombre del archivo VINCULA foto y persona, firmado por la propia empresa:

| Archivo (servidor O3) | Persona (según nomenclatura CMS) | Rol en el caso |
|---|---|---|
| `odo3-dr-monica-lird.png` (29.5 KB) | Dra. Mónica Lird | Testigo directo |
| `odo3-dr-roberto-de-jesus.png` (31.5 KB) | Dr. Roberto de Jesús | Testigo directo |
| `odo3-prof-luiz-meza.png` (22.5 KB) | Dr. Luís Meza | Testigo directo |
| `odo3-dr-ruben-rivarola.png` (30.6 KB) | Dr. Rubén Rivarola | Testigo directo |
| `odo3-dr-Dra.-Maria-Gloria-Acosta.png` (35.2 KB) | Dra. María Gloria Acosta | Testigo directo |
| `odo3-dr-camila-hernandez.png` (28.1 KB) | Dra. Camila Hernández | Testigo directo |
| `odo3-dr-viviana-gonzalez.png` (34.6 KB) | Dra. Viviana González | Homónimo ya distinguido |
| `odo3-dr-maria-jose-gonzalez.png` (35.8 KB) | Dra. María José González | Homónimo a distinguir |
| `46.png` (22.5 KB, 300×300) | Tarjeta "Gabriella González" 2019-2025 | Posible demandante — versión vieja |
| `Dra.-Gabriella-2.png` (838 KB, 1200×1200) | "Gabriella González" desde jun-2025 | Posible demandante — versión nueva |
| `odo3-profesional-.png` (2.7 KB, 300×300) | Tarjeta "Cinthia Ventre" en snapshot 2025-03 | Nombre genérico: probable placeholder, NO asumir que es su rostro |
| `odo3-dr-Dra.-Gabriella...` (resto) | reserva | — |

**Nota honesta:** la tarjeta de Ventre usaba una imagen genérica de baja resolución (2.7 KB) — la prueba de su plantilla es el TEXTO del roster ("Dra. Cinthia Ventre — Odontopediatría", snapshots 2022 y 2025-03), no esa imagen.

---

## 2. El hallazgo: foto de "Gabriella González" REEMPLAZADA en junio 2025

- Tarjeta 2019→2025-03: foto `46.png` (300×300, formato tarjeta).
- Snapshot 2025-09-07 y página viva: foto nueva `Dra.-Gabriella-2.png` (1200×1200, retrato profesional de alta resolución, subida a `/uploads/2025/06/`).
- **La página de profesionales fue rehecha en Q2-2025**: dentro de la misma ventana donde Ventre fue purgada (18/03→13/06/2025), alguien (a) eliminó a Ventre, (b) cambió especialidad publicada de Gabriella de "Rehabilitación Oral" a "operatoria y estética dental", y (c) subió una foto NUEVA de Gabriella en junio 2025.
- **Si la foto es de Gabi:** O3 la re-publicó como profesional ACTIVA con imagen actualizada en junio 2025 — mientras (según su relato) la relación ya estaba rota o se estaba rompiendo. Esto alimenta la línea de "vínculo continuo" y contradice cualquier "egreso antiguo".
- **Verificación pendiente (Gabi, 2 min):** confirmar identidad visual en `fotos-roster/Dra.-Gabriella-2.png` y `46.png`. El modelo activo de esta sesión es solo-texto (glm-4.6/zai), la identificación final no puede automatizarse aquí.
- **Fecha a cruzar:** pedir a Gabi su fecha exacta de cese/alejamiento para ver si la foto de jun-2025 es anterior o posterior.

---

## 3. Infraestructura digital del grupo (para embargo de intangibles y oficios)

Dominios probados hoy (DNS + HTTP):
```
odontologia3.com    → ACTIVO (WordPress + CDN i0.wp.com/Jetpack)
vanguard.com.py     → sin registro A (inexistente/parqueado)
sante.com.py        → sin registro A
scultura.com.py     → sin registro A
tecnodent.com.py    → sin registro A
casadelodontologo.com.py → sin registro A
odontologia3.com.py → sin registro A (solo operan bajo .com)
```
**Implicancias:**
1. El activo digital del grupo está centralizado en `odontologia3.com` (dónde: WordPress.com/Jetpack + CDN). Embargable como bien intangible a nombre de quien figure en el registro del dominio (verificar WHOIS/RDAP — privado, pedir a Carlos oficio).
2. Las marcas secundarias (Vanguard/Santé/Scultura/Tecnodent) NO tienen dominios propios: operan dentro del ecosistema O3 → refuerza unidad económica.
3. Correo corporativo presumiblemente `@odontologia3.com` → oficios de preservación de datos (servidor de correo, agendas, WhatsApp Business 0971 907-913) dirigidos a esa infraestructura.

---

## 4. Estado de la sesión

- 12 fotos + 10 HTML + MANIFEST actualizado: todo commiteado con SHA-256.
- `vision_analyze` no disponible en este runtime (modelo texto-only): identificación fotográfica → Gabi/Carlos.
- NuestrosComercios/DICOM: sin resultados públicos indexados → el camino correcto sigue siendo certificado DGRP ( Carlos, 1 página por RUC).

## Acciones inmediatas que quedan para humanos
1. **Gabi:** (a) confirmar identidad en las 2 fotos de "Gabriella González"; (b) fecha exacta de cese; (c) PDF del LinkedIn de Verónica Amarilla Matto.
2. **Carlos:** RDAP/WHOIS de odontologia3.com vía oficio; certificados DGRP de las 5 cabezas.
3. **Equipo:** mantener vigilancia mensual del roster (si borran a "Gabriella González" tras recibir la demanda, es destrucción de prueba EN CURSO — ya documentamos el patrón con Ventre).
