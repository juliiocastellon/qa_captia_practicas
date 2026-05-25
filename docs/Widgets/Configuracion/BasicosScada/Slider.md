# 🎚️ Slider / Consigna · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Slider / Consigna**, utilizado para modificar valores numéricos de forma visual e interactiva dentro de dashboards y pantallas SCADA.

---

# 📸 Mapeo de Interfaz

<img width="1294" height="596" alt="image" src="https://github.com/user-attachments/assets/669d65e9-d2c7-4a56-bf09-10a77de28785" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Elemento" | Configuración del widget | Gestiona el estado del widget | Permite visualizar el tipo de widget seleccionado y bloquearlo para evitar moverlo accidentalmente dentro del dashboard o SCADA. Para utilizarlo, el usuario debe pulsar “Bloquear” cuando quiera fijar definitivamente su posición. |
| 2 | Sección "Capas" | Organización visual | Gestiona superposición | Permite controlar cómo se posiciona el Slider respecto a otros widgets del canvas. Para utilizarlo, el usuario puede modificar el Z-Index manualmente o utilizar “Traer al frente” y “Enviar atrás”. |
| 3 | Sección "Variables" | Configuración de datos | Configura lectura y escritura | Permite seleccionar las variables utilizadas por el Slider tanto para lectura como para escritura. Para utilizarlo, el usuario debe pulsar “Cambiar” y seleccionar las señales deseadas. También permite configurar el modo de confirmación. |
| 4 | Sección "General" | Configuración básica | Personaliza el widget | Permite modificar el título, unidad y visualización general del Slider. Para utilizarlo, el usuario puede activar o desactivar la visualización de valores, unidades o porcentajes y configurar los decimales mostrados. |
| 5 | Sección "Forma" | Configuración de comportamiento | Ajusta orientación y rango | Permite definir la orientación del Slider y el rango de valores permitido. Para utilizarlo, el usuario debe seleccionar orientación horizontal o vertical y configurar valores mínimos, máximos y pasos. |
| 6 | Sección "Colores" | Configuración visual | Personaliza apariencia | Permite modificar los colores del Slider y sus diferentes elementos visuales. Para utilizarlo, el usuario puede configurar colores para relleno, pista, manilla, valor, etiquetas, pendientes y fondo. |
| 7 | Sección "Comportamiento" | Configuración funcional | Ajusta envío de consignas | Permite configurar cómo responderá el Slider durante la interacción del operador. Para utilizarlo, el usuario puede definir retardos de envío, bloqueos, timeouts y tolerancias de confirmación. |
| 8 | Sección "Estilo" | Configuración visual | Ajusta tamaños y estilos | Permite modificar tamaños de texto, grosor de pista, tamaño de manilla y separaciones visuales del Slider. Para utilizarlo, el usuario debe ajustar los sliders hasta conseguir el diseño deseado. |
| 9 | Sección "Editor" | Configuración del canvas | Ajusta comportamiento de edición | Permite activar el ajuste automático a cuadrícula mientras se mueve el Slider dentro del canvas. Para utilizarlo, el usuario debe activar “Snap a cuadrícula”. |
| 10 | Sección "Acciones" | Gestión del widget | Elimina el widget | Permite eliminar el Slider del dashboard o pantalla SCADA. Para utilizarlo, el usuario debe seleccionar el widget y pulsar “Eliminar elemento”. |

---

# 💡 Guía de Uso

El widget **Slider / Consigna** está diseñado para permitir al operador modificar valores de forma rápida e intuitiva mediante controles deslizantes.

Se utiliza principalmente para:

- Ajustar consignas industriales
- Regular velocidades
- Modificar porcentajes
- Controlar niveles
- Ajustar parámetros de producción
- Gestionar valores dinámicos

## ✅ Cómo configurar correctamente el Slider / Consigna

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard o SCADA.
3. Desde el panel de propiedades:
   - Configura variables de lectura y escritura.
   - Define rangos mínimos y máximos.
   - Ajusta orientación y pasos.
   - Personaliza colores y estilos.
   - Configura comportamiento y confirmaciones.
4. Guarda los cambios realizados.

---

[← Volver a Widgets SCADA Básicos](../widgetsScada_basicos.md)
