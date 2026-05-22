# 🧭 Botón de Navegación · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Botón de Navegación**, utilizado para cambiar rápidamente entre distintas vistas, dashboards o pantallas SCADA dentro de la plataforma.

---

# 📸 Mapeo de Interfaz

<img width="1260" height="591" alt="image" src="https://github.com/user-attachments/assets/01f3b938-3a2f-478a-b341-0fc221256e4c" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Elemento" | Configuración del widget | Gestiona el estado del widget | Permite visualizar el tipo de widget seleccionado y bloquearlo para evitar moverlo accidentalmente dentro del dashboard o SCADA. Para utilizarlo, el usuario debe pulsar “Bloquear” cuando quiera fijar definitivamente su posición. |
| 2 | Sección "Capas" | Organización visual | Gestiona superposición | Permite controlar cómo se posiciona el Botón de Navegación respecto a otros widgets del canvas. Para utilizarlo, el usuario puede modificar el Z-Index manualmente o utilizar “Traer al frente” y “Enviar atrás”. |
| 3 | Sección "General" | Configuración básica | Personaliza el botón | Permite modificar el texto visible del botón. Para utilizarlo, el usuario debe escribir el nombre que quiera mostrar, como por ejemplo “Ir a Producción” o “Abrir SCADA”. |
| 4 | Sección "Navegación" | Configuración de destino | Configura navegación | Permite seleccionar la vista o pantalla a la que navegará el botón. Para utilizarlo, el usuario debe desplegar “Vista destino” y seleccionar la pantalla deseada. |
| 5 | Sección "Estilo" | Configuración visual | Personaliza apariencia | Permite modificar el diseño visual completo del botón de navegación. Para utilizarlo, el usuario puede configurar colores, tipografía, bordes y efectos hover. |
| 5.1 | Subsección "Botón" | Configuración visual | Ajusta apariencia principal | Permite modificar el color de fondo, radio de esquinas, paddings y efectos hover del botón. Para utilizarlo, el usuario debe seleccionar colores y ajustar sliders hasta conseguir el diseño deseado. |
| 5.2 | Subsección "Tipografía" | Configuración textual | Ajusta estilos de texto | Permite modificar el tamaño y color del texto mostrado dentro del botón. Para utilizarlo, el usuario debe mover el slider de tamaño y seleccionar el color deseado. |
| 5.3 | Subsección "Borde" | Configuración visual | Ajusta bordes | Permite configurar el color y grosor del borde del botón. Para utilizarlo, el usuario debe seleccionar el color y ajustar el grosor mediante el selector correspondiente. |
| 6 | Sección "Editor" | Configuración del canvas | Ajusta comportamiento de edición | Permite activar el ajuste automático a cuadrícula mientras se mueve el botón dentro del canvas. Para utilizarlo, el usuario debe activar “Snap a cuadrícula”. |
| 7 | Sección "Acciones" | Gestión del widget | Elimina el widget | Permite eliminar el Botón de Navegación del dashboard o pantalla SCADA. Para utilizarlo, el usuario debe seleccionar el widget y pulsar “Eliminar elemento”. |

---

# 💡 Guía de Uso

El widget **Botón de Navegación** está diseñado para facilitar la navegación entre distintas pantallas SCADA y dashboards dentro de la plataforma.

Se utiliza principalmente para:

- Cambiar entre vistas SCADA
- Navegar entre dashboards
- Crear menús de navegación
- Acceder rápidamente a secciones importantes
- Mejorar la experiencia del operador
- Organizar flujos de navegación industrial

## ✅ Cómo configurar correctamente el Botón de Navegación

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard o SCADA.
3. Desde el panel de propiedades:
   - Configura el texto del botón.
   - Selecciona la vista de destino.
   - Ajusta colores y estilos visuales.
   - Configura tipografía y bordes.
   - Activa efectos hover si es necesario.
4. Guarda los cambios realizados.

---

[← Volver a Widgets SCADA Básicos](../widgetsScada_basicos.md)
