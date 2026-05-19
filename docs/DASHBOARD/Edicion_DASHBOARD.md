# 🖥️ Editor de dashboards

**Objetivo principal:** Permite al usuario crear, configurar y personalizar dashboards interactivos mediante widgets, filtros y herramientas visuales para supervisión y análisis de datos industriales.

## 📸 Mapeo de interfaz
<img width="1227" height="633" alt="image" src="https://github.com/user-attachments/assets/78eed5f6-dcf7-435f-a351-fb201ac9e7da" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Toggle panel lateral | Toggle | Mostrar/ocultar panel | Permite expandir o contraer el panel lateral de widgets y herramientas. |
| 2 | Toggle navegación lateral | Toggle | Mostrar/ocultar navegación | Permite expandir o contraer la barra lateral principal de navegación de la plataforma. |
| 3 | Navegación y nombre del dashboard | Navegación contextual | Volver a dashboards | Muestra el nombre del dashboard actualmente abierto y permite regresar al listado general de dashboards. |
| 4 | Selector temporal | Filtro | Cambia rango temporal | Permite seleccionar el periodo temporal de visualización de datos. |
| 5 | Filtro de planta | Filtro desplegable | Filtra por planta | Permite seleccionar la planta o instalación sobre la que se mostrarán los datos. |
| 6 | Filtro de zona | Filtro desplegable | Filtra por zona | Permite filtrar los datos según zonas o áreas específicas de la instalación. |
| 7 | Selector de agregación | Filtro desplegable | Cambia agregación | Permite seleccionar el tipo de agregación de datos mostrado en los widgets. |
| 8 | Selector de turno/franja | Filtro desplegable | Filtra por turno | Permite visualizar información según turnos o franjas horarias configuradas. |
| 9 | Botón refrescar datos | CTA Secundario | Actualiza dashboard | Fuerza la actualización manual de los datos y widgets del dashboard. |
| 10 | Configuración de navegación y filtros | CTA Secundario | Configurar barra superior | Permite configurar los elementos visibles de navegación y filtros del dashboard, incluyendo opciones como planta, zona, agregación y otros controles contextuales. |
| 11 | Vista previa del dashboard | CTA Secundario | Abrir vista previa | Permite visualizar el dashboard en modo preview para comprobar su comportamiento y apariencia antes de guardar o publicar cambios. |
| 12 | Botón guardar | CTA Principal | Guarda cambios | Guarda los cambios realizados en el dashboard actual. |
| 13 | Toggle panel lateral derecho | Toggle | Mostrar/ocultar widgets | Permite abrir o cerrar el panel lateral de widgets y propiedades. |
| 14 | Canvas del dashboard | Área de trabajo | Edita dashboard | Espacio principal donde se añaden, organizan y configuran los widgets del dashboard. |
| 15 | Selector de resolución | Selector | Cambia resolución | Permite modificar el formato o resolución de visualización del dashboard. |
| 16 | Zoom del canvas | Herramienta de visualización | Ajusta zoom | Permite ampliar o reducir la escala de visualización del dashboard. |
| 17 | Herramientas de ajuste visual | Toolbar | Ajustes rápidos | Incluye herramientas rápidas relacionadas con visualización y posicionamiento. |
| 18 | Pantalla completa | Herramienta de visualización | Activar fullscreen | Permite expandir el canvas del dashboard a pantalla completa para facilitar la edición y visualización. |
| 19 | Herramienta de bloqueo | Herramienta de edición | Bloquear elementos | Permite bloquear widgets o elementos del dashboard para evitar modificaciones accidentales durante la edición. |
| 20 | Configuración de fondo | Herramienta visual | Cambiar fondo | Permite modificar el fondo visual del dashboard mediante colores, imágenes o configuraciones personalizadas. |
| 21 | Herramientas de alineación | Toolbar | Alinear elementos | Permite organizar y alinear automáticamente los widgets dentro del canvas del dashboard. |
| 22 | Herramienta de reorganización | Toolbar | Reorganizar widgets | Permite reorganizar automáticamente los widgets y componentes visuales dentro del dashboard. |
| 23 | Herramienta de eliminación | Toolbar | Eliminar elementos | Permite eliminar widgets o elementos seleccionados del dashboard. |

## 💡 Guía de uso

El editor de dashboards permite construir paneles visuales personalizados mediante widgets y filtros dinámicos. Desde la barra superior puedes configurar el contexto de visualización, incluyendo planta, zona, agregación temporal y rango horario.

El área central funciona como un canvas interactivo donde se añaden y organizan widgets visuales. Los elementos pueden redimensionarse, alinearse y reorganizarse libremente para adaptar el dashboard a las necesidades operativas.

Las herramientas inferiores permiten controlar el zoom, resolución, fondo y organización visual del panel. El sistema muestra continuamente el estado de guardado para indicar si existen cambios pendientes antes de publicar o abandonar el dashboard.
