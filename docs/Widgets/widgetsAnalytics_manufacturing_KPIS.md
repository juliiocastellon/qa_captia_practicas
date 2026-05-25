# 🖥️ Manufacturing KPIs

**Objetivo Principal:** Permite al usuario seleccionar e insertar indicadores de rendimiento industrial específicos de fabricación para monitorizar la eficiencia, calidad y estado operativo de sus máquinas y líneas de producción.

## 📸 Mapeo de Interfaz

<img width="512" height="722" alt="image" src="https://github.com/user-attachments/assets/e56a2359-111d-4892-b5e1-276fafba8545" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 3.4 | Sección "Manufacturing KPIs" | Grupo / Acordeón | Expande/colapsa el bloque |  [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Despliega el bloque para acceder a los indicadores industriales específicos de fabricación disponibles. |
| 3.4.1 | OEE | Elemento seleccionable | Inserta indicador OEE  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites tener en un solo elemento la visión global de la eficiencia del equipo. Configura en Propiedades el activo y el periodo de cálculo. |
| 3.4.2 | Disponibilidad | Elemento seleccionable | Inserta indicador de Availability (A)  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando quieras monitorizar qué porcentaje del tiempo planificado el equipo ha estado realmente operativo. Configura en Propiedades el activo y el turno o periodo a analizar. |
| 3.4.3 | Rendimiento | Elemento seleccionable | Inserta indicador de Performance (P)  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) |  Arrástralo al canvas o haz clic para insertarlo cuando necesites detectar si el equipo está produciendo a la velocidad que debería o si hay pérdidas de cadencia. Configura en Propiedades el activo y la velocidad teórica de referencia. |
| 3.4.4 | Calidad | Elemento seleccionable | Inserta indicador de Quality (Q)  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando quieras identificar qué proporción de lo producido cumple los estándares de calidad requeridos. Configura en Propiedades el activo y los criterios de conformidad. |
| 3.4.5 | Unidades Buenas | Elemento seleccionable | Inserta contador de Good Units  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites llevar un recuento acumulado de las unidades conformes producidas en un periodo. Configura en Propiedades el activo y el intervalo de acumulación. |
| 3.4.6 | Tasa de Scrap | Elemento seleccionable | Inserta indicador de Scrap Rate (%)  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando quieras vigilar el porcentaje de material rechazado y detectar desviaciones en el proceso productivo. Configura en Propiedades el activo y el umbral de alerta. |
| 3.4.7 | Tiempo de Paro | Elemento seleccionable | Inserta indicador de Downtime (minutos)  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites cuantificar el tiempo perdido por paradas y evaluar su impacto en la producción. Configura en Propiedades el activo y el tipo de parada a contabilizar. |
| 3.4.8 | Energía | Elemento seleccionable | Inserta indicador de Energy (kWh)  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando quieras hacer seguimiento del consumo energético del equipo e identificar desviaciones o ineficiencias. Configura en Propiedades el activo y el periodo de medición. |
| 3.4.9 | Throughput | Elemento seleccionable | Inserta indicador de unidades por hora  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites verificar que la cadencia real de producción se corresponde con la planificada. Configura en Propiedades el activo y el intervalo de cálculo. |
| 3.4.10 | OEE Trend | Elemento seleccionable | Inserta gráfico de serie temporal de OEE |  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) Arrástralo al canvas o haz clic para insertarlo cuando quieras analizar cómo ha evolucionado el OEE a lo largo del tiempo e identificar tendencias o puntos de mejora. Configura en Propiedades el activo y el rango histórico a visualizar. |
| 3.4.11 | Timeline Estados | Elemento seleccionable | Inserta timeline de estados de máquina (multi-asset)  | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites visualizar cronológicamente en qué momentos cada máquina ha estado produciendo, parada o en mantenimiento. Configura en Propiedades los activos y los estados a representar. |
| 3.4.12 | Ranking Máquinas | Elemento seleccionable | Inserta tabla de ranking por KPIs | [Configuración](./Configuracion/Manufacturing_KPIs/Manufacturing_KPIs.md) | Arrástralo al canvas o haz clic para insertarlo cuando quieras comparar el rendimiento entre equipos o líneas y priorizar las acciones de mejora donde más impacto tienen. Configura en Propiedades los activos, el KPI de ordenación y el periodo de análisis. |

## 💡 Guía de Uso 

La sección **Manufacturing KPIs** agrupa los 12 indicadores industriales esenciales para el seguimiento del rendimiento de tus equipos y líneas de producción. Puedes comenzar con los indicadores fundamentales del OEE —**OEE** (3.4.1), **Disponibilidad** (3.4.2), **Rendimiento** (3.4.3) y **Calidad** (3.4.4)— para obtener una visión global de la eficiencia operativa, y complementarlos con métricas específicas como **Tasa de Scrap** (3.4.6), **Tiempo de Paro** (3.4.7) o **Energía** (3.4.8) según las necesidades de tu análisis. Para una visión más analítica y comparativa, dispones de **OEE Trend** (3.4.10) para identificar patrones temporales, **Timeline Estados** (3.4.11) para auditar el historial de estados de máquina en múltiples activos, y **Ranking Máquinas** (3.4.12) para comparar el desempeño entre equipos de un vistazo.

[← Volver a Widgets](./widget.md)

[← Anterior](./widgetsAnalytics_indicadores.md) • [📚 Índice](../README.md) • [Siguiente →](./widgetsAnalytics_maintenance_KPIS.md)
