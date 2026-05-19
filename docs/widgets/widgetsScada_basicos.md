# 🖥️ Elementos SCADA – Básicos

**Objetivo Principal:** Permite al usuario seleccionar e insertar en el canvas los elementos SCADA básicos de lectura, control y navegación para construir pantallas de supervisión interactivas.

## 📸 Mapeo de Interfaz

<img width="672" height="652" alt="image" src="https://github.com/user-attachments/assets/d2ec1e58-625e-488e-b30f-03958ebe30dc" />

## 🧩 Despiece de Elementos Funcionales

| Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- |
| Sección "Elementos SCADA" (4) | Grupo / Acordeón raíz | Expande/colapsa el bloque principal | Agrupa todas las categorías y elementos de tipo SCADA disponibles. Incluye el aviso "Arrastra al canvas o haz clic para añadir" como instrucción de uso. |
| Subsección "Básicos" (4.1) | Grupo / Acordeón | Expande/colapsa el subbloque | Agrupa los elementos SCADA de uso fundamental. Muestra un contador (6) con el total de subelementos disponibles. |
| Indicador Lectura (4.1.1) | Elemento seleccionable | Inserta un bloque de lectura de variables | Muestra el valor en tiempo real de entre 1 y 10 variables configurables en un único bloque de lectura. |
| Piloto Redondo (4.1.2) | Elemento seleccionable | Inserta un indicador visual tipo piloto | Representa el estado de una variable booleana mediante un indicador circular luminoso de tipo piloto, habitual en paneles de control industriales. |
| Consigna (4.1.3) | Elemento seleccionable | Inserta un widget de escritura de consigna | Permite visualizar y editar el valor de una consigna directamente desde la vista, con soporte de logs de escritura y control de estados de envío. |
| Botón de Navegación (4.1.4) | Elemento seleccionable | Inserta un botón de navegación entre vistas SCADA | Permite al usuario moverse entre diferentes pantallas o vistas SCADA mediante un botón configurable, facilitando la navegación en entornos multi-pantalla. |
| Panel de Estados (4.1.5) | Elemento seleccionable | Inserta un panel de lista de estados | Muestra una lista de estados de tipo booleano o entero con una presentación visual estilo Apple, útil para supervisar el estado de múltiples señales de forma compacta. |
| Slider / Consigna (4.1.6) | Elemento seleccionable | Inserta un control deslizante con lectura en tiempo real | Permite enviar valores numéricos de consigna mediante un slider interactivo, mostrando simultáneamente la lectura actual de la variable en tiempo real. |

## 💡 Guía de Uso (Generada por IA)

La sección **Elementos SCADA – Básicos** reúne los seis componentes fundamentales para construir pantallas de supervisión y control interactivas. Para incorporar cualquier elemento a tu vista, arrástralo directamente al canvas o haz clic sobre él para añadirlo en la posición por defecto. Los elementos de lectura —**Indicador Lectura** (4.1.1) y **Piloto Redondo** (4.1.2)— te permiten monitorizar variables y estados en tiempo real, mientras que **Consigna** (4.1.3) y **Slider / Consigna** (4.1.6) habilitan la escritura y el envío de valores desde la propia pantalla. Completa tu diseño con **Panel de Estados** (4.1.5) para una supervisión compacta de múltiples señales, y utiliza **Botón de Navegación** (4.1.4) para conectar distintas vistas SCADA y ofrecer una experiencia de navegación fluida al operador.
