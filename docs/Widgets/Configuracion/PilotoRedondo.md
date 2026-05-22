# 🔵 Piloto Redondo · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el comportamiento visual y lógico del widget **Piloto Redondo**, utilizado para representar visualmente estados industriales, señales booleanas y condiciones operativas mediante indicadores luminosos.

---

# 📸 Mapeo de Interfaz

<img width="1367" height="745" alt="image" src="https://github.com/user-attachments/assets/ff61398b-7f6f-42f6-bead-e577fb616d6a" />


---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Elemento" | Configuración del widget | Gestiona el estado del widget | Permite visualizar el tipo de widget seleccionado y bloquearlo para evitar moverlo accidentalmente dentro del dashboard o SCADA. Para utilizarlo, el usuario debe pulsar “Bloquear” cuando quiera fijar definitivamente su posición. |
| 2 | Sección "Capas" | Organización visual | Gestiona superposición | Permite controlar cómo se posiciona el Piloto Redondo respecto a otros widgets del canvas. Para utilizarlo, el usuario puede modificar el Z-Index manualmente o utilizar “Traer al frente” y “Enviar atrás”. |
| 3 | Sección "Datos" | Configuración de variables | Configura la señal del piloto | Permite seleccionar la variable que controlará el estado visual del piloto. Para utilizarlo, el usuario debe pulsar “Cambiar” y seleccionar una señal booleana o variable de estado. |
| 4 | Sección "Piloto" | Configuración visual principal | Personaliza apariencia del piloto | Permite modificar el tamaño, estilo y comportamiento visual general del piloto. Para utilizarlo, el usuario puede ajustar el diámetro, tamaño de imagen y seleccionar distintos estilos visuales. |
| 4.1 | Subsección "Apariencia" | Configuración visual | Ajusta estilo del piloto | Permite definir cómo se visualizará el piloto dentro del dashboard o SCADA. Para utilizarlo, el usuario puede modificar diámetro, bordes y comportamiento visual del indicador. |
| 4.2 | Subsección "Colores" | Configuración de estados | Configura colores y estados | Permite asignar colores e imágenes distintas según el valor de la variable asociada. Para utilizarlo, el usuario debe definir cada estado, seleccionar colores y activar “Blink” si desea parpadeo visual. |
| 5 | Sección "Etiqueta" | Configuración textual | Configura labels y tendencias | Permite mostrar etiquetas descriptivas junto al piloto. Para utilizarlo, el usuario puede activar “Mostrar label”, definir el texto, cambiar colores y activar la visualización del valor o botón de tendencia. |
| 6 | Sección "Padding" | Configuración de espaciado | Ajusta márgenes internos | Permite modificar el espacio interior entre el contenido y los límites del widget. Para utilizarlo, el usuario debe ajustar los paddings superior, inferior, izquierdo y derecho según el diseño deseado. |
| 7 | Sección "Editor" | Configuración del canvas | Ajusta comportamiento de edición | Permite activar el ajuste automático a cuadrícula para facilitar la alineación del widget dentro del canvas. Para utilizarlo, el usuario debe activar “Snap a cuadrícula”. |
| 8 | Sección "Acciones" | Gestión del widget | Elimina el widget | Permite eliminar el Piloto Redondo del dashboard o pantalla SCADA. Para utilizarlo, el usuario debe seleccionar el widget y pulsar “Eliminar elemento”. |

---

# 💡 Guía de Uso

El widget **Piloto Redondo** está diseñado para representar visualmente estados industriales de manera rápida e intuitiva.

Se utiliza principalmente para mostrar:

- Máquinas encendidas o apagadas
- Alarmas activas
- Estados de producción
- Conectividad de equipos
- Señales booleanas
- Estados operativos
- Indicadores de fallo o mantenimiento

## ✅ Cómo configurar correctamente el Piloto Redondo

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard o SCADA.
3. Desde el panel de propiedades:
   - Selecciona la variable de estado.
   - Configura colores para ON/OFF.
   - Ajusta tamaño y estilo visual.
   - Añade etiquetas descriptivas.
   - Configura efectos Blink si es necesario.
4. Guarda los cambios realizados.

[← Volver a Widgets SCADA Básicos](../widgetsScada_basicos.md)
