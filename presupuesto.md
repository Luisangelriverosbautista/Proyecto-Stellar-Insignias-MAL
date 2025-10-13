# Manual Profesional de Gestión de Proyectos en GitHub  
## Proyecto: GreenTech Hub – Comunidad Digital de Innovación Sostenible  

---

## I. Configuración Inicial y Roles Fundamentales 📊

| Rol / Perfil | Responsabilidades Principales | Tarifa Horaria (USD) | Asignación en GitHub |
|---------------|-------------------------------|----------------------|----------------------|
| **Luis Ángel – Gestor del Proyecto (PM)** | Coordinación general, seguimiento de tareas, control de presupuesto. | $25/h | @LuisAngel |
| **Alain – Diseñador y Programador Web** | Diseño visual, desarrollo frontend y backend, integración de multimedia. | $30/h | @AlainDev |
| **Marlen – Documentación y Comunicación** | Redacción, comunicación, difusión y control de versiones. | $20/h | @MarlenWriter |

**Costos Indirectos:**  
Herramientas y servicios (Trello, Notion, Canva, Audacity, OBS Studio, Hosting Web): **$100 USD**

---

## II. Estructura del Tablero de GitHub Projects 

**Nombre del tablero:** `GreenTechHub-Lifecycle`  
**Tipo de vista:** Kanban  

**Columnas del flujo de trabajo (fases del proyecto):**
1. **Fase 0: Análisis y Factibilidad**  
2. **Fase 1: Diseño y Planificación (EDT)**  
3. **Fase 2: Desarrollo e Integración**  
4. **Fase 3: Pruebas, Despliegue y Difusión**

---

## III. Fase 0: Análisis y Factibilidad 

**Actividad 0.1 – Estudio de Viabilidad y Riesgos**

| Descripción | Acción en GitHub | Responsable | Tiempo Estimado | Costo |
|--------------|------------------|--------------|------------------|--------|
| Definir el alcance, riesgos y beneficios del proyecto. | Crear Issue: `0.1. Análisis de Factibilidad y Riesgo` | @LuisAngel | 8h | $200 |
| Redactar el Acta de Constitución del Proyecto. | Crear archivo `README.md` con justificación y objetivos. | @MarlenWriter | 5h | $100 |

**Total Fase 0:**  13h →  **$300 USD**

---

## IV. Fase 1: Diseño y Planificación 

**Actividad 1.1 – Construcción de la EDT (Estructura de Desglose del Trabajo)**

| Descripción | Acción en GitHub | Responsable | Tiempo Estimado | Costo |
|--------------|------------------|--------------|------------------|--------|
| Definir módulos del proyecto: contenido, insignias, multimedia, comunidad. | Crear Issue: `1.1. Definición de Módulos Principales` | @LuisAngel | 6h | $150 |
| Desglosar cada módulo en tareas concretas. | Crear Issues secundarios bajo cada módulo. | @AlainDev | 8h | $240 |
| Crear cronograma en GitHub Projects. | Actualizar columnas y milestones. | @MarlenWriter | 4h | $80 |

**Actividad 1.2 – Estimación y Asignación de Tiempos**

Ejemplo de plantilla para cada *Issue*:
```markdown
**METADATOS DE GESTIÓN**
*  **Tiempo Estimado:** 10 horas
*  **Costo Estimado:** $250
* **Justificación:** Estimación consensuada tras análisis de complejidad.
```

**Total Fase 1:**  18h →  **$470 USD**

---

## V. Fase 2: Desarrollo e Integración 

**Actividad 2.1 – Asignación de Responsabilidades**

| Descripción | Acción en GitHub | Responsable | Tiempo Estimado | Costo |
|--------------|------------------|--------------|------------------|--------|
| Desarrollar estructura del sitio web (HTML/CSS/JS). | Issue: `2.1. Desarrollo Frontend` | @AlainDev | 16h | $480 |
| Implementar sistema de insignias digitales. | Issue: `2.2. Sistema de Insignias` | @AlainDev | 10h | $300 |
| Redacción y carga de contenido educativo. | Issue: `2.3. Publicación de Artículos y Podcasts` | @MarlenWriter | 8h | $160 |
| Coordinación y revisión del desarrollo. | Issue: `2.4. Supervisión Técnica` | @LuisAngel | 6h | $150 |

**Total Fase 2:**  40h →  **$1,090 USD**

---

## VI. Fase 3: Pruebas, Despliegue y Difusión 

**Actividad 3.1 – Pruebas de Calidad y Funcionalidad**

| Descripción | Acción en GitHub | Responsable | Tiempo Estimado | Costo |
|--------------|------------------|--------------|------------------|--------|
| Verificación de usabilidad y enlaces. | Issue: `3.1. Pruebas de Interfaz` | @MarlenWriter | 6h | $120 |
| Validación técnica y revisión del contenido. | Issue: `3.2. QA de Contenido y Multimedia` | @LuisAngel | 4h | $100 |
| Ajustes finales del sitio y despliegue. | Issue: `3.3. Despliegue Final` | @AlainDev | 5h | $150 |

**Actividad 3.2 – Cierre del Proyecto y Reporte Final**

| Descripción | Acción en GitHub | Responsable | Tiempo Estimado | Costo |
|--------------|------------------|--------------|------------------|--------|
| Crear archivo `BUDGET.md` con resumen financiero. | Subir a repositorio raíz. | @LuisAngel | 3h | $75 |
| Documentar resultados y aprendizajes. | Issue: `3.4. Informe Final` | @MarlenWriter | 4h | $80 |

**Total Fase 3:**  22h →  **$525 USD**

---

## VII. Resumen Financiero Global 

| Fase | Horas Totales | Costo Total |
|------|----------------|--------------|
| Fase 0 – Análisis y Factibilidad | 13h | $300 |
| Fase 1 – Diseño y Planificación | 18h | $470 |
| Fase 2 – Desarrollo e Integración | 40h | $1,090 |
| Fase 3 – Pruebas y Despliegue | 22h | $525 |
| **Costos Indirectos (herramientas)** | — | $100 |

** Costo Total del Proyecto: $2,485 USD**  
** Tiempo Total Estimado: 93 horas**

---

## VIII. Recomendaciones para el Tablero de GitHub 

1. **Crear Issues** con títulos como:
   - `0.1. Análisis de Factibilidad y Riesgo`
   - `2.1. Desarrollo Frontend`
   - `3.3. Despliegue Final`
2. **Asignar etiquetas (Labels)** por costo:
   - `costo-$150`, `costo-$300`, etc.
3. **Asignar responsables** con *Assignees*:
   - @LuisAngel, @AlainDev, @MarlenWriter
4. **Agregar hitos (Milestones)** por fase del proyecto.
5. **Actualizar la columna** de cada tarea conforme avanza la fase.
6. **Crear archivo `BUDGET.md`** con el resumen total de costos y justificación.

---

## IX. Conclusión 

El proyecto **GreenTech Hub** utiliza prácticas profesionales de gestión digital basadas en GitHub para planificar, ejecutar y controlar todas sus fases de desarrollo.  
Este manual garantiza **transparencia, trazabilidad y eficiencia**, fomentando la colaboración del equipo y la sostenibilidad en la gestión tecnológica.

---

 **Elaborado por el Equipo GreenTech Hub**  
- Luis Ángel – Gestor del Proyecto  
- Alain – Diseñador y Programador Web  
- Marlene – Documentación y Comunicación  
