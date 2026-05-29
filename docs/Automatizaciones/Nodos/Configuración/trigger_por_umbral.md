# 🖥️ Trigger por Umbral — Configuración

**Objetivo Principal:** Permite al usuario configurar el disparo automático de un workflow cuando una variable monitorizada supera o cumple una condición de umbral definida.

## 📸 Mapeo de Interfaz

<img width="591" height="512" alt="image" src="https://github.com/user-attachments/assets/504c347d-8598-402d-a966-4c59b3164eff" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo del trigger. Por defecto muestra "Trigger por umbral". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito del trigger. Redimensionable. Por defecto muestra "Cuando una variable supera un valor". |
| 3 | Selector "Variable a monitorear" | Dropdown | Selecciona la variable del sistema a vigilar | Lista desplegable para escoger la variable cuyo valor será evaluado continuamente. Muestra placeholder "Selecciona una variable...". |
| 4 | Campos "Operador" + "Umbral" | Dropdown + Input numérico | Define la condición de disparo | Dos campos en línea: **Operador** establece el tipo de comparación (por defecto "> Mayor que") y **Umbral** define el valor numérico límite (por defecto 100). El trigger se activa cuando la variable cumple la condición. |
| 5 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 6 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda todos los parámetros configurados y cierra el panel. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre el **Trigger por umbral** en el canvas del workflow.
2. Edita el **Nombre del nodo** si quieres identificarlo con un nombre personalizado.
3. Añade opcionalmente una **Descripción** para documentar el propósito del trigger.
4. Selecciona la **Variable a monitorear** en el desplegable — será la variable del sistema evaluada continuamente.
5. Define la condición de disparo combinando el **Operador** (ej: `> Mayor que`) y el valor de **Umbral** (ej: `100`).
6. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.


[← Volver a triggers](../triggers.md)
