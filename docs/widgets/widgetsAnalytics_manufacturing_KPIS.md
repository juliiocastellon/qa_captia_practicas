# 🖥️ Manufacturing KPIs

**Objetivo Principal:** Permite al usuario seleccionar e insertar indicadores de rendimiento industrial específicos de fabricación para monitorizar la eficiencia, calidad y estado operativo de sus máquinas y líneas de producción.

## 📸 Mapeo de Interfaz

<img width="512" height="722" alt="image" src="https://github.com/user-attachments/assets/e56a2359-111d-4892-b5e1-276fafba8545" />

## 🧩 Despiece de Elementos Funcionales

| Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- |
| Sección "Manufacturing KPIs" (3.4) | Grupo / Acordeón | Expande/colapsa el bloque | Agrupa todos los indicadores de fabricación disponibles. Muestra un contador (12) con el total de subelementos. |
| OEE (3.4.1) | Elemento seleccionable | Inserta indicador OEE | Muestra la Efectividad Global del Equipo, métrica compuesta que combina disponibilidad, rendimiento y calidad. |
| Disponibilidad (3.4.2) | Elemento seleccionable | Inserta indicador de Availability (A) | Refleja el porcentaje de tiempo en que el equipo está operativo respecto al tiempo planificado de producción. |
| Rendimiento (3.4.3) | Elemento seleccionable | Inserta indicador de Performance (P) | Mide la velocidad real de producción frente a la velocidad máxima teórica del equipo. |
| Calidad (3.4.4) | Elemento seleccionable | Inserta indicador de Quality (Q) | Indica la proporción de unidades producidas correctamente frente al total de unidades fabricadas. |
| Unidades Buenas (3.4.5) | Elemento seleccionable | Inserta contador de Good Units | Muestra el recuento acumulado de unidades conformes producidas en un periodo determinado. |
| Tasa de Scrap (3.4.6) | Elemento seleccionable | Inserta indicador de Scrap Rate (%) | Representa el porcentaje de unidades rechazadas o defectuosas sobre el total producido. |
| Tiempo de Paro (3.4.7) | Elemento seleccionable | Inserta indicador de Downtime (minutos) | Registra el tiempo total en minutos durante el cual el equipo ha permanecido detenido o inoperativo. |
| Energía (3.4.8) | Elemento seleccionable | Inserta indicador de Energy (kWh) | Muestra el consumo energético del equipo o línea de producción expresado en kilovatios-hora. |
| Throughput (3.4.9) | Elemento seleccionable | Inserta indicador de unidades por hora | Refleja la cadencia de producción real, expresada como número de unidades fabricadas por hora. |
| OEE Trend (3.4.10) | Elemento seleccionable | Inserta gráfico de serie temporal de OEE | Visualiza la evolución histórica de los componentes del OEE a lo largo del tiempo mediante una gráfica de tendencia. |
| Timeline Estados (3.4.11) | Elemento seleccionable | Inserta timeline de estados de máquina (multi-asset) | Representa cronológicamente los distintos estados operativos (producción, paro, mantenimiento, etc.) de una o varias máquinas simultáneamente. |
| Ranking Máquinas (3.4.12) | Elemento seleccionable | Inserta tabla de ranking por KPIs | Muestra una clasificación comparativa de máquinas o líneas ordenadas según sus valores de KPIs seleccionados. |

## 💡 Guía de Uso (Generada por IA)

La sección **Manufacturing KPIs** agrupa los 12 indicadores industriales esenciales para el seguimiento del rendimiento de tus equipos y líneas de producción. Puedes comenzar con los indicadores fundamentales del OEE —**OEE** (3.4.1), **Disponibilidad** (3.4.2), **Rendimiento** (3.4.3) y **Calidad** (3.4.4)— para obtener una visión global de la eficiencia operativa, y complementarlos con métricas específicas como **Tasa de Scrap** (3.4.6), **Tiempo de Paro** (3.4.7) o **Energía** (3.4.8) según las necesidades de tu análisis. Para una visión más analítica y comparativa, dispones de **OEE Trend** (3.4.10) para identificar patrones temporales, **Timeline Estados** (3.4.11) para auditar el historial de estados de máquina en múltiples activos, y **Ranking Máquinas** (3.4.12) para comparar el desempeño entre equipos de un vistazo.
