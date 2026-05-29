# 🖥️ Acción: Crear Tarea — Configuración

**Objetivo Principal:** Permite al usuario configurar la creación automática de una tarea en el sistema GMAO como respuesta a un trigger activado en el workflow.

## 📸 Mapeo de Interfaz

<img width="762" height="487" alt="image" src="https://github.com/user-attachments/assets/53ebe600-5cab-4e14-b989-32e45d3f557e" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo de la acción. Por defecto muestra "Crear tarea". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito de la acción. Redimensionable. Por defecto muestra "Crea una tarea GMAO automaticamente". |
| 3 | Sección "Configuración específica" | Contenedor | — | Sección reservada para los parámetros específicos de creación de tarea en GMAO. Aparece vacía en la captura — pendiente de implementación o carga de contenido. |
| 4 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 5 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda todos los parámetros configurados y cierra el panel. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Crear tarea** en el canvas del workflow.
2. Edita el **Nombre del nodo** y la **Descripción** si lo necesitas.
3. Completa los parámetros de la sección **Configuración específica** para definir los detalles de la tarea que se creará en el GMAO.
4. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.

[← Volver a Acciones](../Acciones.md)
