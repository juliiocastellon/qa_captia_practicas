# 📊 Grupo de KPIs · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Grupo de KPIs**, utilizado para representar múltiples indicadores de rendimiento agrupados visualmente dentro de dashboards Analytics.

---

# 📸 Mapeo de Interfaz

<img width="1122" height="597" alt="Captura de pantalla 2026-05-25 123018" src="https://github.com/user-attachments/assets/17da4cff-a485-43a2-bb8d-0d5372b80e6f" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Pestañas de configuración | Navegación interna | Cambia sección de propiedades | Permite alternar entre las distintas categorías de configuración del widget. Para utilizarlo, el usuario debe pulsar "Datos", "Apariencia" o "Texto" según el tipo de configuración que quiera modificar. |
| 1.1 | Campo "Nombre del widget" | Campo de texto | Renombra el widget | Permite definir el nombre identificativo del widget dentro del dashboard. Para utilizarlo, el usuario debe escribir el nombre que quiera mostrar en la cabecera del widget. |
| 1.2 | Sección "Configuración General" | Configuración de datos | Configura variables y agregación | Permite seleccionar las variables que utilizará el widget y cómo se procesarán los datos. Para utilizarlo, el usuario debe pulsar "Editar", seleccionar variables y configurar agregación e intervalo. |
| 1.3 | Sección "Tarjetas KPI" | Configuración de tarjetas | Gestiona las tarjetas KPI individuales | Permite añadir y configurar cada KPI individual dentro del grupo. Muestra el mensaje "Añade al menos dos KPIs desde las variables seleccionadas" cuando no hay variables asignadas. Para utilizarlo, el usuario debe primero seleccionar variables en la Configuración General. |
| 1.4 | Sección "Opciones de Visualización" | Configuración visual | Ajusta la presentación del grupo | Permite configurar el espaciado entre tarjetas y activar modos de visualización especiales. Incluye las siguientes opciones: "Mostrar slider" para mostrar las tarjetas en carrusel, "Modo compacto" para reducir padding y tamaño de fuentes, y "Modo transparente" para eliminar fondo, borde y sombra. Para utilizarlo, el usuario debe introducir el valor de espaciado deseado en píxeles y activar las casillas según necesidad. |
| 1.5 | Sección "Rango de Tiempo" | Configuración temporal | Configura el periodo de datos | Permite definir el rango temporal utilizado por el widget. El usuario puede usar el filtro global, de modo que el widget usará el selector de fechas del dashboard, o configurar un rango propio. |
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

El widget **Grupo de KPIs** está diseñado para agrupar y representar múltiples indicadores de rendimiento en un único contenedor visual.

Se utiliza principalmente para:

- Mostrar varios KPIs relacionados en un mismo espacio
- Comparar indicadores de una misma categoría
- Organizar métricas por área o proceso
- Visualizar datos en modo carrusel para espacios reducidos
- Supervisar múltiples variables simultáneamente
- Monitorizar indicadores en tiempo real
- Presentar dashboards compactos y organizados

## ✅ Cómo configurar correctamente el widget Grupo de KPIs

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard.
3. Desde el panel de propiedades:
   - Configura las variables y el método de agregación.
   - Añade al menos dos KPIs desde las variables seleccionadas.
   - Ajusta el espaciado entre tarjetas.
   - Activa el modo slider, compacto o transparente si es necesario.
   - Configura el rango temporal deseado.
   - Personaliza el contenedor: marco, fondo y transparencia.
   - Añade subtítulo y nota al pie si se requiere contexto adicional.
4. Guarda los cambios realizados.

[← Volver a Widgets Indicadores](../../widgetsAnalytics_indicadores.md)

