# 🖥️ Alarmas – Overview (Centro de Alarmas)

**Objetivo Principal:** Permite al usuario obtener una visión global y en tiempo real del estado del sistema de alarmas, incluyendo métricas clave, alarmas prioritarias activas, incidentes en curso y distribución de alarmas por prioridad.

## 📸 Mapeo de Interfaz

<img width="1202" height="472" alt="image" src="https://github.com/user-attachments/assets/84c85785-8285-4bb1-8109-cb261c688c8a" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Título "Centro de Alarmas" | Cabecera informativa | — | — |
| 2 | Indicador "En vivo" | Badge de estado | Activa/desactiva la actualización en tiempo real | Actívalo para que todos los datos del panel se actualicen automáticamente sin necesidad de recargar la página. |
| 3 | KPI "Activas" | Tarjeta de métrica | — | Comprueba este valor de un vistazo para saber si hay alarmas que requieren atención inmediata. |
| 4 | KPI "Sin Reconocer" | Tarjeta de métrica | — | Revisa este valor para saber cuántas alarmas están esperando ser reconocidas por un operador. |
| 5 | KPI "MTTA (min)" | Tarjeta de métrica | — | Úsalo para evaluar si el equipo está respondiendo a las alarmas dentro del tiempo objetivo establecido. |
| 6 | KPI "Incidentes" | Tarjeta de métrica | — | Comprueba este valor para saber si alguna alarma ha generado un incidente que requiera seguimiento. |
| 7 | Gráfico "Tasa de Alarmas (2h)" | Gráfico de línea temporal | — | Úsalo para detectar picos de actividad inusuales y anticipar situaciones de sobrecarga operativa. |
| 8 | Sección "Alarmas Prioritarias" | Listado | Accede al detalle de cada alarma | Revisa este listado para identificar qué alarmas llevan más tiempo activas sin ser atendidas y priorizarlas. |
| 9 | Sección "Incidentes Principales" | Listado informativo | — | Comprueba esta sección para saber si alguna alarma ha escalado a un incidente que requiera gestión específica. |
| 10 | Mapa de Calor "Alarmas Activas" | Visualización / Heatmap | — | Úsalo para identificar de un vistazo en qué nivel de prioridad se concentran las alarmas activas y dónde enfocar la respuesta. |

## 💡 Guía de Uso

La pestaña **Overview** del Centro de Alarmas es el panel de control principal para la supervisión del estado de alarmas en tiempo real. Los cuatro **KPIs** de la cabecera (3–6) ofrecen de un vistazo las métricas más críticas: número de alarmas activas, alarmas pendientes de reconocimiento, tiempo medio de respuesta e incidentes abiertos. El **gráfico de tasa de alarmas** (7) permite identificar picos de actividad en las últimas horas, mientras que la sección **Alarmas Prioritarias** (8) lista aquellas que requieren atención inmediata junto con su antigüedad y estado. Por último, el **Mapa de Calor** (12) proporciona una visión rápida de la concentración de alarmas por nivel de prioridad, facilitando la priorización de la respuesta operativa. Activa el modo **En vivo** (2) para mantener todos los datos actualizados automáticamente.
