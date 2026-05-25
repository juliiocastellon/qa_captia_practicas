# 📊 KPI · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **KPI**, utilizado para representar valores clave e indicadores de rendimiento industrial dentro de dashboards Analytics.

---

# 📸 Mapeo de Interfaz

<img width="1157" height="618" alt="image" src="https://github.com/user-attachments/assets/af86f599-769d-41f1-9fd5-a72cbab9a008" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Pestañas de configuración | Navegación interna | Cambia sección de propiedades | Permite alternar entre las distintas categorías de configuración del widget. Para utilizarlo, el usuario debe pulsar "Datos", "Apariencia" o "Texto" según el tipo de configuración que quiera modificar. |
| 1.1 | Campo "Nombre del widget" | Campo de texto | Renombra el widget | Permite definir el nombre identificativo del widget dentro del dashboard. Para utilizarlo, el usuario debe escribir el nombre que quiera mostrar en la cabecera del widget. |
| 1.2 | Sección "Configuración General" | Configuración de datos | Configura variables y agregación | Permite seleccionar las variables que utilizará el widget y cómo se procesarán los datos. Para utilizarlo, el usuario debe pulsar "Editar", seleccionar variables y configurar agregación e intervalo. |
| 1.2.1 | Botón "Editar" variables | Botón de acción | Abre selector de variables | Permite acceder al selector de variables para asignar las fuentes de datos del widget. Para utilizarlo, el usuario debe pulsar el icono de edición junto al campo de variables. |
| 1.3 | Selector "Agregación" | Lista desplegable | Define método de agregación | Permite seleccionar cómo se agregan los datos de la variable (Promedio, Suma, Máximo, etc.). Para utilizarlo, el usuario debe seleccionar la opción deseada en el desplegable. |
| 1.4 | Selector "Intervalo" | Lista desplegable | Define intervalo temporal | Permite configurar el intervalo de agrupación de los datos. Para utilizarlo, el usuario debe seleccionar la opción deseada, siendo "Automático" la opción por defecto. |
| 1.5 | Sección "Rango de Tiempo" | Configuración temporal | Configura periodo de datos | Permite definir el rango temporal utilizado por el widget. Para utilizarlo, el usuario puede usar el filtro global o configurar un rango propio. El texto informativo indica que el widget usará el selector de fechas del dashboard cuando se selecciona "Filtro global". |
| 1.6 | Sección "Comparación del KPI" | Configuración de análisis | Configura tendencia comparativa | Permite activar la visualización de la tendencia del periodo, mostrando el % de cambio del valor actual respecto al inicio de la ventana temporal activa. Para utilizarlo, el usuario debe activar la casilla "Mostrar tendencia del periodo". |
| 1.7 | Sección "Tipografía" — Familia de fuente | Lista desplegable | Selecciona la fuente tipográfica | Permite elegir la familia tipográfica del widget. Por defecto utiliza "Sistema (default)". Para modificarla, el usuario debe desplegar el selector y elegir la fuente deseada. |
| 1.8 | Sección "Tipografía" — Tamaño de fuente (px) | Slider numérico | Ajusta el tamaño del texto | Permite configurar el tamaño en píxeles del texto del valor principal. Para utilizarlo, el usuario debe mover el slider o introducir un valor numérico directamente. |
| 1.9 | Sección "Tipografía" — Peso de fuente | Lista desplegable | Ajusta el grosor del texto | Permite seleccionar el peso tipográfico del texto, como "Negrita". Para utilizarlo, el usuario debe seleccionar la opción deseada en el desplegable. |
| 1.10 | Sección "Tipografía" — Color del valor | Selector de color | Define el color del valor principal | Permite elegir el color del texto del valor KPI. Por defecto es #1E293B. Para utilizarlo, el usuario debe pulsar el selector de color y elegir el color deseado. |
| 1.11 | Sección "Tipografía" — Alineación | Botones de selección | Ajusta la alineación del texto | Permite alinear el contenido del widget a izquierda, centro, derecha o justificado. Para utilizarlo, el usuario debe pulsar el botón de alineación deseado. |
| 1.12 | Sección "Tipografía" — Decimales | Campo numérico | Define el número de decimales | Permite configurar cuántos decimales se mostrarán en el valor. Por defecto es 1. Para utilizarlo, el usuario debe introducir el número de decimales deseado. |
| 1.13 | Opción "Formato compacto (K, M)" | Casilla de verificación | Activa formato abreviado de números | Permite mostrar valores grandes en formato compacto (ej. 1.2k o 3.4M en lugar del número completo). Para utilizarlo, el usuario debe activar o desactivar la casilla según necesidad. |
| 1.14 | Campos "Prefijo" y "Sufijo / Unidad" | Campos de texto | Añade unidades o etiquetas al valor | Permite definir un prefijo (ej. $) y un sufijo o unidad (ej. kWh, %, ºC) que se muestran junto al valor KPI. Si no se define sufijo, se usará la unidad de la variable automáticamente. |
| 1.15 | Sección "Estados Booleanos (Opcional)" | Configuración condicional | Configura visualización de estados | Permite habilitar la configuración de estados booleanos seleccionando una variable booleana. Para utilizarlo, el usuario debe seleccionar una variable bool/ezina para habilitar esta configuración. |
| 2 | Pestaña "Apariencia" | Configuración visual | Personaliza el widget | Permite acceder a todas las configuraciones visuales del widget. |
| 2.1 | Sección "Contenedor" — Estilo de marco | Lista desplegable | Ajusta el estilo del contenedor | Permite seleccionar el estilo visual del marco del widget, como "Tarjeta". Para utilizarlo, el usuario debe seleccionar la opción deseada en el desplegable. |
| 2.2 | Opciones "Ocultar header" y "Ocultar borde" | Casillas de verificación | Controla la visibilidad de elementos | Permite ocultar la cabecera del widget y/o su borde exterior. Para utilizarlo, el usuario debe activar o desactivar cada casilla según el diseño deseado. |
| 2.3 | Selector "Fondo" | Selector de color | Define el color de fondo | Permite elegir el color de fondo del contenedor del widget. Por defecto es #FFFFFF. Para utilizarlo, el usuario debe pulsar el selector de color y elegir el color deseado. |
| 2.4 | Slider "Transparencia" | Slider | Ajusta la opacidad del widget | Permite controlar el nivel de transparencia del contenedor, desde 0% hasta 100%. Para utilizarlo, el usuario debe mover el slider hasta el valor deseado. |
| 3 | Pestaña "Texto" | Configuración textual | Configura textos adicionales | Permite acceder a configuraciones relacionadas con textos auxiliares mostrados en el widget. |
| 3.1 | Campo "Subtítulo" | Campo de texto | Añade un texto secundario | Permite añadir un subtítulo que se muestra bajo el título principal del widget. Para utilizarlo, el usuario debe escribir el texto deseado en el campo "Texto secundario bajo el título". |
| 3.2 | Campo "Nota al pie" | Campo de texto | Añade una nota informativa | Permite añadir un texto pequeño al final del widget a modo de nota o aclaración. Para utilizarlo, el usuario debe escribir el texto deseado en el campo "Texto pequeño al final del widget". |

---

# 💡 Guía de Uso

El widget **KPI** está diseñado para representar un valor clave de forma destacada y clara dentro del dashboard.

Se utiliza principalmente para:

- Mostrar valores instantáneos de una variable
- Visualizar indicadores de rendimiento (KPIs)
- Comparar el valor actual frente a un periodo anterior
- Supervisar umbrales o estados críticos
- Mostrar datos con unidades y formato personalizado
- Monitorizar variables en tiempo real
- Representar estados booleanos de forma visual

## ✅ Cómo configurar correctamente el widget KPI

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard.
3. Desde el panel de propiedades:
   - Configura la variable y el método de agregación.
   - Ajusta el intervalo y el rango temporal.
   - Personaliza tipografía, color y alineación.
   - Configura decimales, prefijo y sufijo.
   - Activa el formato compacto si es necesario.
   - Habilita la comparación del KPI para mostrar tendencias.
   - Personaliza el contenedor: marco, fondo y transparencia.
   - Añade subtítulo y nota al pie si se requiere contexto adicional.
4. Guarda los cambios realizados.
