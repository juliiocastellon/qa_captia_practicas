# 🖥️ Alarmas – Overview (Centro de Alarmas)

**Objetivo Principal:** Permite al usuario obtener una visión global y en tiempo real del estado del sistema de alarmas, incluyendo métricas clave, alarmas prioritarias activas, incidentes en curso y distribución de alarmas por prioridad.

## 📸 Mapeo de Interfaz

<img width="1202" height="472" alt="image" src="https://github.com/user-attachments/assets/84c85785-8285-4bb1-8109-cb261c688c8a" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Título "Centro de Alarmas" | Cabecera informativa | — | Identifica la vista actual como el panel central de gestión y supervisión de alarmas. |
| 2 | Indicador "En vivo" | Badge de estado | Activa/desactiva la actualización en tiempo real | Señala que los datos mostrados se están actualizando en tiempo real. El botón de play permite iniciar o pausar el modo en vivo. |
| 3 | KPI "Activas" | Tarjeta de métrica | — | Muestra el número total de alarmas activas en el momento de la consulta (valor actual: 2), identificadas con icono de campana en rojo. |
| 4 | KPI "Sin Reconocer" | Tarjeta de métrica | — | Indica el número de alarmas activas que aún no han sido reconocidas por ningún operador (valor actual: 2), señaladas con icono de advertencia en naranja. |
| 5 | KPI "MTTA (min)" | Tarjeta de métrica | — | Muestra el Tiempo Medio hasta el Reconocimiento de alarmas expresado en minutos. Permite evaluar la velocidad de respuesta del equipo operativo. |
| 6 | KPI "Incidentes" | Tarjeta de métrica | — | Muestra el número de incidentes activos asociados a alarmas (valor actual: 0), identificados con icono de verificación en morado. |
| 7 | Gráfico "Tasa de Alarmas (2h)" | Gráfico de línea temporal | — | Representa la frecuencia de disparo de alarmas en los últimos tramos temporales con resolución de 2 horas, permitiendo detectar picos o patrones de actividad anómala. |
| 8 | Sección "Alarmas Prioritarias" | Listado | Accede al detalle de cada alarma | Muestra las alarmas activas de mayor prioridad ordenadas por criticidad. Cada fila indica el nombre del monitor, el origen, el tiempo transcurrido desde su activación y su estado (active_unacked). |
| 9 | Sección "Incidentes Principales" | Listado informativo | — | Muestra los incidentes activos de mayor relevancia. En el estado actual no hay incidentes activos ("Sin incidentes activos"). |
| 10 | Mapa de Calor "Alarmas Activas" | Visualización / Heatmap | — | Representa gráficamente la distribución de alarmas activas por nivel de prioridad (P1–P4). La fila P2 muestra 2 alarmas activas resaltadas en naranja, mientras que el resto de prioridades no presentan alarmas. |

## 💡 Guía de Uso

La pestaña **Overview** del Centro de Alarmas es el panel de control principal para la supervisión del estado de alarmas en tiempo real. Los cuatro **KPIs** de la cabecera (3–6) ofrecen de un vistazo las métricas más críticas: número de alarmas activas, alarmas pendientes de reconocimiento, tiempo medio de respuesta e incidentes abiertos. El **gráfico de tasa de alarmas** (7) permite identificar picos de actividad en las últimas horas, mientras que la sección **Alarmas Prioritarias** (8) lista aquellas que requieren atención inmediata junto con su antigüedad y estado. Por último, el **Mapa de Calor** (12) proporciona una visión rápida de la concentración de alarmas por nivel de prioridad, facilitando la priorización de la respuesta operativa. Activa el modo **En vivo** (2) para mantener todos los datos actualizados automáticamente.
