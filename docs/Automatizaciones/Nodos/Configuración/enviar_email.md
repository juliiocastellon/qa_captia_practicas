# 🖥️ Acción: Enviar Email — Configuración

**Objetivo Principal:** Permite al usuario configurar el envío automático de un correo electrónico como respuesta a un trigger, definiendo destinatarios, contenido y apariencia del mensaje.

## 📸 Mapeo de Interfaz

<img width="917" height="597" alt="image" src="https://github.com/user-attachments/assets/47cedd3e-936a-45f5-bb0a-432bf2dd731f" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo de la acción. Por defecto muestra "Enviar email". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito de la acción. Por defecto muestra "Envía un correo electrónico". |
| 3 | Selector "Tipo de email" | Dropdown | Define la plantilla visual y textos por defecto | Determina el estilo y estructura del email generado. Por defecto: "Notificación general". |
| 4 | Campo "Destinatarios (To) *" | Input texto | Define los receptores principales del email | Campo obligatorio. Acepta múltiples emails separados por comas. Admite variables dinámicas con la sintaxis `{{variable}}`. |
| 5 | Campo "BCC (opcional)" | Input texto | Añade destinatarios en copia oculta | Campo opcional. Permite enviar el email a direcciones adicionales sin que sean visibles para el resto de destinatarios. |
| 6 | Campo "CC (opcional)" | Input texto | Añade destinatarios en copia | Campo opcional. Permite enviar el email a direcciones adicionales visibles para todos los destinatarios. |
| 7 | Campo "Asunto *" | Input texto + Insertar variable | Define el asunto del email | Campo obligatorio. Admite variables dinámicas del workflow mediante el botón "Insertar variable". Por defecto: `Alerta: {{trigger.variable_name}} = {{trigger.value}}`. |
| 8 | Campo "Preheader (opcional)" | Input texto + Insertar variable | Define el texto de previsualización en bandeja de entrada | Texto visible junto al asunto en el cliente de correo (máx. 150 caracteres). Admite variables dinámicas. |
| 9 | Campo "Título principal (Hero)" | Input texto + Insertar variable | Define el título grande de la cabecera del email | Si se deja vacío se usará uno por defecto según el tipo. Admite variables dinámicas. |
| 10 | Campo "Subtítulo (Hero)" | Input texto + Insertar variable | Define el subtítulo de la cabecera del email | Complementa el título principal. Admite variables dinámicas. Ej: `{{trigger.variable_name}}`. |
| 11 | Campo "Texto introductorio" | Textarea + Insertar variable | Define el párrafo inicial tras el saludo | Primer bloque de texto del cuerpo del email. Admite variables dinámicas. |
| 12 | Campo "Contenido principal" | Textarea + Insertar variable | Define el cuerpo principal del email | Bloque de texto extenso del email. Admite variables del workflow como `{{trigger.value}}` o `{{workflow.name}}`. Por defecto incluye plantilla con variable, valor actual y umbral. |
| 13 | Campo "Texto del botón" | Input texto | Define la etiqueta del botón CTA del email | Texto visible en el botón de llamada a la acción incluido en el email. Ej: "Ver detalles". |
| 14 | Campo "URL del botón" | Input texto | Define el destino del botón CTA del email | URL a la que redirige el botón del email. Por defecto apunta a la aplicación. |
| 15 | Sección "Adjuntos" | Bloque informativo | Informa sobre cómo adjuntar archivos | Indica que para adjuntar archivos es necesario añadir previamente un nodo "Generar informe" en el workflow. Incluye aviso de funcionalidad próxima: sugerencia de contenido por IA. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Enviar email** en el canvas del workflow.
2. Edita el **Nombre del nodo** y la **Descripción** si lo necesitas.
3. Selecciona el **Tipo de email** para definir la plantilla visual base.
4. Introduce los **Destinatarios** principales. Puedes usar `{{variable}}` para emails dinámicos.
5. Rellena opcionalmente los campos **CC** y **BCC** para copias visibles u ocultas.
6. Define el **Asunto** del email. Usa el botón "Insertar variable" para incluir datos del workflow.
7. Añade opcionalmente un **Preheader** para el texto de previsualización en bandeja (máx. 150 caracteres).
8. Completa el contenido del email: **Título**, **Subtítulo**, **Texto introductorio** y **Contenido principal**. Todos admiten variables dinámicas.
9. Configura el **botón CTA** con su texto y URL de destino.
10. Si necesitas adjuntar archivos, añade un nodo **Generar informe** antes de este nodo en el workflow.
11. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.

[← Volver a Nodos del Workflow](../logica_control.md)
