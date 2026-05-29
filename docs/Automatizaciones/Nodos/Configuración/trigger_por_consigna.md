# 🖥️ Trigger por Consigna — Configuración

**Objetivo Principal:** Permite al usuario configurar el disparo automático de un workflow cuando el sistema SCADA modifica una consigna o setpoint de un asset concreto.

## 📸 Mapeo de Interfaz

<img width="603" height="506" alt="image" src="https://github.com/user-attachments/assets/7ea8a3ea-cde9-4c69-9b06-459a697f5fcb" />


## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo del trigger. Por defecto muestra "Trigger por consigna". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito del trigger. Redimensionable. Por defecto muestra "Cuando SCADA modifica una consigna/setpoint". |
| 3 | Campo "Asset ID (obligatorio)" | Input texto | Identifica el asset a monitorear | Campo obligatorio. Acepta el identificador del asset cuya consigna se quiere vigilar. Placeholder de ejemplo: `M01, APP, bomba_01`. |
| 4 | Campo "Variable ID (opcional)" | Input texto | Filtra por una variable específica del asset | Campo opcional. Permite acotar el trigger a una variable concreta del asset. Placeholder de ejemplo: `global__presion_setpoint`. Si se deja vacío, el trigger reacciona a cualquier cambio de consigna del asset. |
| 5 | Selector "Origen" | Dropdown | Define el sistema origen de la modificación | Permite seleccionar de qué sistema proviene el cambio de consigna. Por defecto: `SCADA`. |
| 6 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 7 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda todos los parámetros configurados y cierra el panel. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre el **Trigger por consigna** en el canvas del workflow.
2. Edita el **Nombre del nodo** si quieres identificarlo con un nombre personalizado.
3. Añade opcionalmente una **Descripción** para documentar el propósito del trigger.
4. Introduce el **Asset ID** del equipo o asset cuya consigna quieres monitorear (campo obligatorio). Ej: `M01, APP, bomba_01`.
5. Opcionalmente, especifica el **Variable ID** para limitar el trigger a una consigna concreta del asset. Si se deja vacío, cualquier cambio de setpoint lo activará.
6. Selecciona el **Origen** del cambio de consigna (por defecto `SCADA`).
7. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.

[← Volver a Nodos del Workflow](../nodos.md)
