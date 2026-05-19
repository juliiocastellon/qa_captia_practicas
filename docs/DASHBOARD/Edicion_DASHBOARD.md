# 🖥️ Editor de dashboards

**Objetivo principal:** Permite al usuario crear, configurar y personalizar dashboards interactivos mediante widgets, filtros y herramientas visuales para supervisión y análisis de datos industriales.

## 📸 Mapeo de interfaz
<img width="1228" height="552" alt="image" src="https://github.com/user-attachments/assets/e4e8de41-b228-44db-8580-a683074bb8e1" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Toggle panel lateral | Toggle | Mostrar/ocultar panel | Permite expandir o contraer el panel lateral de widgets y herramientas. |
| 2 | Navegación de retorno | CTA Secundario | Volver a dashboards | Permite regresar al listado general de dashboards. |
| 3 | Nombre del dashboard | Información editable | Renombrar dashboard | Muestra el nombre actual del dashboard y permite identificar el panel abierto. |
| 4 | Selector temporal | Filtro | Cambia rango temporal | Permite seleccionar el periodo temporal de visualización de datos. |
| 5 | Filtro de planta | Filtro desplegable | Filtra por planta | Permite seleccionar la planta o instalación sobre la que se mostrarán los datos. |
| 6 | Filtro de zona | Filtro desplegable | Filtra por zona | Permite filtrar los datos según zonas o áreas específicas de la instalación. |
| 7 | Selector de agregación | Filtro desplegable | Cambia agregación | Permite seleccionar el tipo de agregación de datos mostrado en los widgets. |
| 8 | Selector de turno/franja | Filtro desplegable | Filtra por turno | Permite visualizar información según turnos o franjas horarias configuradas. |
| 9 | Botón refrescar datos | CTA Secundario | Actualiza dashboard | Fuerza la actualización manual de los datos y widgets del dashboard. |
| 10 | Configuración del dashboard | CTA Secundario | Abre configuración | Permite acceder a parámetros generales y opciones avanzadas del dashboard. |
| 11 | Estado de guardado | Indicador de estado | — | Muestra si existen cambios pendientes de guardar en el dashboard actual. |
| 12 | Botón guardar | CTA Principal | Guarda cambios | Guarda los cambios realizados en el dashboard actual. |
| 13 | Toggle panel lateral derecho | Toggle | Mostrar/ocultar widgets | Permite abrir o cerrar el panel lateral de widgets y propiedades. |
| 14 | Canvas del dashboard | Área de trabajo | Edita dashboard | Espacio principal donde se añaden, organizan y configuran los widgets del dashboard. |
| 15 | Selector de resolución | Selector | Cambia resolución | Permite modificar el formato o resolución de visualización del dashboard. |
| 16 | Zoom del canvas | Herramienta de visualización | Ajusta zoom | Permite ampliar o reducir la escala de visualización del dashboard. |
| 17 | Herramientas de ajuste visual | Toolbar | Ajustes rápidos | Incluye herramientas rápidas relacionadas con visualización y posicionamiento. |
| 18 | Herramientas de interacción | Toolbar | Acciones rápidas | Permite activar acciones de interacción sobre widgets y elementos del canvas. |
| 19 | Configuración de fondo | Herramienta visual | Cambia fondo | Permite modificar el fondo visual del dashboard. |
| 20 | Herramientas de alineación | Toolbar | Alinear elementos | Permite organizar y alinear widgets dentro del área de trabajo. |
| 21 | Herramientas de organización | Toolbar | Reorganizar widgets | Permite reorganizar automáticamente los widgets del dashboard. |
| 22 | Herramientas de eliminación | Toolbar | Eliminar elementos | Permite eliminar widgets o elementos seleccionados del dashboard. |
| 23 | Controles de redimensionamiento | Control visual | Ajusta tamaño | Permite modificar manualmente el tamaño de widgets y elementos visuales dentro del dashboard. |

## 💡 Guía de uso

El editor de dashboards permite construir paneles visuales personalizados mediante widgets y filtros dinámicos. Desde la barra superior puedes configurar el contexto de visualización, incluyendo planta, zona, agregación temporal y rango horario.

El área central funciona como un canvas interactivo donde se añaden y organizan widgets visuales. Los elementos pueden redimensionarse, alinearse y reorganizarse libremente para adaptar el dashboard a las necesidades operativas.

Las herramientas inferiores permiten controlar el zoom, resolución, fondo y organización visual del panel. El sistema muestra continuamente el estado de guardado para indicar si existen cambios pendientes antes de publicar o abandonar el dashboard.
