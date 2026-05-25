# 🖥️ Editor de dashboards

**Objetivo principal:** Permite al usuario crear, configurar y personalizar dashboards interactivos mediante widgets, filtros y herramientas visuales para supervisión y análisis de datos industriales.

## 📸 Mapeo de interfaz
<img width="1227" height="633" alt="image" src="https://github.com/user-attachments/assets/78eed5f6-dcf7-435f-a351-fb201ac9e7da" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Toggle panel lateral | Toggle | Mostrar/ocultar panel | Permite al usuario expandir o contraer el panel lateral de widgets y herramientas para disponer de más espacio de trabajo. Para utilizarlo, el usuario debe pulsar el botón de apertura o cierre del panel lateral. |
| 2 | Toggle navegación lateral | Toggle | Mostrar/ocultar navegación | Permite al usuario mostrar u ocultar la barra lateral principal de navegación de la plataforma para mejorar la visualización del dashboard. Para utilizarlo, el usuario debe pulsar el icono correspondiente situado en la interfaz. |
| 3 | Navegación y nombre del dashboard | Navegación contextual | Volver a dashboards | Permite al usuario identificar el dashboard actualmente abierto y regresar al listado general de dashboards. Para volver atrás, el usuario debe pulsar sobre la navegación contextual o botón de retorno. |
| 4 | Selector temporal | Filtro | Cambia rango temporal | Permite al usuario seleccionar el periodo temporal de visualización de los datos mostrados en el dashboard. Para utilizarlo, el usuario debe abrir el selector y elegir el rango deseado, como últimas horas, días o un periodo personalizado. |
| 5 | Filtro de planta | Filtro desplegable | Filtra por planta | Permite al usuario visualizar información únicamente de una planta o instalación concreta. Para utilizarlo, el usuario debe abrir el desplegable y seleccionar la planta deseada. |
| 6 | Filtro de zona | Filtro desplegable | Filtra por zona | Permite al usuario filtrar los datos según una zona o área específica de la instalación. Para utilizarlo, el usuario debe seleccionar la zona correspondiente desde el desplegable. |
| 7 | Selector de agregación | Filtro desplegable | Cambia agregación | Permite al usuario modificar la forma en la que se agrupan los datos mostrados en los widgets, como medias, máximos o mínimos. Para utilizarlo, el usuario debe seleccionar el tipo de agregación deseado desde el desplegable. |
| 8 | Selector de turno/franja | Filtro desplegable | Filtra por turno | Permite al usuario visualizar información correspondiente a turnos o franjas horarias específicas. Para utilizarlo, el usuario debe seleccionar el turno deseado desde el filtro disponible. |
| 9 | Botón refrescar datos | CTA Secundario | Actualiza dashboard | Permite al usuario actualizar manualmente los datos mostrados en el dashboard para cargar la información más reciente. Para utilizarlo, el usuario debe pulsar el botón de refresco. |
| 10 | Configuración de navegación y filtros | CTA Secundario | Configurar barra superior | Permite al usuario personalizar los filtros y elementos visibles en la barra superior del dashboard. Para utilizarlo, el usuario debe abrir la configuración y activar o desactivar los controles deseados. |
| 11 | Vista previa del dashboard | CTA Secundario | Abrir vista previa | Permite al usuario visualizar cómo se comportará el dashboard antes de guardar o publicar los cambios. Para utilizarlo, el usuario debe pulsar el botón de vista previa. |
| 12 | Botón guardar | CTA Principal | Guarda cambios | Permite al usuario almacenar todos los cambios realizados en el dashboard actual. Para utilizarlo, el usuario debe pulsar el botón “Guardar” después de modificar widgets o configuraciones. |
| 13 | Toggle panel lateral derecho | Toggle | Mostrar/ocultar widgets | Permite al usuario abrir o cerrar el panel lateral derecho donde se encuentran widgets y propiedades. Para utilizarlo, el usuario debe pulsar el botón correspondiente del panel lateral. |
| 14 | Canvas del dashboard | Área de trabajo | Edita dashboard | Permite al usuario diseñar y organizar visualmente el dashboard añadiendo [Widgets](../Widgets/widget.md) y configurando variables. Para utilizarlo, el usuario debe arrastrar elementos al canvas y posicionarlos según sus necesidades. |
| 15 | Selector de resolución | Selector | Cambia resolución | Permite al usuario modificar el formato o resolución de visualización del dashboard para adaptarlo a diferentes pantallas o dispositivos. Para utilizarlo, el usuario debe seleccionar una resolución desde el menú disponible. |
| 16 | Zoom del canvas | Herramienta de visualización | Ajusta zoom | Permite al usuario ampliar o reducir la escala visual del dashboard para facilitar la edición de elementos. Para utilizarlo, el usuario debe utilizar los controles de zoom disponibles. |
| 17 | Herramientas de ajuste visual | Toolbar | Ajustes rápidos | Permite al usuario realizar ajustes rápidos relacionados con la visualización y posicionamiento de elementos del dashboard. Para utilizarlo, el usuario debe seleccionar la herramienta deseada desde la barra de herramientas. |
| 18 | Pantalla completa | Herramienta de visualización | Activar fullscreen | Permite al usuario expandir el área de trabajo a pantalla completa para facilitar la edición y visualización del dashboard. Para utilizarlo, el usuario debe pulsar el botón de pantalla completa. |
| 19 | Herramienta de bloqueo | Herramienta de edición | Bloquear elementos | Permite al usuario bloquear widgets o componentes del dashboard para evitar modificaciones accidentales. Para utilizarlo, el usuario debe seleccionar un elemento y activar la opción de bloqueo. |
| 20 | Configuración de fondo | Herramienta visual | Cambiar fondo | Permite al usuario modificar el fondo visual del dashboard utilizando colores, imágenes u otras configuraciones personalizadas. Para utilizarlo, el usuario debe abrir la configuración de fondo y seleccionar el diseño deseado. |
| 21 | Herramientas de alineación | Toolbar | Alinear elementos | Permite al usuario organizar automáticamente los widgets del dashboard alineándolos correctamente dentro del canvas. Para utilizarlo, el usuario debe seleccionar varios elementos y utilizar las opciones de alineación disponibles. |
| 22 | Herramienta de reorganización | Toolbar | Reorganizar widgets | Permite al usuario reorganizar automáticamente los widgets y componentes visuales del dashboard para optimizar la distribución del espacio. Para utilizarlo, el usuario debe pulsar la herramienta de reorganización automática. |
| 23 | Herramienta de eliminación | Toolbar | Eliminar elementos | Permite al usuario eliminar widgets o elementos seleccionados del dashboard. Para utilizarlo, el usuario debe seleccionar el elemento que desea borrar y pulsar la herramienta de eliminación. |

## 💡 Guía de uso

El editor de dashboards permite construir paneles visuales personalizados mediante widgets y filtros dinámicos. Desde la barra superior puedes configurar el contexto de visualización, incluyendo planta, zona, agregación temporal y rango horario.

El área central funciona como un canvas interactivo donde se añaden y organizan widgets visuales. Los elementos pueden redimensionarse, alinearse y reorganizarse libremente para adaptar el dashboard a las necesidades operativas.

Las herramientas inferiores permiten controlar el zoom, resolución, fondo y organización visual del panel. El sistema muestra continuamente el estado de guardado para indicar si existen cambios pendientes antes de publicar o abandonar el dashboard.

[← Anterior](./DASHBOARD.md) • [📚 Índice](../README.md) • [Siguiente →](../Informes/Informes.md)
