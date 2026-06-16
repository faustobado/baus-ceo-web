# Esquema de Preguntas y Campos del Formulario

> **Instrucciones para el CEO:** Modifica los textos, etiquetas o añade/quita opciones directamente en este archivo. Cuando termines, indícame: *"Actualiza el formulario en base a formulario_preguntas.md"* y yo regeneraré el `index.html` de forma automática.

---

## SECCIÓN 1: Información General
*Datos del ejecutivo de cuenta, marca y detalles del deal.*

1. **ae_nombre** (Requerido)
   - **Etiqueta:** Nombre completo del AE
   - **Placeholder:** Ej: Fausto Bado Rocha

2. **ae_email** (Requerido)
   - **Etiqueta:** Email del AE
   - **Placeholder:** nombre@viamedia.ai

3. **lider_ventas** (Requerido)
   - **Etiqueta:** Líder de Ventas
   - **Placeholder:** Selecciona o escribe el líder

4. **nombre_campana** (Requerido)
   - **Etiqueta:** Nombre de la Campaña
   - **Placeholder:** Agencia_Marca_Detalle_Fecha

5. **hay_agencia** (Requerido)
   - **Etiqueta:** ¿Hay agencia involucrada?
   - **Opciones:** Sí, No

6. **nombre_agencia** (Opcional)
   - **Etiqueta:** Nombre de la Agencia
   - **Placeholder:** Dejar vacío si no aplica

7. **trabajo_previo_agencia** (Opcional)
   - **Etiqueta:** ¿Hemos trabajado previamente con esta agencia?
   - **Opciones:** Sí, trabajado | Sí, enviado propuestas | No

8. **marca** (Requerido)
   - **Etiqueta:** Marca / Anunciante
   - **Placeholder:** Nombre comercial de la marca

9. **sitio_web** (Requerido)
   - **Etiqueta:** Sitio web de la Marca
   - **Placeholder:** https://...

10. **trabajo_previo_marca** (Requerido)
    - **Etiqueta:** ¿Trabajo previo con esta marca?
    - **Opciones:** Sí, No

11. **industria_restringida** (Opcional)
    - **Etiqueta:** Industria restringida
    - **Opciones:** N/A, Cannabis, Armas de fuego, Alcohol, Tabaco, Otro

12. **tipo_servicio** (Requerido)
    - **Etiqueta:** Tipo de Servicio
    - **Opciones:** Servicio Gestionado (Managed Service), Autoservicio

13. **link_hubspot** (Opcional)
    - **Etiqueta:** Link al Deal en HubSpot
    - **Placeholder:** https://app.hubspot.com/...

14. **entregables** (Requerido)
    - **Etiqueta:** Entregables requeridos
    - **Opciones:** Solo Media Plan (2 días hábiles, $20k+), Media Plan + Propuesta Completa

15. **email_adicional** (Opcional)
    - **Etiqueta:** Email adicional para copia
    - **Placeholder:** copia@viamedia.ai

16. **fecha_solicitud** (Requerido)
    - **Etiqueta:** Fecha de solicitud
    - **Nota:** Autocompletado con la fecha de hoy

17. **fecha_entrega** (Requerido)
    - **Etiqueta:** Fecha de entrega requerida

18. **por_que_viamedia** (Requerido)
    - **Etiqueta:** ¿Por qué Viamedia está siendo considerada?
    - **Ayuda:** ¿Qué elementos de nuestra oferta resonaron con el equipo?

---

## SECCIÓN 2: Datos Básicos de la Campaña
*Fechas, presupuesto, creativos y objetivos generales.*

19. **fecha_inicio** (Requerido)
    - **Etiqueta:** Fecha de inicio

20. **fecha_fin** (Requerido)
    - **Etiqueta:** Fecha de fin

21. **presupuesto_total** (Requerido)
    - **Etiqueta:** Presupuesto total (USD)
    - **Placeholder:** 25000 (Mínimo 1000)

22. **distribucion_uniforme** (Requerido)
    - **Etiqueta:** ¿Distribución uniforme?
    - **Opciones:** Sí, No

23. **flighting** (Opcional)
    - **Etiqueta:** Solicitudes específicas de flighting
    - **Ayuda:** Heavy-up, go dark, distribución flexible por geografía, etc.

24. **assets_creativos** (Requerido - Opción Múltiple)
    - **Etiqueta:** Assets creativos disponibles
    - **Opciones:** Video, Audio, Display, Social, Attention+, CTV, OTT, Otro

25. **otros_assets** (Opcional)
    - **Etiqueta:** Si seleccionó 'Otro', especifique

26. **duracion_video** (Opcional - Opción Múltiple)
    - **Etiqueta:** Duración de video
    - **Opciones:** 6s, 15s, 30s, 60s

27. **proposito** (Requerido)
    - **Etiqueta:** Propósito de la campaña
    - **Ayuda:** Contexto del cliente, objetivos, challenge, enfoque dual si aplica

28. **benchmarks** (Opcional)
    - **Etiqueta:** Benchmarks / KPIs objetivo por canal
    - **Ayuda:** Ej: OLV VCR 60-70%, Audio LTR >90%, CTV VCR >90%, Attention+ CTR + Viewability

29. **pricing** (Opcional)
    - **Etiqueta:** Consideraciones de pricing
    - **Placeholder:** Ej: Rate Card LATAM 2026 aprobada

30. **aprobacion_tarifas** (Opcional)
    - **Etiqueta:** Referencia de aprobación de tarifas
    - **Placeholder:** Nombre del archivo de aprobación

31. **viewability** (Opcional)
    - **Etiqueta:** ¿Viewability garantizada?
    - **Opciones:** No, Sí

32. **medicion** (Opcional)
    - **Etiqueta:** Requisitos de medición
    - **Opciones:** Ninguno, Brand Lift, Foot Traffic, Conversiones, Otro

33. **fees_terceros** (Opcional)
    - **Etiqueta:** ¿Cubrir fees de terceros?
    - **Opciones:** Ninguno, Sí (especificar abajo)

34. **valor_agregado** (Opcional)
    - **Etiqueta:** Valor agregado solicitado
    - **Placeholder:** Dashboard, Brand Lift, etc.

---

## SECCIÓN 3: Targeting de la Campaña
*Audiencia y geografía.*

35. **targeting_audiencia** (Requerido)
    - **Etiqueta:** Targeting de audiencia
    - **Ayuda:** Demográfico, comportamental, personas AI, split de audiencia (ej: 50/50 TH vs No TH), tácticas de targeting

36. **tipo_geografia** (Requerido)
    - **Etiqueta:** Tipo de geografía
    - **Opciones:** Nacional, Regional, Ciudades específicas, Geo-fencing, Otro

37. **detalle_geografia** (Requerido)
    - **Etiqueta:** Detalle de la geografía
    - **Ayuda:** Ciudades, estados, zonas de geo-fence, ubicaciones de tiendas, etc.

---

## SECCIÓN 4: Estrategia de Campaña
*Productos a incluir y presupuestos por canal.*

38. **productos_incluir** (Requerido - Opción Múltiple)
    - **Etiqueta:** Productos a incluir
    - **Opciones:** OLV, Streaming Audio, Podcast Audio, Attention+ Mobile, Attention+ CTV, CTV Only RON, OTT RON, Display, Native, DOOH, Social, SEM, Email

39. **presupuesto_por_producto** (Opcional)
    - **Etiqueta:** ¿Tiene asignaciones de presupuesto por producto?
    - **Opciones:** No, Sí
    - **Campos de presupuesto mensual (USD) si activa 'Sí':**
      - Attention+ Mobile
      - Attention+ CTV
      - CTV RON
      - OTT RON
      - OLV
      - Streaming Audio
      - Podcast Audio
      - Display
      - Native
      - DOOH
      - Social
      - SEM
      - Email

40. **detalles_productos** (Opcional)
    - **Etiqueta:** Detalles adicionales sobre productos
    - **Placeholder:** Ej: Todos los productos deben correr en Geo: México, contenido en español

41. **productos_excluir** (Opcional)
    - **Etiqueta:** Productos a excluir
    - **Placeholder:** Ej: Solo incluir productos seleccionados arriba

---

## SECCIÓN 5: KPIs y Medición de Éxito
*Criterios de éxito y KPIs primarios.*

42. **criterio_exito** (Requerido)
    - **Etiqueta:** ¿Cómo se medirá el éxito? ¿Qué se necesita para renovar?

43. **kpis_primarios_canales** (Opcional)
    - **Mapeos de KPI por canal:**
      - **KPI primario — OTT:** N/A, VCR, CTR, Viewability, Reach
      - **KPI primario — CTV:** N/A, VCR, CTR, Viewability, Reach
      - **KPI primario — Attention+ Mobile:** N/A, CTR, Viewability, Engagement Rate
      - **KPI primario — OLV:** N/A, VCR, CTR, Viewability
      - **KPI primario — Audio:** N/A, Listen Rate, LTR, Reach
      - **KPI primario — Display:** N/A, CTR, Viewability, CPC
      - **KPI primario — DOOH:** N/A, Reach, Foot Traffic, Impressions
      - **KPI primario — Social:** N/A, CTR, Engagement, CPC, CPM

---

## SECCIÓN 6: Información Adicional
*Notas y archivos adicionales.*

44. **info_adicional** (Opcional)
    - **Etiqueta:** ¿Algo más que debamos saber para que esta propuesta esté lista?

45. **archivos_relevantes** (Opcional)
    - **Etiqueta:** Archivos adicionales relevantes
    - **Placeholder:** Ej: Brief_Falabella_EN.docx, Rate_Card_2026.xlsx
