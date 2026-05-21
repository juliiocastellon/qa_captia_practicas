# 🖥️ Alarmas – KPIs de Alarmas

**Objetivo Principal:** Permite al usuario evaluar el rendimiento del sistema de gestión de alarmas mediante indicadores clave de operación, análisis de tendencias y métricas de reducción de ruido, en un rango temporal configurable.

## 📸 Mapeo de Interfaz

<img width="1347" height="482" alt="image" src="https://github.com/user-attachments/assets/fa9cb55d-d265-466a-bc6e-2971d6e99856" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Título "KPIs de Alarmas" | Cabecera informativa | — | — |
| 2 | Accesos rápidos de rango temporal | Botones de acceso rápido | Aplica un intervalo de tiempo predefinido a todos los KPIs | Úsalos para cambiar el horizonte de análisis y comparar el rendimiento en distintos periodos sin configuración adicional. |
| 3 | KPI "Tasa Alarmas/h" | Tarjeta de métrica | — | Compáralo con el objetivo para saber si la frecuencia de alarmas está dentro de los niveles aceptables. |
| 4 | KPI "MTTA (min)" | Tarjeta de métrica | — | Compáralo con el objetivo para evaluar si el equipo está reconociendo las alarmas con suficiente rapidez. |
| 5 | KPI "MTTR (min)" | Tarjeta de métrica | — | Compáralo con el objetivo para evaluar si las alarmas se están resolviendo dentro del tiempo comprometido. |
| 6 | KPI "SLA Breach" | Tarjeta de métrica | — | Comprueba que el valor sea 0; cualquier número mayor indica alarmas que han superado el tiempo de respuesta comprometido. |
| 7 | KPI "Carga Cognitiva" | Tarjeta de métrica | — | Úsalo para detectar si el volumen de alarmas está generando una carga excesiva sobre los operadores. |
| 8 | Gráfico "Tasa de Alarmas (24h)" | Gráfico de línea temporal | — | Úsalo para identificar en qué momentos del día o del turno se concentra el mayor número de alarmas. |
| 9 | Panel "Top Infractores" | Listado informativo | — | Revísalo para localizar los activos o reglas que más alarmas generan y priorizar acciones de mejora. |
| 10 | Sección "Reducción de Ruido" | Panel de métricas agrupadas | — | Consúltala para evaluar si los mecanismos de filtrado están reduciendo eficazmente el ruido operativo antes de que llegue al operador. |
| 11 | Métrica "Deduplicadas" | Indicador numérico | — | Comprueba este porcentaje para saber cuántas alarmas repetidas está filtrando automáticamente el sistema. |
| 12 | Métrica "Suprimidas" | Indicador numérico | — | Comprueba este porcentaje para saber cuántas alarmas están siendo inhibidas por reglas de mantenimiento activas. |
| 13 | Métrica "Aparcadas" | Indicador numérico | — | Comprueba este porcentaje para saber cuántas alarmas han sido apartadas temporalmente para revisión posterior. |

## 💡 Guía de Uso

La pestaña **KPIs de Alarmas** centraliza los indicadores de rendimiento que permiten evaluar la salud operativa del sistema de gestión de alarmas. Selecciona el horizonte temporal de análisis con los **accesos rápidos** (2) —desde 1 hora hasta 7 días— para actualizar simultáneamente todos los indicadores. Los cinco **KPIs de cabecera** (3–7) muestran de un vistazo las métricas más críticas: frecuencia de alarmas, tiempos de respuesta y resolución, incumplimientos de SLA y carga sobre el operador, cada uno con su objetivo de referencia para facilitar la interpretación. El **gráfico de tasa (24h)** (8) permite identificar patrones temporales de actividad, mientras que **Top Infractores** (9) ayuda a localizar los focos que más alarmas generan. Por último, la sección **Reducción de Ruido** (10) ofrece visibilidad sobre la eficacia de los mecanismos de filtrado activos, indicando qué porcentaje de alarmas han sido deduplicadas, suprimidas o aparcadas antes de llegar al operador.
