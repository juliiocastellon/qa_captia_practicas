# 📊 Tabla · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Tabla**, utilizado para representar datos de variables en formato tabular con filas temporales, encabezados personalizables y estilos visuales dentro de dashboards Analytics.

---

# 📸 Mapeo de Interfaz

<img width="1334" height="649" alt="Captura de pantalla 2026-05-26 095904" src="https://github.com/user-attachments/assets/166b48d6-5149-4dd4-a7ac-a28812ccc097" />


---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Pestañas de configuración | Navegación interna | Cambia sección de propiedades | Permite alternar entre las distintas categorías de configuración del widget. Para utilizarlo, el usuario debe pulsar "Datos", "Apariencia" o "Texto" según el tipo de configuración que quiera modificar. |
| 1.1 | Campo "Nombre del widget" | Campo de texto | Renombra el widget | Permite definir el nombre identificativo del widget dentro del dashboard. Para utilizarlo, el usuario debe escribir el nombre que quiera mostrar en la cabecera del widget. |
| 1.2 | Sección "Configuración General" | Configuración de datos | Configura variables y agregación | Permite seleccionar las variables que utilizará la tabla y cómo se procesarán los datos. Para utilizarlo, el usuario debe pulsar "Editar", seleccionar las variables y configurar agregación e intervalo. |
| 1.3 | Sección "Rango de Tiempo" | Configuración temporal | Configura el periodo de datos | Permite definir el rango temporal utilizado por el widget. El usuario puede usar el filtro global, de modo que el widget usará el selector de fechas del dashboard, o configurar un rango propio. |
| 1.4 | Sección "Configuración de Tabla" | Configuración estructural | Define la estructura y formato de la tabla | Permite configurar el número máximo de filas mostradas (por defecto 10), el número de decimales (por defecto 1), el formato de fecha (por defecto dd/MM/yyyy HH:mm) y la visibilidad de la columna de fecha/hora mediante la casilla "Mostrar columna de fecha/hora". |
| 1.5 | Sección "Nombres de Columnas" | Configuración de encabezados | Personaliza los nombres de las columnas | Permite definir el nombre que se mostrará en el encabezado de cada columna de la tabla, incluyendo la columna de fecha/hora y las columnas de variables. También permite configurar la alineación del contenido de cada columna (por defecto "Izquierda"). El sistema indica que es necesario seleccionar variables en la pestaña "Datos" para poder renombrar las columnas. |
| 1.6 | Sección "Estilos de Encabezados" | Configuración visual | Personaliza el estilo de los encabezados | Permite configurar el tamaño de fuente en píxeles (por defecto 11), el peso de fuente (por defecto "Negrita"), el color del texto y el color de fondo de los encabezados de la tabla. Para utilizarlo, el usuario debe ajustar los valores y selectores de color según el diseño deseado. |
| 1.7 | Sección "Estilos de Celdas" | Configuración visual | Personaliza el estilo de las celdas | Permite configurar el tamaño de fuente en píxeles (por defecto 13), el peso de fuente (por defecto "Normal"), el color del texto y el color de fondo de las celdas de datos de la tabla. Para utilizarlo, el usuario debe ajustar los valores y selectores de color según el diseño deseado. |
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

El widget **Tabla** está diseñado para representar datos de variables en formato tabular, mostrando registros temporales con columnas personalizables y estilos diferenciados para encabezados y celdas.

Se utiliza principalmente para:

- Visualizar registros históricos de variables en formato tabla
- Comparar múltiples variables en un mismo rango temporal
- Exportar visualmente datos tabulados dentro del dashboard
- Mostrar datos con formato de fecha y número personalizado
- Supervisar lecturas ordenadas cronológicamente
- Analizar series de datos con precisión decimal configurable
- Presentar información estructurada con estilos visuales corporativos

## ✅ Cómo configurar correctamente el widget Tabla

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard.
3. Desde el panel de propiedades:
   - Configura las variables y el método de agregación.
   - Ajusta el rango temporal deseado.
   - Define el número máximo de filas, decimales y formato de fecha.
   - Activa o desactiva la columna de fecha/hora según necesidad.
   - Personaliza los nombres y alineación de cada columna.
   - Ajusta los estilos visuales de encabezados y celdas.
   - Personaliza el contenedor: marco, fondo y transparencia.
   - Añade subtítulo y nota al pie si se requiere contexto adicional.
4. Guarda los cambios realizados.

[← Volver a Widgets](../../widgetsAnalytics_datos.md)

