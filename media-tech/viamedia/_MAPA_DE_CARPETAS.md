# 🗺 Mapa de Directorios Numerados: Viamedia (CEO Cockpit)

Esta guía sirve para identificar rápidamente qué tipo de documentos y URLs contiene cada directorio numérico dentro de `baus-ceo-web/media-tech/viamedia/`.

Esta numeración permite ofuscar las URLs frente a terceros y mantener un orden ejecutivo dentro de la plataforma `baus.ceo`.

**Regla canónica (sincronizada con [CLAUDE.md](../../../CLAUDE.md) §4):**

```
baus-ceo-web/media-tech/viamedia/[NNNN]/[slug]/
  ├─ index.html      ← documento renderizado
  ├─ source.md       ← fuente editable (obligatorio)
  └─ assets/         ← imágenes/recursos (vacío si no aplica)
```

URL pública: `baus.ceo/media-tech/viamedia/[NNNN]/[slug]/`

---

## 📂 7391: Propuestas Comerciales y Patrocinios
**Propósito:** Alojar todas las propuestas de ventas, decks para clientes corporativos de compra programática e integraciones de datos.
- **Ejemplos:** Propuesta de Apertura (Crece Fácil).
- **URL:** `baus.ceo/media-tech/viamedia/7391/[cliente]/`

## 📂 8452: Reportes de Campaña y Operativos (Ongoing Campaigns)
**Propósito:** Centralizar los informes de rendimiento mensual, dashboards ejecutivos de pauta programática y monitoreo de inventario.
- **Ejemplos:** Reportes de branding, monitoreo de deals.
- **URL:** `baus.ceo/media-tech/viamedia/8452/[version]/`

---

## Crear una nueva categoría

Cualquier nueva categoría operativa (ej. Finanzas, Casos de Estudio) debe:

1. Asignarse una numeración de 4 dígitos aleatorios no repetida (1000-9999).
2. Registrarse aquí con propósito, ejemplos y URL.
3. Crearse la estructura `[NNNN]/[slug]/{index.html,source.md,assets/}` desde el inicio.

Categorías actuales reservadas: `7391, 8452`.
