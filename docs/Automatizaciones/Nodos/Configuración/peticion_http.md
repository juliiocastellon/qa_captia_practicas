# 🖥️ Acción: Petición HTTP — Configuración

**Objetivo Principal:** Permite al usuario configurar una llamada a una API externa o webhook como respuesta automática a un trigger activado en el workflow.

## 📸 Mapeo de Interfaz

<img width="630" height="667" alt="image" src="https://github.com/user-attachments/assets/4f7dbb6e-614f-4ee1-9b02-467d02f09379" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo de la acción. Por defecto muestra "Petición HTTP". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito de la acción. Redimensionable. Por defecto muestra "Llama a una API externa (webhook)". |
| 3 | Campos "Método" + "URL" | Dropdown + Input texto | Define el tipo de petición y el endpoint destino | Dos campos en línea: **Método** selecciona el verbo HTTP (por defecto `GET`) y **URL** define el endpoint al que se realizará la llamada. Placeholder: `https://api.ejemplo.com/webhook`. |
| 4 | Campo "Headers (JSON)" | Textarea (JSON) | Define las cabeceras HTTP de la petición | Acepta un objeto JSON con las cabeceras necesarias para la llamada (ej: autenticación, content-type). Por defecto muestra `{}`. |
| 5 | Campo "Timeout (segundos)" | Input numérico | Define el tiempo máximo de espera de la respuesta | Establece el límite de tiempo en segundos antes de cancelar la petición si no hay respuesta. Rango válido: 1-300 segundos. Por defecto: `30`. |
| 6 | Botón "Probar" | Botón de acción secundaria | Ejecuta la petición HTTP con la configuración actual | Permite verificar que la llamada funciona correctamente antes de guardar el nodo. |
| 7 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 8 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda todos los parámetros configurados y cierra el panel. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Petición HTTP** en el canvas del workflow.
2. Edita el **Nombre del nodo** y la **Descripción** si lo necesitas.
3. Selecciona el **Método** HTTP adecuado (`GET`, `POST`, etc.) e introduce la **URL** del endpoint o webhook destino.
4. Si la API requiere cabeceras específicas (autenticación, tipo de contenido, etc.), introdúcelas en el campo **Headers** como un objeto JSON válido.
5. Ajusta el **Timeout** si el sistema externo puede tardar más de 30 segundos en responder (máx. 300 segundos).
6. Usa el botón **Probar** para verificar que la petición llega correctamente al endpoint antes de guardar.
7. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.
