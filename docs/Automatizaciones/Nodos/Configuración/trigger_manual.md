# 🖥️ Trigger Manual — Configuración

**Objetivo Principal:** Permite al usuario nombrar, describir y guardar la configuración del nodo de trigger manual dentro de un workflow.

## 📸 Mapeo de Interfaz

<img width="872" height="635" alt="Captura de pantalla 2026-05-27 091425" src="https://github.com/user-attachments/assets/124423ca-97b8-47d1-b003-d8c5946b7903" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Nombre del nodo" | Input texto | Actualiza el nombre del nodo en el workflow | Permite personalizar el nombre identificativo del trigger. Por defecto muestra "Trigger manual". |
| 2 | Campo "Descripción (opcional)" | Textarea | Almacena una descripción libre del nodo | Campo opcional para documentar el propósito del trigger. Redimensionable. Por defecto muestra "Ejecuta el workflow manualmente". |
| 3 | Sección "Configuración específica" | Bloque informativo (read-only) | — | Indica al usuario que este trigger se activa mediante el botón "Probar workflow". No tiene parámetros configurables adicionales. |
| 4 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 5 | Botón "Guardar cambios" | CTA Principal | Persiste la configuración del nodo | Guarda el nombre y descripción introducidos y cierra el panel de configuración. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre el **Trigger manual** en el canvas del workflow.
2. Edita el **Nombre del nodo** si quieres identificarlo con un nombre personalizado.
3. Añade opcionalmente una **Descripción** para documentar para qué sirve este trigger en el contexto del workflow.
4. La sección **Configuración específica** es informativa: este trigger no requiere parámetros adicionales, se lanza desde el botón "Probar workflow".
5. Pulsa **Guardar cambios** para confirmar, o **Cancelar** para descartar.
