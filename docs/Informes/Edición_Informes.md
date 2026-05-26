# 🖥️ Informes – Vista de Edición / Previsualización de Plantilla

**Objetivo Principal:** Permite al usuario visualizar, configurar y ajustar el contenido de una plantilla de informe, aplicando filtros de contexto, navegando entre páginas y controlando la presentación del documento.

## 📸 Mapeo de Interfaz

<img width="1161" height="543" alt="Captura de pantalla 2026-05-20 123934" src="https://github.com/user-attachments/assets/cacdb38d-a673-4869-a133-bee43259356e" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Desplegable de páginas | Panel / Desplegable | Despliega el listado de páginas disponibles en la plantilla | Permite navegar directamente a cualquier página del informe seleccionándola desde el panel lateral. |
| 2 | Toggle panel superior | Botón / Toggle | Muestra u oculta la barra de herramientas superior | Permite maximizar el área de visualización del canvas ocultando los controles de la cabecera. |
| 3 | Botón volver | Navegación | Regresa al listado de plantillas de Informes | Cancela la edición o previsualización actual y devuelve al usuario a la pantalla principal de Informes. |
| 4 | Nombre de plantilla "Informe Energía 7d" | Etiqueta informativa | — | Muestra el nombre de la plantilla activa que se está visualizando o editando. |
| 5 | Selector de formato de página "A4" | Desplegable | Cambia el formato del papel del informe | Permite seleccionar el tamaño de página del documento (A4, A3, carta, etc.). |
| 6 | Selector de orientación "Vertical" | Desplegable | Cambia la orientación de la página | Permite alternar entre orientación vertical (portrait) y horizontal (landscape) para el informe. |
| 7 | Selector de intervalo temporal "1m" | Desplegable | Define el rango de tiempo de los datos mostrados | Filtra los datos del informe según el intervalo temporal seleccionado (1 minuto, 1 hora, 1 día, etc.). |
| 8 | Filtro "Planta" | Desplegable | Filtra los datos por planta | Permite acotar los datos del informe a una planta o instalación específica. |
| 9 | Filtro "Zona" | Desplegable | Filtra los datos por zona | Permite acotar los datos del informe a una zona concreta dentro de la planta seleccionada. |
| 10 | Filtro "Máq." (Máquina) | Desplegable | Filtra los datos por máquina | Permite acotar los datos del informe a una máquina o activo específico. |
| 11 | Filtro "Todos" | Desplegable | Filtra los datos por estado o agrupación global | Permite aplicar un filtro adicional de alcance global sobre el conjunto de datos del informe. |
| 12 | Botón recargar | Acción | Recarga los datos del informe con los filtros activos | Fuerza una actualización de los datos mostrados aplicando la configuración de filtros actual. |
| 13 | Botón previsualizar | Acción | Abre la vista previa del informe | Muestra el informe en modo lectura, tal y como lo verá el destinatario final. |
| 14 | Botón exportar PDF | Acción | Exporta el informe en formato PDF | Genera y descarga el informe actual como archivo PDF con los datos y filtros aplicados. |
| 15 | Botón guardar | Acción | Guarda los cambios realizados en la plantilla | Persiste la configuración actual de la plantilla, incluyendo filtros, formato y disposición de elementos. |
| 16 | Toggle panel de widgets | Panel / Desplegable | Despliega el panel lateral de widgets disponibles | Muestra el panel desde el que se pueden añadir o gestionar los elementos visuales (widgets) del informe. |
| 17 | Botón zoom reducir | Control de zoom | Reduce el nivel de zoom del canvas | Aleja la vista del canvas para obtener una perspectiva más amplia del informe. |
| 18 | Botón resetear zoom | Control de zoom | Restablece el zoom al 100% | Devuelve el nivel de zoom a su valor por defecto (100%), mostrando el informe a escala real. |
| 19 | Botón zoom ampliar | Control de zoom | Aumenta el nivel de zoom del canvas | Acerca la vista del canvas para inspeccionar con mayor detalle el contenido del informe. |

## 💡 Guía de Uso 

En la vista de edición de **Informes** puedes configurar y revisar el contenido de tu plantilla de forma completa. Utiliza los filtros de la barra superior —**Planta** (8), **Zona** (9), **Máq.** (10) e intervalo temporal (7)— para contextualizar los datos que se mostrarán en el informe, y pulsa el botón de **recarga** (12) para aplicar los cambios. Si necesitas añadir o reorganizar elementos visuales, despliega el **panel de widgets** (16); para navegar entre las diferentes páginas del documento, usa el **desplegable de páginas** (1). Una vez satisfecho con el resultado, puedes **previsualizar** (13) el informe tal como lo verá el destinatario, **exportarlo a PDF** (14) o **guardar** (15) los cambios en la plantilla. Controla el nivel de detalle del canvas con los botones de zoom (17–19), pudiendo restablecer la vista al 100% en cualquier momento con el botón de reset (18).


[← Anterior](../Informes/Informes.md) • [📚 Índice](../README.md) • [Siguiente →](../Widgets/widget.md)
