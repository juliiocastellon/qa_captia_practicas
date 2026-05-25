# 🖥️ Elementos SCADA – Básicos

**Objetivo Principal:** Permite al usuario seleccionar e insertar en el canvas los elementos SCADA básicos de lectura, control y navegación para construir pantallas de supervisión interactivas.

## 📸 Mapeo de Interfaz

<img width="672" height="652" alt="image" src="https://github.com/user-attachments/assets/d2ec1e58-625e-488e-b30f-03958ebe30dc" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Configuración | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 4 | Sección "Elementos SCADA" | Grupo / Acordeón raíz | Expande/colapsa el bloque principal | — | Despliega el bloque para acceder a todos los elementos SCADA disponibles; arrástralos al canvas o haz clic sobre ellos para añadirlos a tu vista. |
| 4.1 | Subsección "Básicos" | Grupo / Acordeón | Expande/colapsa el subbloque | — | Despliega el subbloque para acceder a los 6 elementos SCADA de uso más habitual en pantallas de supervisión y control. |
| 4.1.1 | Indicador Lectura | Elemento seleccionable | Inserta un bloque de lectura de variables | [Configuración](./Configuracion/IndicadorLectura_config.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites mostrar en tiempo real el valor de varias variables en un mismo bloque sin crear un elemento por cada una. Configura en Propiedades las variables a mostrar, entre 1 y 10. |
| 4.1.2 | Piloto Redondo | Elemento seleccionable | Inserta un indicador visual tipo piloto | [Configuración](./Configuracion/PilotoRedondo.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites indicar de forma inmediata si un equipo o señal está activo o inactivo. Configura en Propiedades la variable booleana y los colores de cada estado. |
| 4.1.3 | Consigna | Elemento seleccionable | Inserta un widget de escritura de consigna | [Configuración](./Configuracion/Consigna.md) | Arrástralo al canvas o haz clic para insertarlo cuando el operador necesite no solo ver el valor de una variable sino también modificarlo directamente desde la pantalla. Configura en Propiedades la variable de escritura y los permisos de edición. |
| 4.1.4 | Botón de Navegación | Elemento seleccionable | Inserta un botón de navegación entre vistas SCADA | [Configuración](./Configuracion/Boton_navegacion.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites conectar distintas pantallas SCADA y permitir al operador navegar entre ellas sin salir del entorno de supervisión. Configura en Propiedades la vista de destino y la etiqueta del botón. |
| 4.1.5 | Panel de Estados | Elemento seleccionable | Inserta un panel de lista de estados | [Configuración](./Configuracion/Panel_Estados.md) | Arrástralo al canvas o haz clic para insertarlo cuando necesites supervisar de forma compacta el estado de varias señales booleanas o enteras a la vez. Configura en Propiedades las variables y las etiquetas de cada estado. |
| 4.1.6 | Slider / Consigna | Elemento seleccionable | Inserta un control deslizante con lectura en tiempo real | [Configuración](./Configuracion/Slider.md) | Arrástralo al canvas o haz clic para insertarlo cuando el operador necesite ajustar un valor numérico de forma continua y ver simultáneamente cómo responde la variable en tiempo real. Configura en Propiedades el rango del slider y la variable de escritura. |

## 💡 Guía de Uso 

La sección **Elementos SCADA – Básicos** reúne los seis componentes fundamentales para construir pantallas de supervisión y control interactivas. Para incorporar cualquier elemento a tu vista, arrástralo directamente al canvas o haz clic sobre él para añadirlo en la posición por defecto. Los elementos de lectura —**Indicador Lectura** (4.1.1) y **Piloto Redondo** (4.1.2)— te permiten monitorizar variables y estados en tiempo real, mientras que **Consigna** (4.1.3) y **Slider / Consigna** (4.1.6) habilitan la escritura y el envío de valores desde la propia pantalla. Completa tu diseño con **Panel de Estados** (4.1.5) para una supervisión compacta de múltiples señales, y utiliza **Botón de Navegación** (4.1.4) para conectar distintas vistas SCADA y ofrecer una experiencia de navegación fluida al operador.

[← Volver a Widgets](./widget.md)

[← Anterior](widgetsAnalytics_avanzados.md) • [📚 Índice](../README.md) • [Siguiente →](widgetsScada_alarmas.md)
