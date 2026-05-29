# 🖥️ Acción: Generar Informe — Configuración

**Objetivo Principal:** Permite al usuario configurar la generación automática de un informe PDF a partir de una plantilla, con un rango de tiempo y parámetros personalizables.

## 📸 Mapeo de Interfaz

<img width="600" height="682" alt="image" src="https://github.com/user-attachments/assets/3584592e-bf7f-42bc-83bf-e23d94e7561a" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo de la acción. Por defecto muestra "Generar informe". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito de la acción. Redimensionable. Por defecto muestra "Crea un informe PDF desde plantilla". |
| 3 | Selector "Plantilla de informe" | Dropdown | Selecciona la plantilla base para generar el PDF | Lista desplegable con las plantillas de informe disponibles en el sistema. Muestra placeholder "Selecciona una plantilla...". |
| 4 | Selector "Período" | Dropdown | Define el rango de tiempo de los datos del informe | Establece el intervalo temporal sobre el que se generará el informe. Por defecto: "Últimos 7 días". Si se deja vacío, se usan los filtros por defecto de la plantilla. |
| 5 | Campo "Parámetros (JSON)" | Textarea (JSON) | Permite pasar parámetros adicionales a la plantilla | Acepta un objeto JSON con parámetros extra para personalizar la plantilla de informe. Por defecto muestra `{}`. |
| 6 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 7 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda todos los parámetros configurados y cierra el panel. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Generar informe** en el canvas del workflow.
2. Edita el **Nombre del nodo** y la **Descripción** si lo necesitas.
3. Selecciona la **Plantilla de informe** que se usará como base para generar el PDF.
4. Define el **Período** de datos que debe cubrir el informe (ej: "Últimos 7 días"). Si se deja vacío, se aplicarán los filtros por defecto de la plantilla.
5. Si la plantilla requiere parámetros adicionales, introdúcelos en el campo **Parámetros (JSON)** como un objeto JSON válido.
6. Coloca este nodo **antes** de cualquier nodo de envío (email, WhatsApp) si necesitas adjuntar el informe generado.
7. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.

   [← Volver a Nodos del Workflow](../nodos.md)
