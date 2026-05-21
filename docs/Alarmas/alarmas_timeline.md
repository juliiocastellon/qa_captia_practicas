# 🖥️ Alarmas – Timeline de Alarmas

**Objetivo Principal:** Permite al usuario visualizar cronológicamente la duración y distribución de las alarmas activas agrupadas por nivel de severidad, dentro de un rango de tiempo configurable.

## 📸 Mapeo de Interfaz

<img width="1276" height="257" alt="image" src="https://github.com/user-attachments/assets/e487545a-30b7-4624-8ba7-66c6847d1d85" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Título "Timeline de Alarmas" | Cabecera informativa | — | Identifica la vista actual como la línea de tiempo de alarmas del sistema. |
| 2 | Selector de rango "Desde – Hasta" | Control de fecha/hora | Define el intervalo temporal del timeline | Permite al usuario establecer manualmente una fecha y hora de inicio y fin para acotar la visualización de alarmas. Valores actuales: 20/05/2026 12:05 a 20/05/2026 14:05. |
| 3 | Accesos rápidos de rango temporal | Botones de acceso rápido | Aplica un rango predefinido al timeline | Permite seleccionar intervalos de tiempo predefinidos: 1h, 2h, 12h, 24h y 7d, actualizando el timeline de forma inmediata. |
| 4 | Botón "En vivo" | Toggle | Activa/desactiva la actualización en tiempo real | Permite iniciar o pausar el modo de actualización continua del timeline con los datos más recientes. |
| 5 | Desplegable "Agrupar por: Severidad" | Filtro / Select | Cambia el criterio de agrupación de las filas del timeline | Permite reorganizar las barras del timeline agrupándolas por diferentes criterios, siendo "Severidad" el valor activo por defecto. |
| 6 | Controles de visualización del gráfico | Barra de iconos | Zoom, reset, descarga y otras acciones sobre el gráfico | Agrupa las herramientas de interacción con el timeline: zoom in/out, restablecer vista, descargar imagen y anclar la vista actual. |

## 💡 Guía de Uso 

La pestaña **Timeline** te permite analizar visualmente cuándo se han producido las alarmas y durante cuánto tiempo han permanecido activas. Utiliza el **selector de rango** (3) o los **accesos rápidos** (4) para definir el intervalo de tiempo que deseas inspeccionar, y emplea el desplegable **Agrupar por** (7) para reorganizar las filas según el criterio que más te interese. Cada barra coloreada representa la duración activa de una alarma: las que se extienden hasta el extremo derecho del gráfico corresponden a alarmas que siguen activas en este momento. La **leyenda** (8) te indica el nivel de severidad asociado a cada color, y los **controles del gráfico** (9) te permiten hacer zoom para explorar intervalos concretos con mayor detalle. Activa el modo **En vivo** (6) para que el timeline se actualice automáticamente con los datos más recientes.
