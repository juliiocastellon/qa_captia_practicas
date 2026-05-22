# 📊 Indicador de Lectura · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el aspecto visual, comportamiento y datos mostrados por el widget **Indicador de Lectura**, utilizado para visualizar variables industriales y valores en tiempo real.

---

# 📸 Mapeo de Interfaz

<img width="1317" height="577" alt="image" src="https://github.com/user-attachments/assets/2bf71c51-2c5b-462c-aa35-ece35aab17e8" />


---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Elemento" | Configuración del widget | Gestiona el estado del widget | Permite visualizar el tipo de widget seleccionado y bloquearlo para evitar moverlo accidentalmente dentro del dashboard o SCADA. Para utilizarlo, el usuario debe pulsar el botón “Bloquear” cuando quiera fijar definitivamente su posición. |
| 2 | Sección "Capas" | Organización visual | Gestiona superposición | Permite controlar cómo se posiciona el Indicador de Lectura respecto a otros widgets del canvas. Para utilizarlo, el usuario puede modificar el Z-Index manualmente o utilizar “Traer al frente” y “Enviar atrás” para reorganizar visualmente el widget. |
| 3 | Sección "General" | Configuración básica | Personaliza el widget | Permite modificar el título y comportamiento general del Indicador de Lectura. Para utilizarlo, el usuario puede escribir un nombre personalizado, activar “Mostrar título” para visualizarlo encima del widget o activar “Mostrar botón tendencia” para permitir el acceso rápido a gráficas históricas de la variable. |
| 4 | Sección "Tipografía" | Configuración visual | Cambia tamaños de texto | Permite ajustar el tamaño del título y del valor numérico mostrado en el Indicador de Lectura. Para utilizarlo, el usuario debe mover los sliders hasta conseguir el tamaño visual adecuado según el espacio disponible en pantalla. |
| 5 | Configuración "Color texto" | Selector visual | Modifica colores del widget | Permite cambiar el color y opacidad del texto mostrado por el Indicador de Lectura. Para utilizarlo, el usuario debe seleccionar el color deseado y ajustar la transparencia usando el slider de opacidad. |
| 6 | Configuración "Peso" | Selector de estilo | Cambia grosor tipográfico | Permite aplicar diferentes estilos visuales al texto del Indicador de Lectura. Para utilizarlo, el usuario puede seleccionar opciones como “Semibold” o “Bold” para dar mayor visibilidad al valor mostrado. |
| 7 | Configuración "Alineación" | Selector desplegable | Ajusta posición del contenido | Permite definir cómo se alineará el contenido del widget dentro del espacio disponible. Para utilizarlo, el usuario debe seleccionar izquierda, centro o derecha según el diseño del dashboard o SCADA. |
| 8 | Sección "Variables" | Configuración de datos | Añade variables industriales | Permite seleccionar las variables que mostrará el Indicador de Lectura. Para utilizarlo, el usuario debe pulsar “Añadir variable” y escoger una o varias señales industriales disponibles. El widget soporta entre 1 y 10 variables simultáneamente. |
| 9 | Configuración "Color fondo" | Configuración visual | Modifica fondo del widget | Permite cambiar el color y transparencia del fondo del Indicador de Lectura. Para utilizarlo, el usuario debe seleccionar un color y ajustar el nivel de opacidad para adaptarlo visualmente al dashboard. |
| 10 | Configuración "Color borde" | Configuración visual | Modifica bordes | Permite cambiar el color y grosor del borde del Indicador de Lectura. Para utilizarlo, el usuario debe seleccionar un color y ajustar el grosor utilizando el selector correspondiente. |
| 11 | Configuración "Padding" | Configuración de espaciado | Ajusta márgenes internos | Permite modificar el espacio interior entre el contenido y los bordes del widget. Para utilizarlo, el usuario debe ajustar los valores de padding superior, inferior, izquierdo y derecho hasta conseguir una distribución visual cómoda y equilibrada. |
| 12 | Sección "Editor" | Configuración del canvas | Ajusta comportamiento de edición | Permite activar el ajuste automático a cuadrícula mientras se mueve el Indicador de Lectura dentro del canvas. Para utilizarlo, el usuario debe activar “Snap a cuadrícula” si quiere alinear widgets automáticamente. |
| 13 | Sección "Acciones" | Gestión del widget | Elimina el widget | Permite eliminar el Indicador de Lectura del dashboard o pantalla SCADA. Para utilizarlo, el usuario debe seleccionar el widget y pulsar “Eliminar elemento”. |

---

# 💡 Guía de Uso

El widget **Indicador de Lectura** está diseñado para mostrar información crítica de forma rápida y visual dentro de dashboards y pantallas SCADA.


## ✅ Cómo configurar correctamente el Indicador de Lectura

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard o SCADA.
3. Desde el panel de propiedades:
   - Configura el título.
   - Añade variables industriales.
   - Ajusta tamaños y colores.
   - Configura alineación y tipografía.
   - Personaliza fondo y bordes.
4. Guarda los cambios realizados.

[← Volver a Widgets SCADA Básicos](../widgetsScada_basicos.md)
