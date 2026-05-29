# 🖥️ Trigger Programado — Configuración

**Objetivo Principal:** Permite al usuario configurar la ejecución automática de un workflow en horarios recurrentes mediante una expresión cron y zona horaria.

## 📸 Mapeo de Interfaz

<img width="737" height="677" alt="image" src="https://github.com/user-attachments/assets/b5e22cb6-26a8-4140-b811-70b389a3287c" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo del trigger. Por defecto muestra "Trigger programado". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito del trigger. Redimensionable. Por defecto muestra "Ejecuta en horarios específicos (cron)". |
| 3 | Campo "Expresión Cron" | Input texto | Define la frecuencia y horario de ejecución | Acepta una expresión cron estándar (5 campos). Incluye texto de ayuda con ejemplo: "A las 09:00, de lunes a viernes". Placeholder por defecto: `0 9 * * 1-5`. |
| 4 | Selector "Zona horaria" | Dropdown | Establece el contexto horario para interpretar el cron | Permite seleccionar la zona horaria en la que se ejecutará el cron. Por defecto: Madrid (España). Incluye texto informativo: "La hora del cron se interpretará en esta zona horaria". |
| 5 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 6 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda todos los parámetros configurados y cierra el panel. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre el **Trigger programado** en el canvas del workflow.
2. Edita el **Nombre del nodo** si quieres identificarlo con un nombre personalizado.
3. Añade opcionalmente una **Descripción** para documentar el propósito del trigger.
4. Introduce la **Expresión Cron** que define cuándo debe ejecutarse el workflow. Ejemplo: `0 9 * * 1-5` ejecuta de lunes a viernes a las 09:00.
5. Selecciona la **Zona horaria** correcta para que el cron se interprete en el huso horario esperado.
6. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.


[← Volver a Nodos del Workflow](../triggers.md)
