# 📊 Gauge · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Gauge**, utilizado para representar visualmente un valor dentro de un rango operativo definido, con zonas de color y estados de alerta, dentro de dashboards Analytics.

---

# 📸 Mapeo de Interfaz

<img width="1182" height="627" alt="image" src="https://github.com/user-attachments/assets/c9c542ee-b534-416a-b6ae-bca041fa53ae" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Pestañas de configuración | Navegación interna | Cambia sección de propiedades | Permite alternar entre las distintas categorías de configuración del widget. Para utilizarlo, el usuario debe pulsar "Datos", "Apariencia" o "Texto" según el tipo de configuración que quiera modificar. |
| 1.1 | Campo "Nombre del widget" | Campo de texto | Renombra el widget | Permite definir el nombre identificativo del widget dentro del dashboard. Para utilizarlo, el usuario debe escribir el nombre que quiera mostrar en la cabecera del widget. |
| 1.2 | Sección "Configuración General" | Configuración de datos | Configura variables y agregación | Permite seleccionar la variable que utilizará el gauge y cómo se procesarán los datos. Para utilizarlo, el usuario debe pulsar "Editar", seleccionar la variable y configurar agregación e intervalo. |
| 1.3 | Sección "Rango de Tiempo" | Configuración temporal | Configura el periodo de datos | Permite definir el rango temporal utilizado por el widget. El usuario puede usar el filtro global, de modo que el widget usará el selector de fechas del dashboard, o configurar un rango propio. |
| 1.4 | Sección "Escala del Gauge" | Configuración de escala | Define el rango operativo | Permite establecer los valores mínimo y máximo del gauge. El valor real se normaliza sobre esta escala. Para utilizarlo, el usuario debe introducir el valor mínimo (inicio de la escala) y el valor máximo (fin de la escala). La vista previa muestra el rango configurado. |
| 1.5 | Sección "Zonas de color" | Configuración visual condicional | Define umbrales de color | Permite añadir zonas de color asociadas a umbrales de valor real. Cada zona define un umbral y el color se aplica hasta ese umbral. Para utilizarlo, el usuario debe pulsar "+ Añadir zona" y configurar los umbrales deseados. Adicionalmente, la opción "Mostrar badge de estado" muestra un indicador bajo el gauge con el estado "En rango", "Fuera de rango" o "Sin datos". |
| 1.6 | Sección "Comparación del KPI" | Configuración de análisis | Configura tendencia comparativa | Permite activar la visualización de la tendencia del periodo, mostrando el % de cambio del valor actual respecto al inicio de la ventana temporal activa. Para utilizarlo, el usuario debe activar la casilla "Mostrar tendencia del periodo". |
| 1.7 | Sección "Tipografía" — Familia de fuente | Lista desplegable | Selecciona la fuente tipográfica | Permite elegir la familia tipográfica del widget. Por defecto utiliza "Sistema (default)". Para modificarla, el usuario debe desplegar el selector y elegir la fuente deseada. |
| 1.8 | Sección "Tipografía" — Tamaño de fuente (px) | Slider numérico | Ajusta el tamaño del texto | Permite configurar el tamaño en píxeles del texto del valor principal, con un rango entre 12px y 120px. Para utilizarlo, el usuario debe mover el slider o introducir un valor numérico directamente. |
| 1.9 | Sección "Tipografía" — Peso de fuente | Lista desplegable | Ajusta el grosor del texto | Permite seleccionar el peso tipográfico del texto, como "Negrita". Para utilizarlo, el usuario debe seleccionar la opción deseada en el desplegable. |
| 1.10 | Sección "Tipografía" — Color del valor | Selector de modo | Define el color del valor principal | Permite elegir entre "Automático", donde el color cambia según el estado (verde en rango, rojo fuera de rango), o "Color fijo" para establecer un color personalizado independiente del estado. |
| 1.11 | Sección "Tipografía" — Decimales y formato | Configuración numérica | Ajusta la presentación del valor | Permite configurar el número de decimales mostrados y activar el formato compacto (K, M) para valores grandes. También permite definir un prefijo (ej. $) y un sufijo o unidad (ej. kWh, %, ºC). Si no se define sufijo, se usará la unidad de la variable automáticamente. |
| 1.12 | Sección "Estados Booleanos (Opcional)" | Configuración condicional | Configura visualización de estados | Permite habilitar la configuración de estados booleanos seleccionando una variable booleana. Para utilizarlo, el usuario debe seleccionar una variable booleana para habilitar esta configuración. |
| 2 | Pestaña "Apariencia" | Configuración visual | Personaliza el widget | Permite acceder a todas las configuraciones visuales del contenedor del widget. |
| 2.1 | Sección "Contenedor" — Estilo de marco | Lista desplegable | Ajusta el estilo del contenedor | Permite seleccionar el estilo visual del marco del widget, como "Tarjeta". Para utilizarlo, el usuario debe seleccionar la opción deseada en el desplegable. |
| 2.2 | Opciones "Ocultar header" y "Ocultar borde" | Casillas de verificación | Controla la visibilidad de elementos | Permite ocultar la cabecera del widget y/o su borde exterior. Para utilizarlo, el usuario debe activar o desactivar cada casilla según el diseño deseado. |
| 2.3 | Selector "Fondo" | Selector de color | Define el color de fondo | Permite elegir el color de fondo del contenedor del widget. Por defecto es #FFFFFF. Para utilizarlo, el usuario debe pulsar el selector de color y elegir el color deseado. |
| 2.4 | Slider "Transparencia" | Slider | Ajusta la opacidad del widget | Permite controlar el nivel de transparencia del contenedor, desde 0% hasta 100%. Para utilizarlo, el usuario debe mover el slider hasta el valor deseado. |
| 3 | Pestaña "Texto" | Configuración textual | Configura textos adicionales | Permite acceder a configuraciones relacionadas con textos auxiliares mostrados en el widget. |
| 3.1 | Campo "Subtítulo" | Campo de texto | Añade un texto secundario | Permite añadir un subtítulo que se muestra bajo el título principal del widget. Para utilizarlo, el usuario debe escribir el texto deseado en el campo "Texto secundario bajo el título". |
| 3.2 | Campo "Nota al pie" | Campo de texto | Añade una nota informativa | Permite añadir un texto pequeño al final del widget a modo de nota o aclaración. Para utilizarlo, el usuario debe escribir el texto deseado en el campo "Texto pequeño al final del widget". |

---

# 💡 Guía de Uso

El widget **Gauge** está diseñado para representar visualmente un valor dentro de un rango operativo definido, permitiendo identificar de forma inmediata si el valor se encuentra dentro o fuera del rango esperado.

Se utiliza principalmente para:

- Visualizar el nivel actual de una variable respecto a su rango operativo
- Supervisar umbrales críticos mediante zonas de color
- Mostrar estados de alerta (en rango / fuera de rango)
- Monitorizar variables industriales en tiempo real
- Comparar el valor actual frente a un periodo anterior
- Representar métricas con unidades y formato personalizado
- Analizar tendencias de comportamiento respecto al rango definido

## ✅ Cómo configurar correctamente el widget Gauge

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard.
3. Desde el panel de propiedades:
   - Configura la variable y el método de agregación.
   - Ajusta el rango temporal deseado.
   - Define los valores mínimo y máximo de la escala del gauge.
   - Añade zonas de color con sus umbrales correspondientes.
   - Activa el badge de estado si se necesita indicador visual.
   - Habilita la comparación del KPI para mostrar tendencias.
   - Personaliza tipografía, color (automático o fijo) y formato numérico.
   - Configura el contenedor: marco, fondo y transparencia.
   - Añade subtítulo y nota al pie si se requiere contexto adicional.
4. Guarda los cambios realizados.

[← Volver a Widgets Indicadores](../../widgetsAnalytics_indicadores.md)
