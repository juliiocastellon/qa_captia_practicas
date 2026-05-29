# 🖥️ Acción: Enviar WhatsApp — Configuración

**Objetivo Principal:** Permite al usuario configurar el envío automático de un mensaje de WhatsApp a un número de teléfono definido como respuesta a un trigger activado.

## 📸 Mapeo de Interfaz

<img width="462" height="575" alt="image" src="https://github.com/user-attachments/assets/1cb1ac8c-77a7-407f-9354-6d90992c557a" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo de la acción. Por defecto muestra "Enviar WhatsApp". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito de la acción. Por defecto muestra "Envía un mensaje de WhatsApp". |
| 3 | Campo "Número de teléfono *" | Input texto | Define el destinatario del mensaje | Campo obligatorio. Acepta formato internacional con prefijo (ej: `+34` para España). Admite variables dinámicas con la sintaxis `{{variable}}` para números dinámicos. |
| 4 | Campo "Mensaje *" | Textarea + Insertar variable | Define el contenido del mensaje de WhatsApp | Campo obligatorio. Incluye aviso de plantilla ("Alerta de proceso") y admite variables del workflow: `{{trigger.variable_name}}`, `{{trigger.value}}`, `{{trigger.unit}}`, `{{trigger.threshold}}`, `{{workflow.name}}`. Incluye nota informativa: los mensajes requieren que el destinatario haya iniciado conversación en las últimas 24h o usar una plantilla aprobada por WhatsApp. |
| 5 | Sección "Archivos adjuntos" | Bloque informativo | Informa sobre cómo adjuntar archivos | Indica que para adjuntar archivos es necesario añadir previamente un nodo "Generar informe" antes de este nodo en el workflow. |
| 6 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 7 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda todos los parámetros configurados y cierra el panel. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Enviar WhatsApp** en el canvas del workflow.
2. Edita el **Nombre del nodo** y la **Descripción** si lo necesitas.
3. Introduce el **Número de teléfono** destinatario en formato internacional (ej: `+34612345678`). Puedes usar `{{variable}}` para números dinámicos.
4. Redacta el **Mensaje** que se enviará. Usa el botón "Insertar variable" para incluir datos del workflow como el valor actual, el umbral o el nombre de la variable.
5. Ten en cuenta la restricción de WhatsApp: el destinatario debe haber iniciado conversación en las últimas 24h, o el mensaje debe basarse en una plantilla aprobada por WhatsApp.
6. Si necesitas adjuntar archivos, añade un nodo **Generar informe** antes de este nodo en el workflow.
7. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.

[← Volver a Acciones](../Acciones.md)
