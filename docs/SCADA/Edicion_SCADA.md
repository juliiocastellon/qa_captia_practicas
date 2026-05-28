# 🖥️ Editor de pantallas SCADA

**Objetivo principal:** Permite al usuario crear, editar y configurar pantallas SCADA de forma visual, incorporando widgets, elementos industriales y propiedades dinámicas para supervisión y control en tiempo real.

## 📸 Mapeo de interfaz
<img width="1031" height="491" alt="image" src="https://github.com/user-attachments/assets/bca6cade-4d21-4f20-9227-66505cd898c1" />


## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Botón "Nueva escena" | CTA Principal | Crear nueva escena | Permite al usuario crear una nueva escena o pantalla SCADA dentro del proyecto actual. Para utilizarlo, el usuario debe pulsar el botón “Nueva escena”, introducir un nombre y comenzar a diseñar la nueva pantalla. |
| 2 | Panel de escenas | Navegación lateral | Selecciona escena | Permite al usuario visualizar todas las escenas disponibles dentro del proyecto SCADA y cambiar rápidamente entre ellas. Para utilizarlo, el usuario debe hacer clic sobre la escena que desea abrir o editar. |
| 3 | Toggle lateral de escenas | Toggle | Mostrar/ocultar panel | Permite al usuario expandir o ocultar el panel lateral de escenas para disponer de más espacio de trabajo. Para utilizarlo, el usuario debe pulsar el icono de desplegado o cierre del panel. |
| 4 | Navegación de retorno | CTA Secundario | Volver a listado SCADA | Permite al usuario regresar al listado principal de pantallas SCADA o a la vista anterior. Para utilizarlo, el usuario debe pulsar el botón de retorno situado en la parte superior de la interfaz. |
| 5 | Selector de modo | Control de estado | Cambia modo edición/ejecución | Permite al usuario alternar entre el modo edición y el modo ejecución de la pantalla SCADA. Para utilizarlo, el usuario debe seleccionar el modo deseado para editar componentes o visualizar la pantalla en funcionamiento. |
| 6 | Estado de guardado | Indicador de estado | — | Permite al usuario comprobar si los cambios realizados en la escena SCADA han sido guardados correctamente o si existen modificaciones pendientes de guardar. |
| 7 | Estado de conexión realtime | Indicador de estado | — | Permite al usuario comprobar si la pantalla SCADA mantiene conexión en tiempo real con las variables y servicios asociados para visualizar datos actualizados automáticamente. |
| 8 | Asistente IA | Herramienta IA | Abre asistente inteligente | Permite al usuario acceder a herramientas de ayuda basadas en inteligencia artificial para facilitar tareas de configuración, diseño o automatización. Para utilizarlo, el usuario debe pulsar el botón del asistente y escribir la consulta o acción deseada. |
| 9 | Botón de imagen de fondo | CTA Secundario | Configurar fondo de escena | Permite al usuario añadir o modificar la imagen de fondo utilizada en la escena SCADA. Para utilizarlo, el usuario debe pulsar el botón, seleccionar una imagen desde su dispositivo y confirmar la carga. |
| 10 | Botón "Guardar" | CTA Principal | Guarda cambios | Permite al usuario almacenar todos los cambios realizados en la escena SCADA actual. Para utilizarlo, el usuario debe pulsar el botón “Guardar” después de realizar modificaciones en la pantalla. |
| 11 | Área de diseño SCADA | Canvas de edición | Edita escena | Permite al usuario diseñar y organizar visualmente la pantalla SCADA añadiendo [Widgets](../Widgets/widget.md), componentes y variables. Para utilizarla, el usuario debe arrastrar elementos al canvas y configurarlos según sus necesidades. |
| 12 | Toggle panel de widgets | Toggle | Mostrar/ocultar panel lateral | Permite al usuario mostrar u ocultar el panel lateral de widgets y propiedades para aumentar el espacio de edición disponible. Para utilizarlo, el usuario debe pulsar el botón de apertura o cierre del panel lateral. |

## 💡 Guía de uso

El editor SCADA permite construir y modificar pantallas industriales mediante un entorno visual de edición. Desde el panel lateral de escenas puedes cambiar rápidamente entre pantallas existentes o crear nuevas escenas para diferentes procesos o instalaciones.

El área central de diseño funciona como un canvas interactivo donde puedes añadir widgets, indicadores y componentes industriales. El panel lateral derecho permite incorporar nuevos elementos SCADA y configurar sus propiedades visuales y funcionales.

Antes de publicar cambios, puedes alternar entre modo edición y ejecución para comprobar el comportamiento de la pantalla en tiempo real. El sistema muestra constantemente el estado de guardado y la conexión realtime para asegurar que la información visualizada está sincronizada correctamente.

[← Anterior](./SCADA.md) • [📚 Índice](../README.md) • [Siguiente →](../DASHBOARD/DASHBOARD.md)
