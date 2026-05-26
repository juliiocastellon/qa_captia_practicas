# 📊 Tabla por Asset · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Tabla por Asset**, utilizado para representar datos de variables en formato tabular donde cada fila corresponde a un asset, permitiendo comparar múltiples activos industriales en un mismo rango temporal dentro de dashboards Analytics.

---

# 📸 Mapeo de Interfaz

<img width="1114" height="595" alt="Captura de pantalla 2026-05-26 110441" src="https://github.com/user-attachments/assets/a6defdb1-6f3b-4e97-b413-bf20df234197" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Pestañas de configuración | Navegación interna | Cambia sección de propiedades | Permite alternar entre las distintas categorías de configuración del widget. Para utilizarlo, el usuario debe pulsar "Datos", "Apariencia" o "Texto" según el tipo de configuración que quiera modificar. |
| 1.1 | Campo "Nombre del widget" | Campo de texto | Renombra el widget | Permite definir el nombre identificativo del widget dentro del dashboard. Para utilizarlo, el usuario debe escribir el nombre que quiera mostrar en la cabecera del widget. |
| 1.2 | Sección "Configuración General" | Configuración de datos | Configura variables y agregación | Permite seleccionar las variables que utilizará la tabla y cómo se procesarán los datos. Para utilizarlo, el usuario debe pulsar "Editar", seleccionar las variables y configurar agregación e intervalo. |
| 1.3 | Sección "Rango de Tiempo" | Configuración temporal | Configura el periodo de datos | Permite definir el rango temporal utilizado por el widget. El usuario puede usar el filtro global, de modo que el widget usará el selector de fechas del dashboard, o configurar un rango propio. |
| 1.4 | Sección "Estilos de Encabezados" | Configuración visual | Personaliza el estilo de los encabezados | Permite configurar el tamaño de fuente en píxeles (por defecto 11), el peso de fuente (por defecto "Negrita"), el color del texto y el color de fondo de los encabezados de la tabla. Para utilizarlo, el usuario debe ajustar los valores y selectores de color según el diseño deseado. |
| 1.5 | Sección "Estilos de Celdas" | Configuración visual | Personaliza el estilo de las celdas | Permite configurar el tamaño de fuente en píxeles (por defecto 13), el peso de fuente (por defecto "Normal"), el color del texto, el color de fondo de las celdas y el color de banda de título. El color de banda de título permite diferenciar visualmente la fila de identificación del asset. Para utilizarlo, el usuario debe ajustar los valores y selectores de color según el diseño deseado. |
| 1.6 | Sección "Configuración Tabla por Asset" | Configuración estructural | Define decimales y assets de la tabla | Permite configurar el número de decimales mostrados (por defecto 1) y gestionar los assets que se mostrarán en la tabla. Cada fila de la tabla corresponde a un asset. El campo "Asset IDs" muestra el número de assets seleccionados e indica que el usuario puede seleccionar la lista o añadir assets manualmente. |
| 1.7 | Selector de Assets | Selector múltiple con búsqueda | Selecciona los assets a mostrar | Permite buscar y seleccionar los assets que se representarán como filas en la tabla. Incluye la opción "Seleccionar todos" para añadir todos los assets disponibles de una vez (muestra el total disponible entre paréntesis), una lista de assets con casillas de verificación individuales (ej. AULA01, AULA02…) y el campo "Añadir asset manual…" para incorporar assets mediante introducción manual de su identificador. |
| 2 | Pestaña "Apariencia" | Configuración visual | Personaliza el contenedor del widget | Permite acceder a todas las configuraciones visuales del contenedor del widget. |
| 2.1 | Sección "Contenedor" — Estilo de marco | Lista desplegable | Ajusta el estilo del contenedor | Permite seleccionar el estilo visual del marco del widget, como "Tarjeta". Para utilizarlo, el usuario debe seleccionar la opción deseada en el desplegable. |
| 2.2 | Opciones "Ocultar header" y "Ocultar borde" | Casillas de verificación | Controla la visibilidad de elementos | Permite ocultar la cabecera del widget y/o su borde exterior. Para utilizarlo, el usuario debe activar o desactivar cada casilla según el diseño deseado. |
| 2.3 | Selector "Fondo" | Selector de color | Define el color de fondo | Permite elegir el color de fondo del contenedor del widget. Por defecto es #FFFFFF. Para utilizarlo, el usuario debe pulsar el selector de color y elegir el color deseado. |
| 2.4 | Slider "Transparencia" | Slider | Ajusta la opacidad del widget | Permite controlar el nivel de transparencia del contenedor, desde 0% hasta 100%. Para utilizarlo, el usuario debe mover el slider hasta el valor deseado. |
| 3 | Pestaña "Texto" | Configuración textual | Configura textos adicionales | Permite acceder a configuraciones relacionadas con textos auxiliares mostrados en el widget. |
| 3.1 | Campo "Subtítulo" | Campo de texto | Añade un texto secundario | Permite añadir un subtítulo que se muestra bajo el título principal del widget. Para utilizarlo, el usuario debe escribir el texto deseado en el campo "Texto secundario bajo el título". |
| 3.2 | Campo "Nota al pie" | Campo de texto | Añade una nota informativa | Permite añadir un texto pequeño al final del widget a modo de nota o aclaración. Para utilizarlo, el usuario debe escribir el texto deseado en el campo "Texto pequeño al final del widget". |

---

# 💡 Guía de Uso

El widget **Tabla por Asset** está diseñado para representar datos de variables en formato tabular donde cada fila corresponde a un asset industrial, permitiendo comparar el estado o valor de múltiples activos en un mismo vistazo.

Se utiliza principalmente para:

- Comparar variables entre múltiples activos industriales
- Visualizar el estado de una misma variable en diferentes equipos
- Monitorizar flotas de activos de forma centralizada
- Analizar diferencias de rendimiento entre zonas o máquinas
- Presentar datos tabulados por activo con formato visual personalizado
- Supervisar aulas, equipos o instalaciones de forma consolidada
- Detectar desviaciones entre activos de una misma categoría

## ✅ Cómo configurar correctamente el widget Tabla por Asset

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard.
3. Desde el panel de propiedades:
   - Configura las variables y el método de agregación.
   - Ajusta el rango temporal deseado.
   - Define el número de decimales en la sección Configuración Tabla por Asset.
   - Selecciona los assets a mostrar usando el buscador, la opción "Seleccionar todos" o añadiéndolos manualmente.
   - Personaliza los estilos de encabezados: fuente, peso y colores.
   - Personaliza los estilos de celdas: fuente, peso, colores y banda de título.
   - Configura el contenedor: marco, fondo y transparencia.
   - Añade subtítulo y nota al pie si se requiere contexto adicional.
4. Guarda los cambios realizados.
