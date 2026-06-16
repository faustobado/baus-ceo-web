# Esquema de Preguntas y Campos del Formulario

> **Instrucciones para el CEO:** Modifica los textos, etiquetas o añade/quita opciones directamente en este archivo. Cuando termines, indícame: *"Actualiza el formulario en base a formulario_preguntas.md"* y yo regeneraré el `index.html` de forma automática.

---

## SECCIÓN 1: Información General

*Datos del ejecutivo de cuenta, marca y detalles del deal.*

1. **ae_nombre** titular de la cuenta (Requerido)
   
   - **Etiqueta:** Nombre completo del Titular de la Cuenta
   - **Placeholder:** Ej: Fausto Bado Rocha

2. **ae_email** (Requerido)
   
   - **Etiqueta:** Email del AE
   - **Placeholder:** nombre@bemassive.mx

3. **nombre_campana** (Requerido)
   
   - **Etiqueta:** Nombre de la Campaña
   - **Placeholder:** Agencia_Marca_Detalle_Fecha

4. **hay_agencia** (Requerido)
   
   - **Etiqueta:** ¿Hay agencia involucrada?
   - **Opciones:** Sí, No

5. **nombre_agencia** (Opcional)
   
   - **Etiqueta:** Nombre de la Agencia
   - **Placeholder:** Dejar vacío si no aplica

6. **trabajo_previo_agencia** (Opcional)
   
   - **Etiqueta:** ¿Hemos trabajado previamente con esta agencia?
   - **Opciones:** Sí, trabajado | Sí, enviado propuestas | No

7. **marca** (Requerido)
   
   - **Etiqueta:** Marca / Anunciante
   - **Placeholder:** Nombre comercial de la marca

8. **sitio_web** (Requerido)
   
   - **Etiqueta:** Sitio web de la Marca
   - **Placeholder:** https://...

9. **trabajo_previo_marca** (Requerido)
   
   - **Etiqueta:** ¿Trabajo previo con esta marca?
   - **Opciones:** Sí, No

10. **industria_restringida** (Opcional)
    
    - **Etiqueta:** Industria restringida
    - **Opciones:** N/A, Cannabis, Armas de fuego, Alcohol, Tabaco, Otro

11. **tipo_servicio** (Requerido)
    
    - **Etiqueta:** Tipo de Servicio
    - **Opciones:** Servicio Gestionado (Managed Service), Autoservicio

12. **fecha_solicitud** (Requerido)
    
    - **Etiqueta:** Fecha de solicitud
    - **Nota:** Autocompletado con la fecha de hoy

13. **fecha_entrega** (Requerido)
    
    - **Etiqueta:** Fecha de entrega requerida

14. **por_que_massive_impact** (Requerido)
    
    - **Etiqueta:** ¿Por qué MI está siendo considerado?
    - **Ayuda:** ¿Qué elementos de nuestra oferta resonaron con el cliente?

---

## SECCIÓN 2: Datos Básicos de la Campaña

*Fechas, presupuesto, creativos y objetivos generales.*

19. **fecha_inicio** (Requerido)
    
    - **Etiqueta:** Fecha de inicio

20. **fecha_fin** (Requerido)
    
    - **Etiqueta:** Fecha de fin

21. **presupuesto_total_costos** (Requerido)
    
    - **Etiqueta:** Presupuesto total costos (USD)
    - **Placeholder:** 25000 (Mínimo 1000)

22. **distribucion_uniforme** (Requerido)
    
    - **Etiqueta:** ¿Distribución uniforme?
    - **Opciones:** Sí, No

23. **ponderacion delivery impresiones** (Opcional)
    
    - **Etiqueta:** Solicitudes específicas de flighting
    - **Ayuda:** Heavy-up horarios, distribución flexible por geografía, etc.

24. **assets_creativos** (Requerido - Opción Múltiple)
    
    - **Etiqueta:** Assets creativos disponibles
    - **Opciones:** Video, Audio, Display, Attention+, CTV.

25. **duracion_video** (Opcional - Opción Múltiple)
    
    - **Etiqueta:** Duración de video
    - **Opciones:** 15s, 30s, 60s

26. **proposito** (Requerido)
    
    - **Etiqueta:** Propósito de la campaña
    - **Ayuda:** Contexto del cliente, objetivos, challenge, enfoque

27. **benchmarks** (Opcional)
    
    - **Etiqueta:** Benchmarks / KPIs objetivo por canal
    - **Ayuda:** Ej: OLV VCR 60-70%, Audio-LTR >90%, CTV-VCR >90%, Attention+ -CTR + Viewability

28. **medicion** (Opcional)
    
    - **Etiqueta:** Requisitos de medición
    - **Opciones:** Ninguno, Brand Lift, Conversiones, Otro

---

## SECCIÓN 3: Targeting de la Campaña

*Audiencia y geografía.*

35. **targeting_audiencia** (Requerido)
    
    - **Etiqueta:** Targeting de audiencia
    - **Ayuda:** Demográfico, comportamental, buyer person, split de audiencia, targeting, etc.

36. **tipo_geografia** (Requerido)
    
    - **Etiqueta:** Tipo de geografía
    - **Opciones:** Nacional, Regional, Ciudades específicas, Geo-fencing, Otro

37. **detalle_geografia** (Requerido)
    
    - **Etiqueta:** Detalle de la geografía
    - **Ayuda:** Ciudades, estados, zonas de geo-fence, ubicaciones de tiendas, etc.

38. **link_google_maps** (Requerido)
    
    - **Etiqueta:** Link de Google Maps para Geo-fence
    - **Placeholder:** https://www.google.com/maps/... o https://maps.app.goo.gl/...

---

## SECCIÓN 4: Estrategia de Campaña

*Productos a incluir y presupuestos por canal.*

38. **productos_incluir** (Requerido - Opción Múltiple)
    
    - **Etiqueta:** Productos a incluir
    - **Opciones:** OLV, Streaming Audio, Podcast Audio, Attention+ Mobile, Attention+ CTV, CTV Only RON, OTT RON, Display.

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

40. **detalles_canales** (Opcional)
    
    - **Etiqueta:** Detalles adicionales sobre los canales y formatos
    - **Placeholder:** Ej: Todos los productos deben correr en Geo: México, contenido en español

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
      - **KPI primario — Display:** N/A, CTR, Viewability, CPM

---

## SECCIÓN 6: Información Adicional

*Notas y archivos adicionales.*

44. **info_adicional** (Opcional)
    
    - **Etiqueta:** ¿Algo más que debamos saber para que esta propuesta esté lista?

45. **archivos_relevantes** (Opcional)
    
    - **Etiqueta:** Adjuntar link de Google Drive de archivos relevantes (propuesta, brief, etc.)
    - **Placeholder:** https://drive.google.com/drive/folders/... o https://drive.google.com/file/...
