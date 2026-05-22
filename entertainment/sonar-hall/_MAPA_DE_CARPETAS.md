# 🗺 Mapa de Directorios Numerados: Sonar Hall (CEO Cockpit)

Esta guía sirve para identificar rápidamente qué tipo de documentos y URLs contiene cada directorio numérico dentro de `baus-ceo-web/entertainment/sonar-hall/`.

Esta numeración permite ofuscar las URLs frente a terceros y mantener un orden ejecutivo dentro de la plataforma `baus.ceo`.

**Regla canónica (sincronizada con [CLAUDE.md §11](../../../CLAUDE.md)):**

```
baus-ceo-web/entertainment/[unidad]/[NNNN]/[slug]/
  ├─ index.html      ← documento renderizado
  ├─ source.md       ← fuente editable (obligatorio)
  └─ assets/         ← imágenes/recursos (vacío si no aplica)
```

URL pública: `baus.ceo/entertainment/[unidad]/[NNNN]/[slug]/`

---

## 📂 1284: Minutas de Alineación y Acuerdos
**Propósito:** Documentar oficialmente las juntas críticas, alineaciones estratégicas entre socios (BAUS - Índigo), bitácoras de incidentes y "Next Steps".
- **Ejemplos:** Minuta de crisis de boleteras, alineación del Mundial (The Match Lounge), re-estructuración de modelo de negocio.
- **URL:** `baus.ceo/entertainment/sonar-hall/1284/[slug_minuta]/`

## 📂 3306: Handovers y Transiciones Operativas
**Propósito:** Dashboards de transición de equipo, handovers entre roles, documentos de pasaje de funciones.
- **Ejemplos:** Handover Dashboard Mayo 2026 (post-ruptura Indigo, transición Fausto a booker externo).
- **URL:** `baus.ceo/entertainment/sonar-hall/3306/[slug_handover]/`

## 📂 7391: Propuestas Comerciales y Patrocinios
**Propósito:** Alojar todas las propuestas de ventas, decks para patrocinadores y alianzas estratégicas.
- **Ejemplos:** Propuesta de Naming Right (Ninja), Activaciones (Coca-Cola), Decks Comerciales (LGCY, Renata Gonzalez).
- **URL:** `baus.ceo/entertainment/sonar-hall/7391/[marca]/`

## 📂 8294: Auditorías de Viabilidad de Artistas
**Propósito:** Análisis y due diligence de artistas evaluados para booking en Sonar Hall (viabilidad económica, perfil de audiencia, riders, fit con la marca).
- **Ejemplos:** Mind Against, Stacey Pullen, Tiesto.
- **URL:** `baus.ceo/entertainment/sonar-hall/8294/[artista]/`

## 📂 8452: Reportes Operativos (Ongoing Operations)
**Propósito:** Centralizar los reportes ejecutivos de estatus del venue, calendarios de eventos y pipeline de rentas/in-house.
- **Ejemplos:** Tablas de eventos confirmados, en negociación y prospectos (UI/UX Premium).
- **URL:** `baus.ceo/entertainment/sonar-hall/8452/[version]/`

## 📂 5108: Gobernanza y Comunicación con Socios
**Propósito:** Decks ejecutivos, frameworks operativos y propuestas internas dirigidas a socios capitalistas (Celesta · Roberto · Sam · Gou). Material de alta sensibilidad — **no auto-publica**.
- **Ejemplos:** Framework Operativo post-Indigo (22-may-2026), revisiones estratégicas con el Board, propuestas de re-estructuración de rol.
- **URL:** `baus.ceo/entertainment/sonar-hall/5108/[slug]/`
- ⚠️ **Sensibilidad:** contiene quotes textuales privados, montos, percepción de stakeholders. Requiere orden explícita para publicación pública.

---

## Crear una nueva categoría

Cualquier nueva categoría operativa (ej. Finanzas, Planos Técnicos, Permisos) debe:

1. Asignarse una numeración de 4 dígitos aleatorios no repetida (1000-9999).
2. Registrarse aquí con propósito, ejemplos y URL.
3. Crearse la estructura `[NNNN]/[slug]/{index.html,source.md,assets/}` desde el inicio.

Categorías actuales reservadas: `1284, 3306, 5108, 7391, 8294, 8452`.
