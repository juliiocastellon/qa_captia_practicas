# 🖥️ Editor de automatizaciones

**Objetivo principal:** Permite al usuario crear, editar y supervisar workflows automáticos mediante nodos visuales, conexiones lógicas y reglas industriales para automatizar procesos y acciones dentro de la plataforma.

## 📸 Mapeo de interfaz
<img width="1227" height="582" alt="image" src="https://github.com/user-attachments/assets/1b3281b7-a537-4e67-b665-80759a692694" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional | 
| :--- | :--- | :--- | :--- | :--- | 
| 1 | Panel "Triggers" | Panel informativo | Configura disparadores | Permite al usuario visualizar y configurar los triggers o eventos que iniciarán automáticamente el workflow. Para utilizarlo, el usuario debe acceder al panel y seleccionar o configurar el evento que activará la automatización. |
| 2 | Panel "Estadísticas" | Panel informativo | Ver estadísticas | Permite al usuario consultar métricas relacionadas con la ejecución del workflow, como ejecuciones realizadas, errores o tiempos de respuesta. Para utilizarlo, el usuario debe abrir el panel de estadísticas y revisar la información mostrada. | 
| 3 | Panel "Información" | Panel informativo | Ver información | Permite al usuario visualizar información general y parámetros básicos del workflow seleccionado. Para utilizarlo, el usuario debe acceder al panel y consultar los datos disponibles sobre la automatización. |
| 4 | Gestión de pestañas de workflows | Navegación por pestañas | Cambiar workflow | Permite al usuario alternar entre diferentes workflows abiertos simultáneamente y crear nuevas pestañas de edición. Para utilizarlo, el usuario debe pulsar sobre la pestaña del workflow que desea visualizar o editar. |
| 5 | Cabecera del workflow | Navegación contextual | Identifica workflow | Permite al usuario identificar rápidamente el workflow actualmente abierto mostrando su nombre, tipo y estado. |
| 6 | Controles de deshacer y rehacer | Herramienta de edición | Deshacer/Rehacer acciones | Permite al usuario revertir o restaurar cambios realizados durante la edición del workflow. Para utilizarlo, el usuario debe pulsar los botones de deshacer o rehacer según la acción que quiera recuperar o revertir. |
| 7 | Herramienta de copiar selección | Herramienta de edición | Copiar nodos | Permite al usuario copiar nodos o elementos seleccionados dentro del workflow. Para utilizarlo, el usuario debe seleccionar uno o varios nodos y pulsar la herramienta de copiar. |
| 8 | Herramienta de pegar | Herramienta de edición | Pegar nodos | Permite al usuario pegar dentro del canvas nodos previamente copiados. Para utilizarlo, el usuario debe pulsar la herramienta de pegar en la zona donde desea colocar los elementos copiados. |
| 9 | Botón guardar workflow | CTA Principal | Guarda cambios | Permite al usuario guardar todos los cambios realizados en el workflow actual. Para utilizarlo, el usuario debe pulsar el botón “Guardar” después de modificar nodos, conexiones o configuraciones. |
| 10 | Botón de logs de ejecución | CTA Secundario | Ver logs | Permite al usuario acceder al historial y registros de ejecución del workflow para supervisar errores, estados y comportamiento de la automatización. Para utilizarlo, el usuario debe pulsar el botón de logs. |
| 11 | Atajos de teclado | Panel contextual | Ver atajos | Permite al usuario consultar los atajos de teclado disponibles para agilizar la edición y navegación dentro del editor de workflows. Para utilizarlo, el usuario debe abrir el panel de atajos y revisar las combinaciones disponibles. |
| 12 | Categoría "Nodos del workflow" | Categoría de biblioteca | Mostrar nodos | Permite al usuario visualizar los nodos estándar disponibles para construir automatizaciones dentro del canvas. Para utilizarlo, el usuario debe abrir la categoría y arrastrar los nodos deseados al área de trabajo. |
| 13 | Categoría "Catálogo UDT" | Categoría de biblioteca | Mostrar catálogo UDT | Permite al usuario acceder a nodos y elementos basados en definiciones UDT para automatizaciones avanzadas. Para utilizarlo, el usuario debe abrir la categoría y seleccionar los elementos que desea utilizar en el workflow. |
| 14 | Categorías de nodos | Listado de categorías | Filtrar nodos | Permite al usuario organizar y localizar nodos según categorías funcionales como triggers, acciones, variables o monitorización. Para utilizarlo, el usuario debe seleccionar la categoría correspondiente para visualizar los nodos relacionados. [NODOS](./Nodos/nodos.md)
 |
| 15 | Canvas del workflow | Área de trabajo | Edita automatización | Permite al usuario crear y organizar visualmente automatizaciones conectando nodos dentro del workflow. Para utilizarlo, el usuario debe arrastrar nodos al canvas y conectarlos entre sí según la lógica deseada. |
## 💡 Guía de uso

El editor de automatizaciones permite construir workflows visuales mediante nodos conectados entre sí. Desde el canvas principal puedes diseñar lógicas automáticas arrastrando componentes desde la biblioteca lateral y conectándolos según el flujo deseado.

Los paneles laterales permiten consultar información, estadísticas y triggers asociados al workflow. Además, la biblioteca de nodos organiza los distintos componentes disponibles por categorías para facilitar la construcción de automatizaciones complejas.

Durante la edición, el sistema permite guardar cambios, duplicar workflows, deshacer acciones y ejecutar automatizaciones para validar su comportamiento antes de ponerlas en producción.

[← Anterior](./Automatizaciones.md) • [📚 Índice](../README.md) • [Siguiente →](../Tareas/Tareas.md)
