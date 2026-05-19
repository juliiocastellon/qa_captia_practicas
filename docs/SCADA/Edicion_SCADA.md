# 🖥️ Editor de pantallas SCADA

**Objetivo principal:** Permite al usuario crear, editar y configurar pantallas SCADA de forma visual, incorporando widgets, elementos industriales y propiedades dinámicas para supervisión y control en tiempo real.

## 📸 Mapeo de interfaz
<img width="1226" height="637" alt="image" src="https://github.com/user-attachments/assets/06697305-d4c4-4aab-b000-39fbdcb31d07" />


## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Botón "Nueva escena" | CTA Principal | Crear nueva escena | Permite crear una nueva escena o pantalla SCADA dentro del entorno de edición actual. |
| 2 | Panel de escenas | Navegación lateral | Selecciona escena | Muestra el listado de escenas disponibles dentro del proyecto SCADA. Permite cambiar rápidamente entre pantallas, reorganizar escenas y acceder a opciones rápidas de gestión. |
| 3 | Toggle lateral de escenas | Toggle | Mostrar/ocultar panel | Permite expandir o contraer el panel lateral de escenas para maximizar el área de trabajo. |
| 4 | Navegación de retorno | CTA Secundario | Volver a listado SCADA | Permite regresar a la vista general de pantallas SCADA o al menú anterior. |
| 5 | Selector de modo | Control de estado | Cambia modo edición/ejecución | Permite alternar entre el modo de edición de la pantalla y el modo de ejecución/visualización operativa. |
| 6 | Estado de guardado | Indicador de estado | — | Muestra el estado actual de persistencia de cambios realizados en la escena SCADA. |
| 7 | Estado de conexión realtime | Indicador de estado | — | Indica el estado de conexión en tiempo real con los datos o servicios SCADA asociados a la pantalla. |
| 8 | Herramientas rápidas de edición | Toolbar | Acciones rápidas | Incluye accesos rápidos relacionados con configuración, herramientas de diseño y acciones de edición avanzada. |
| 9 | Botón de vista previa / ejecución | CTA Secundario | Ejecutar vista SCADA | Permite abrir una previsualización operativa de la escena SCADA en ejecución. |
| 10 | Botón "Guardar" | CTA Principal | Guarda cambios | Guarda los cambios realizados en la pantalla SCADA actual. |
| 11 | Área de diseño SCADA | Canvas de edición | Edita escena | Espacio principal de trabajo donde se colocan, organizan y configuran los elementos visuales y widgets SCADA. |
| 12 | Panel lateral de widgets y propiedades | Panel lateral | Configura elementos | Permite añadir widgets, componentes SCADA y modificar propiedades visuales o funcionales de los elementos seleccionados. |

## 💡 Guía de uso

El editor SCADA permite construir y modificar pantallas industriales mediante un entorno visual de edición. Desde el panel lateral de escenas puedes cambiar rápidamente entre pantallas existentes o crear nuevas escenas para diferentes procesos o instalaciones.

El área central de diseño funciona como un canvas interactivo donde puedes añadir widgets, indicadores y componentes industriales. El panel lateral derecho permite incorporar nuevos elementos SCADA y configurar sus propiedades visuales y funcionales.

Antes de publicar cambios, puedes alternar entre modo edición y ejecución para comprobar el comportamiento de la pantalla en tiempo real. El sistema muestra constantemente el estado de guardado y la conexión realtime para asegurar que la información visualizada está sincronizada correctamente.
