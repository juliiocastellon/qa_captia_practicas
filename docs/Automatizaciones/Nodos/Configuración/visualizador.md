# 🖥️ Monitor: Visualizador — Configuración

**Objetivo Principal:** Permite al usuario configurar un nodo de monitorización que muestra el valor actual de una conexión o variable de proceso durante la ejecución del workflow.

## 📸 Mapeo de Interfaz

<img width="882" height="596" alt="image" src="https://github.com/user-attachments/assets/f5ad2916-e669-462b-bdd5-d580f6fbd523" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo del nodo. Por defecto muestra "Visualizador". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito del nodo. Redimensionable. Por defecto muestra "Muestra el valor actual de una conexion". |
| 3 | Sección "Configuración específica" | Contenedor | — | Sección reservada para los parámetros específicos del visualizador. Aparece vacía en la captura — pendiente de implementación o carga de contenido. |
| 4 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 5 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda todos los parámetros configurados y cierra el panel. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Visualizador** en el canvas del workflow.
2. Edita el **Nombre del nodo** y la **Descripción** si lo necesitas.
3. Completa los parámetros de la sección **Configuración específica** para definir qué conexión o variable debe monitorizar el nodo.
4. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.

   [← Volver a Nodos del Workflow](../nodos.md)
