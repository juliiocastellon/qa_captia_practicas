# 🖥️ Acción: Escribir Variable Global Interna — Configuración

**Objetivo Principal:** Permite al usuario buscar y seleccionar una variable global interna del proceso para escribir un valor en ella desde el workflow.

## 📸 Mapeo de Interfaz

<img width="667" height="487" alt="image" src="https://github.com/user-attachments/assets/d211e6c4-2bfe-4df3-a509-af2da7d226c1" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Buscar por nombre o clave técnica" | Input búsqueda | Filtra la lista de variables globales disponibles | Permite localizar una variable escribiendo su nombre o clave técnica. Muestra el contador de resultados disponibles (ej: "0 variables globales disponibles"). |
| 2 | Área de resultados | Lista (read-only) | Muestra las variables que coinciden con la búsqueda | Presenta las variables globales encontradas. Cuando no hay variables activas muestra el mensaje "No hay variables globales activas. Crea una variable GLOBAL desde Variables." |
| 3 | Campo de selección activa | Bloque informativo (read-only) | Refleja la variable seleccionada de la lista | Muestra la variable escogida por el usuario. Mientras no hay selección muestra el placeholder "Selecciona una variable global de la lista". |
| 4 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 5 | Botón "Guardar" | CTA Principal | Persiste la variable seleccionada en el nodo | Guarda la variable global elegida y cierra el panel. Deshabilitado hasta que se selecciona una variable. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Escribir variable global interna** en el canvas del workflow.
2. Usa el campo de búsqueda para localizar la variable destino por su **nombre** o **clave técnica**.
3. Selecciona la variable deseada de la lista — aparecerá confirmada en el campo de selección activa.
4. Si no aparecen variables disponibles, es necesario crear primero una variable de tipo GLOBAL desde el módulo **Variables**.
5. Pulsa **Guardar** para confirmar, o **Cancelar** para descartar.

   [← Volver a Nodos del Workflow](../nodos.md)
