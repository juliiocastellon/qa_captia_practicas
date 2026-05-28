# 🖥️ Global: Leer Variable Global Interna — Configuración

**Objetivo Principal:** Permite al usuario buscar y seleccionar una variable global interna del proceso para leer su valor dentro del workflow.

## 📸 Mapeo de Interfaz

<img width="700" height="497" alt="image" src="https://github.com/user-attachments/assets/47061476-17f0-4054-89c2-f33e0d61a0c0" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Campo "Buscar por nombre o clave técnica" | Input búsqueda | Filtra la lista de variables globales disponibles | Permite localizar una variable escribiendo su nombre o clave técnica. Muestra el contador de resultados disponibles (ej: "0 variables disponibles"). |
| 2 | Área de resultados | Lista (read-only) | Muestra las variables que coinciden con la búsqueda | Presenta las variables globales encontradas. Cuando no hay resultados muestra el mensaje "No se encontraron variables globales". |
| 3 | Campo de selección activa | Bloque informativo (read-only) | Refleja la variable seleccionada de la lista | Muestra la variable escogida por el usuario. Mientras no hay selección muestra el placeholder "Selecciona una variable de la lista". |
| 4 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 5 | Botón "Guardar" | CTA Principal | Persiste la variable seleccionada en el nodo | Guarda la variable global elegida y cierra el panel. Deshabilitado hasta que se selecciona una variable. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Leer variable global interna** en el canvas del workflow.
2. Usa el campo de búsqueda para localizar la variable por su **nombre** o **clave técnica**.
3. Selecciona la variable deseada de la lista de resultados — aparecerá confirmada en el campo de selección activa.
4. Pulsa **Guardar** para confirmar, o **Cancelar** para descartar.
