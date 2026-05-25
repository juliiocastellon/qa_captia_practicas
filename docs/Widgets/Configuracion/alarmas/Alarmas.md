# 🚨 Banner de Alarmas · Propiedades del Widget

**Objetivo Principal:** Permite al usuario configurar el widget **Banner de Alarmas**, utilizado para visualizar alarmas activas y estados críticos dentro de dashboards y pantallas SCADA.

---

# 📸 Mapeo de Interfaz

<img width="912" height="592" alt="image" src="https://github.com/user-attachments/assets/f5a0ba57-2ebb-4c0b-b197-5e5ce7b8fcbc" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Elemento" | Configuración del widget | Gestiona el estado del widget | Permite visualizar el tipo de widget seleccionado y bloquearlo para evitar moverlo accidentalmente dentro del dashboard o SCADA. Para utilizarlo, el usuario debe pulsar el botón “Bloquear” cuando quiera fijar definitivamente su posición. |
| 2 | Sección "Capas" | Organización visual | Gestiona superposición | Permite controlar cómo se posiciona el Banner de Alarmas respecto a otros widgets del canvas. Para utilizarlo, el usuario puede modificar el Z-Index manualmente o utilizar “Traer al frente” y “Enviar atrás” para reorganizar visualmente el widget. |
| 3 | Sección "General" | Configuración básica | Personaliza el widget | Permite modificar el título y comportamiento general del Banner de Alarmas. Para utilizarlo, el usuario puede definir el número máximo de alarmas visibles, activar el timestamp para mostrar fecha y hora o habilitar el modo compacto para reducir espacio ocupado dentro del dashboard. |
| 4 | Sección "Alarmas (Tags)" | Configuración de datos | Configura alarmas monitorizadas | Permite seleccionar las variables booleanas que actuarán como alarmas dentro del widget. Para utilizarlo, el usuario debe pulsar “Añadir variable” y seleccionar las señales que quiera supervisar visualmente. |
| 4.1 | Configuración "Tags de alarmas" | Selector de variables | Añade alarmas al banner | Permite asociar variables booleanas al Banner de Alarmas. Para utilizarlo, el usuario debe añadir una o varias variables que representen estados de alarma activos o inactivos. |
| 5 | Sección "Editor" | Configuración del canvas | Ajusta comportamiento de edición | Permite activar el ajuste automático a cuadrícula mientras se mueve el Banner de Alarmas dentro del canvas. Para utilizarlo, el usuario debe activar “Snap a cuadrícula” si quiere alinear widgets automáticamente. |
| 6 | Sección "Acciones" | Gestión del widget | Elimina el widget | Permite eliminar el Banner de Alarmas del dashboard o pantalla SCADA. Para utilizarlo, el usuario debe seleccionar el widget y pulsar “Eliminar elemento”. |

---

# 💡 Guía de Uso

El widget **Banner de Alarmas** está diseñado para mostrar visualmente alarmas activas y estados críticos dentro de dashboards y pantallas SCADA.

Se utiliza principalmente para:

- Visualizar alarmas activas
- Supervisar estados críticos
- Mostrar incidencias en tiempo real
- Detectar eventos importantes
- Centralizar avisos visuales
- Facilitar supervisión operativa
- Mejorar la monitorización visual

## ✅ Cómo configurar correctamente el widget Banner de Alarmas

1. Arrastra el widget al canvas.
2. Selecciona el widget dentro del dashboard o SCADA.
3. Desde el panel de propiedades:
   - Configura el título.
   - Define el número máximo de alarmas visibles.
   - Añade variables de alarma.
   - Ajusta opciones visuales.
   - Activa timestamps o modo compacto si es necesario.
4. Guarda los cambios realizados.

---

[← Volver a Alarmas](../../widgetsScada_alarmas.md)
