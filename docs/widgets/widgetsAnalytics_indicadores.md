# 🖥️ Indicadores

**Objetivo Principal:** Permite al usuario seleccionar e insertar elementos visuales de medición y seguimiento de métricas clave en su dashboard o vista.

## 📸 Mapeo de Interfaz

<img width="947" height="657" alt="Captura de pantalla 2026-05-19 121159" src="https://github.com/user-attachments/assets/10b68258-2b7f-4b23-b585-47878c623f29" />

## 🧩 Despiece de Elementos Funcionales

| Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- |
| Sección "Indicadores" (3.3) | Grupo / Acordeón | Expande/colapsa el bloque | Agrupa todos los elementos de tipo indicador disponibles. Muestra un contador (5) con la cantidad de subelementos. |
| KPI (3.3.1) | Elemento seleccionable | Inserta un indicador de métrica clave | Muestra un valor único y destacado que representa una métrica clave del negocio. |
| KPI Calculado (3.3.2) | Elemento seleccionable | Inserta un KPI con fórmula personalizada | Permite definir una fórmula de cálculo propia para derivar el valor mostrado a partir de otras métricas. |
| Gauge Radial (3.3.3) | Elemento seleccionable | Inserta un indicador circular de progreso | Visualiza el nivel de cumplimiento o progreso de una métrica mediante un arco o dial circular. |
| Gauge (3.3.4) | Elemento seleccionable | Inserta un indicador de nivel o progreso | Representa el estado de una métrica en forma de velocímetro o barra de progreso semicircular. |
| Grupo de KPIs (3.3.5) | Elemento seleccionable | Inserta un panel de múltiples métricas en rejilla | Permite mostrar simultáneamente varios KPIs organizados en una cuadrícula, facilitando la comparativa rápida. |

## 💡 Guía de Uso 

En la sección **Indicadores** dispones de cinco elementos para visualizar el rendimiento y seguimiento de tus métricas. Para mostrar un valor puntual y directo, utiliza **KPI** (3.3.1); si ese valor debe calcularse a partir de una fórmula propia, opta por **KPI Calculado** (3.3.2). Cuando necesites representar el progreso hacia un objetivo de forma visual, puedes elegir entre **Gauge Radial** (3.3.3), con formato circular, o **Gauge** (3.3.4), con formato de velocímetro. Por último, si quieres presentar varias métricas de forma compacta y comparativa en un mismo espacio, selecciona **Grupo de KPIs** (3.3.5). El contador (5) en la cabecera de la sección te indica el total de elementos disponibles, y puedes colapsar o expandir el bloque en cualquier momento usando la flecha de la derecha.

[← Anterior](./widgetsAnalytics_graficos.md) • [📚 Índice](../README.md) • [Siguiente →](./widgetsAnalytics_maintenance_KPIS.md)
