# 🖥️ Alarmas – Timeline de Alarmas

**Objetivo Principal:** Permite al usuario visualizar cronológicamente la duración y distribución de las alarmas activas agrupadas por nivel de severidad, dentro de un rango de tiempo configurable.

## 📸 Mapeo de Interfaz

<img width="1276" height="257" alt="image" src="https://github.com/user-attachments/assets/e487545a-30b7-4624-8ba7-66c6847d1d85" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Título "Timeline de Alarmas" | Cabecera informativa | — | — |
| 2 | Selector de rango "Desde – Hasta" | Control de fecha/hora | Define el intervalo temporal del timeline | Ajústalo para enfocar el análisis en el periodo exacto que te interesa revisar. |
| 3 | Accesos rápidos de rango temporal | Botones de acceso rápido | Aplica un rango predefinido al timeline | Úsalos para cambiar rápidamente el horizonte temporal sin tener que introducir fechas manualmente. |
| 4 | Botón "En vivo" | Toggle | Activa/desactiva la actualización en tiempo real | Actívalo para que el timeline se actualice solo y puedas hacer seguimiento en tiempo real sin recargar. |
| 5 | Desplegable "Agrupar por: Severidad" | Filtro / Select | Cambia el criterio de agrupación de las filas del timeline | Cámbialo para reorganizar las filas por Severidad, Categoría o Regla según el criterio que más te ayude a identificar patrones. |
| 6 | Controles de visualización del gráfico | Barra de iconos | Zoom, reset, descarga y otras acciones sobre el gráfico | Úsalos para hacer zoom en un intervalo concreto, restablecer la vista o descargar el gráfico para compartirlo. |
| 7 | Gráfico | Gráfico de línea temporal | — | Observa si alguna barra llega hasta el extremo derecho: si es así, esa alarma sigue activa en este momento. Usa la agrupación para identificar rápidamente dónde se concentra la actividad. |

## 💡 Guía de Uso 

La pestaña **Timeline** te permite analizar visualmente cuándo se han producido las alarmas y durante cuánto tiempo han permanecido activas. Utiliza el **selector de rango** (3) o los **accesos rápidos** (4) para definir el intervalo de tiempo que deseas inspeccionar, y emplea el desplegable **Agrupar por** (7) para reorganizar las filas según el criterio que más te interese. Cada barra coloreada representa la duración activa de una alarma: las que se extienden hasta el extremo derecho del gráfico corresponden a alarmas que siguen activas en este momento. La **leyenda** (8) te indica el nivel de severidad asociado a cada color, y los **controles del gráfico** (9) te permiten hacer zoom para explorar intervalos concretos con mayor detalle. Activa el modo **En vivo** (6) para que el timeline se actualice automáticamente con los datos más recientes.
