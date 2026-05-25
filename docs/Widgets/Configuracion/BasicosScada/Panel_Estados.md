# 📋 Panel de Estados · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Panel de Estados**, utilizado para visualizar múltiples estados industriales en una lista organizada y visualmente clara dentro de dashboards y pantallas SCADA.

---

# 📸 Mapeo de Interfaz

<img width="1590" height="623" alt="image" src="https://github.com/user-attachments/assets/4b5fd269-2875-4afc-bb95-8500abde2767" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Elemento" | Configuración del widget | Gestiona el estado del widget | Permite visualizar el tipo de widget seleccionado y bloquearlo para evitar moverlo accidentalmente dentro del dashboard o SCADA. Para utilizarlo, el usuario debe pulsar “Bloquear” cuando quiera fijar definitivamente su posición. |
| 2 | Sección "Capas" | Organización visual | Gestiona superposición | Permite controlar cómo se posiciona el Panel de Estados respecto a otros widgets del canvas. Para utilizarlo, el usuario puede modificar el Z-Index manualmente o utilizar “Traer al frente” y “Enviar atrás”. |
| 3 | Sección "General" | Configuración básica | Personaliza el panel | Permite modificar el título y comportamiento general del Panel de Estados. Para utilizarlo, el usuario puede escribir un nombre personalizado, seleccionar el tamaño visual del panel y activar opciones como tooltips en hover. |
| 4 | Sección "Estilo del Panel" | Configuración visual | Personaliza apariencia general | Permite modificar el fondo, bordes, padding y sombras del Panel de Estados. Para utilizarlo, el usuario debe seleccionar colores y ajustar sliders según el diseño visual deseado. |
| 5 | Sección "Estilo del Título" | Configuración textual | Ajusta el encabezado | Permite modificar el color, tamaño y formato del título mostrado en el panel. Para utilizarlo, el usuario puede cambiar el tamaño del texto o activar mayúsculas automáticas. |
| 6 | Sección "Estilo de Filas" | Configuración visual | Ajusta apariencia de filas | Permite configurar la altura, espaciado y apariencia de cada fila del panel. Para utilizarlo, el usuario debe ajustar sliders y activar divisores si desea separar visualmente cada estado mostrado. |
| 7 | Sección "Estados" | Configuración de estados | Añade y configura estados | Permite crear y configurar los diferentes estados que mostrará el panel. Para utilizarlo, el usuario debe añadir estados, asignar etiquetas y seleccionar las variables correspondientes. |
| 7.1 | Configuración de Estado | Configuración individual | Personaliza cada estado | Permite configurar individualmente cada estado del panel. Para utilizarlo, el usuario debe definir etiqueta, variable asociada, tipo de señal y colores ON/OFF. También puede activar Blink para estados críticos. |
| 8 | Sección "Colores por defecto" | Configuración visual | Configura colores globales | Permite definir los colores fallback utilizados automáticamente para distintos tipos de estados como OFF, ON, alarma o aviso. Para utilizarlo, el usuario debe seleccionar los colores deseados y ajustar la opacidad. |
| 9 | Sección "Editor" | Configuración del canvas | Ajusta comportamiento de edición | Permite activar el ajuste automático a cuadrícula mientras se mueve el Panel de Estados dentro del canvas. Para utilizarlo, el usuario debe activar “Snap a cuadrícula”. |
| 10 | Sección "Acciones" | Gestión del widget | Elimina el widget | Permite eliminar el Panel de Estados del dashboard o pantalla SCADA. Para utilizarlo, el usuario debe seleccionar el widget y pulsar “Eliminar elemento”. |

---

# 💡 Guía de Uso

El widget **Panel de Estados** está diseñado para supervisar múltiples señales o estados industriales desde un único bloque visual organizado.

Se utiliza principalmente para:

- Supervisar estados de equipos
- Visualizar señales ON/OFF
- Mostrar estados de operación
- Centralizar indicadores industriales
- Detectar alarmas visuales
- Agrupar señales relacionadas

## ✅ Cómo configurar correctamente el Panel de Estados

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard o SCADA.
3. Desde el panel de propiedades:
   - Configura el título del panel.
   - Añade estados y etiquetas.
   - Selecciona las variables correspondientes.
   - Ajusta colores y estilos visuales.
   - Personaliza tamaños, padding y filas.
4. Guarda los cambios realizados.

---

[← Volver a Widgets SCADA Básicos](../../widgetsScada_basicos.md)
