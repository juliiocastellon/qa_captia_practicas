# 📊 Series Avanzadas · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Series Avanzadas**, utilizado para representar tendencias y evolución temporal de datos industriales con opciones de personalización visual avanzada de líneas, puntos, leyendas y tipografía dentro de dashboards Analytics.

---

# 📸 Mapeo de Interfaz

<img width="1298" height="721" alt="Captura de pantalla 2026-05-26 123029" src="https://github.com/user-attachments/assets/87581a5e-dd44-4233-88a9-8e66bb452838" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Pestañas de configuración | Navegación interna | Cambia sección de propiedades | Permite alternar entre las distintas categorías de configuración del widget. Para utilizarlo, el usuario debe pulsar "Datos", "Apariencia" o "Texto" según el tipo de configuración que quiera modificar. |
| 1.1 | Campo "Nombre del widget" | Campo de texto | Renombra el widget | Permite definir el nombre identificativo del widget dentro del dashboard. Para utilizarlo, el usuario debe escribir el nombre que quiera mostrar en la cabecera del widget. |
| 1.2 | Sección "Configuración General" | Configuración de datos | Configura variables y agregación | Permite seleccionar las variables que utilizará el gráfico y cómo se procesarán los datos. Para utilizarlo, el usuario debe pulsar "Editar", seleccionar las variables y configurar agregación e intervalo. |
| 1.3 | Sección "Rango de Tiempo" | Configuración temporal | Configura el periodo de datos | Permite definir el rango temporal utilizado por el widget. El usuario puede usar el filtro global, de modo que el widget usará el selector de fechas del dashboard, o configurar un rango propio. |
| 2 | Pestaña "Apariencia" | Configuración visual | Personaliza el gráfico y su contenedor | Permite acceder a todas las configuraciones visuales del widget, incluyendo contenedor, opciones de gráfico, tipografía y grosor de elementos. |
| 2.1 | Sección "Contenedor" | Configuración visual | Ajusta la apariencia del contenedor | Permite seleccionar el estilo de marco (por defecto "Tarjeta"), ocultar el header o el borde, definir el color de fondo (por defecto #FFFFFF) y ajustar la transparencia mediante slider. |
| 2.2 | Sección "Opciones de Gráfico" | Configuración funcional | Ajusta los elementos interactivos del gráfico | Permite activar o desactivar la leyenda del gráfico y configurar su posición (por defecto "Abajo") y alineación (por defecto "Centro"), con opción de mostrarla flotante sobre el gráfico. También permite activar o desactivar la cuadrícula y el tooltip al pasar el cursor (hover). Todos los parámetros están activados por defecto. |
| 2.3 | Sección "Tipografía" | Configuración textual | Ajusta fuentes y estilos de texto | Permite seleccionar la familia tipográfica (por defecto "Sistema (default)") y configurar de forma independiente el estilo del título (tamaño 16, Negrita, color #111827), el subtítulo (tamaño 13, Normal, color #6B7280) y la leyenda (tamaño 12, Normal, color #374151). Para cada elemento el usuario puede ajustar tamaño, peso y color de forma independiente. |
| 2.4 | Sección "Grosor y Tamaño" | Configuración visual | Ajusta el grosor y tamaño de los elementos gráficos | Permite configurar mediante sliders el grosor de línea (por defecto 3.5px), el tamaño de los puntos de datos (por defecto 2.5px) y el borde de los puntos (por defecto 0.5px). Para utilizarlo, el usuario debe mover cada slider hasta conseguir la visualización deseada. |
| 3 | Pestaña "Texto" | Configuración textual | Configura textos adicionales | Permite acceder a configuraciones relacionadas con textos auxiliares mostrados en el widget. |
| 3.1 | Campo "Subtítulo" | Campo de texto | Añade un texto secundario | Permite añadir un subtítulo que se muestra bajo el título principal del widget. Para utilizarlo, el usuario debe escribir el texto deseado en el campo "Texto secundario bajo el título". |
| 3.2 | Campo "Nota al pie" | Campo de texto | Añade una nota informativa | Permite añadir un texto pequeño al final del widget a modo de nota o aclaración. Para utilizarlo, el usuario debe escribir el texto deseado en el campo "Texto pequeño al final del widget". |

---

# 💡 Guía de Uso

El widget **Series Avanzadas** está diseñado para representar la evolución temporal de múltiples variables con un alto nivel de personalización visual, permitiendo ajustar con precisión todos los elementos del gráfico para adaptarse a los estándares visuales del dashboard.

Se utiliza principalmente para:

- Visualizar tendencias temporales de múltiples variables simultáneamente
- Representar series de datos con personalización visual avanzada
- Comparar la evolución de diferentes variables en el mismo eje temporal
- Supervisar cambios continuos con control preciso del grosor y tamaño de elementos
- Mostrar leyendas posicionadas y alineadas según el diseño del dashboard
- Analizar datos históricos con tooltips interactivos
- Monitorizar variables industriales en tiempo real con estilo visual corporativo

## ✅ Cómo configurar correctamente el widget Series Avanzadas

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard.
3. Desde el panel de propiedades:
   - Configura las variables y el método de agregación.
   - Ajusta el rango temporal deseado.
   - Personaliza el contenedor: marco, fondo y transparencia.
   - Configura la leyenda: actívala, define su posición, alineación y si debe mostrarse flotante.
   - Activa o desactiva la cuadrícula y el tooltip según el diseño deseado.
   - Ajusta la tipografía de título, subtítulo y leyenda de forma independiente.
   - Regula el grosor de línea, tamaño de puntos y borde de puntos mediante los sliders.
   - Añade subtítulo y nota al pie si se requiere contexto adicional.
4. Guarda los cambios realizados.


[← Volver a Widgets SCADA Básicos](../../widgetsScada_basicos.md)
