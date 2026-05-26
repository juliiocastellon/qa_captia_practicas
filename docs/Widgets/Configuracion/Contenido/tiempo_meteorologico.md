# 📊 Tiempo Meteorológico · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Tiempo Meteorológico**, utilizado para mostrar condiciones climáticas actuales y previsiones meteorológicas de una ubicación geográfica concreta dentro de dashboards Analytics.

---

# 📸 Mapeo de Interfaz

<img width="1018" height="554" alt="Captura de pantalla 2026-05-26 113405" src="https://github.com/user-attachments/assets/12360b9b-e443-4085-b70d-500051b01cd7" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Pestañas de configuración | Navegación interna | Cambia sección de propiedades | Permite alternar entre las distintas categorías de configuración del widget. Para utilizarlo, el usuario debe pulsar "Datos", "Apariencia" o "Texto" según el tipo de configuración que quiera modificar. |
| 1.1 | Campo "Nombre del widget" | Campo de texto | Renombra el widget | Permite definir el nombre identificativo del widget dentro del dashboard. Para utilizarlo, el usuario debe escribir el nombre que quiera mostrar en la cabecera del widget. |
| 1.2 | Sección "Ubicación" | Configuración de localización | Define la ubicación meteorológica | Permite introducir las coordenadas geográficas (latitud y longitud) de la ubicación para la cual se obtendrán los datos meteorológicos. El sistema indica que las coordenadas se pueden obtener desde Google Maps haciendo clic derecho sobre el mapa y seleccionando "¿Qué hay aquí?". |
| 1.3 | Sección "Visualización" | Configuración de presentación | Configura unidades y horizonte de previsión | Permite seleccionar el sistema de unidades (por defecto "Métrico (ºC, m/s)"), el horizonte de previsión por horas (por defecto "12 horas") y el número de días de pronóstico (por defecto "3 días"). Para utilizarlo, el usuario debe seleccionar las opciones deseadas en cada desplegable. |
| 1.4 | Sección "Parámetros a Mostrar" | Configuración de contenido | Selecciona la información meteorológica visible | Permite activar o desactivar los bloques de información que se mostrarán en el widget. Los parámetros principales disponibles son: "Mostrar estado actual" (temperatura actual, condición y ubicación), "Mostrar pronóstico por horas" (gráfica con temperatura de las próximas horas) y "Mostrar pronóstico por días" (pronóstico para los próximos días). Adicionalmente, en la sección "Detalles adicionales" el usuario puede activar o desactivar "Sensación térmica", "Velocidad del viento" y "Humedad". Todos los parámetros están activados por defecto. |
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

El widget **Tiempo Meteorológico** está diseñado para mostrar las condiciones climáticas actuales y la previsión meteorológica de una ubicación geográfica definida, integrando información ambiental relevante en el contexto del dashboard industrial.

Se utiliza principalmente para:

- Mostrar las condiciones climáticas actuales de una instalación o planta
- Visualizar previsiones horarias y diarias de temperatura
- Correlacionar datos industriales con condiciones meteorológicas externas
- Monitorizar parámetros ambientales como humedad, viento y sensación térmica
- Apoyar la toma de decisiones operativas en función del clima
- Integrar contexto meteorológico en dashboards de eficiencia energética
- Supervisar condiciones externas que puedan afectar a procesos productivos

## ✅ Cómo configurar correctamente el widget Tiempo Meteorológico

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard.
3. Desde el panel de propiedades:
   - Introduce las coordenadas de latitud y longitud de la ubicación deseada. Puedes obtenerlas desde Google Maps haciendo clic derecho sobre el punto y seleccionando "¿Qué hay aquí?".
   - Selecciona el sistema de unidades, el horizonte de previsión por horas y el número de días de pronóstico.
   - Activa o desactiva los parámetros a mostrar según las necesidades del dashboard: estado actual, pronóstico por horas, pronóstico por días, sensación térmica, velocidad del viento y humedad.
   - Personaliza el contenedor: marco, fondo y transparencia.
   - Añade subtítulo y nota al pie si se requiere contexto adicional.
4. Guarda los cambios realizados.


[← Volver a Widgets SCADA Básicos](../../widgetsAnalitycs_contenido.md)

