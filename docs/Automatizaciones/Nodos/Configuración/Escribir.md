# 📝 Escribir parámetro · Propiedades del Nodo

**Objetivo Principal:** Permite al usuario configurar un nodo de tipo **Escribir parámetro**, utilizado para escribir valores dentro de variables, salidas o parámetros globales de un workflow.

---

# 📸 Mapeo de Interfaz

<img width="593" height="566" alt="image" src="https://github.com/user-attachments/assets/b1e7e28a-4605-4117-8f4d-8ccd9ad0dd5d" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Nodo "Escribir parámetro" | Nodo de acción | Configura escritura de valores | Permite escribir valores dentro de variables, parámetros o salidas utilizadas por el workflow. |
| 1.1 | Sección "Configuración básica" | Configuración general | Configura información básica | Permite definir la información principal identificativa del nodo. |
| 1.1.1 | Campo "Nombre del nodo" | Campo de texto | Renombra el nodo | Permite asignar un nombre identificativo al nodo dentro del workflow. Para utilizarlo, el usuario debe escribir el nombre deseado en el campo correspondiente. |
| 1.2 | Campo "Descripción" | Campo de texto | Añade descripción | Permite añadir información descriptiva sobre el comportamiento o propósito del nodo. Para utilizarlo, el usuario debe escribir el texto descriptivo dentro del campo correspondiente. |
| 1.3 | Sección "Configuración específica" | Configuración de escritura | Configura variable destino | Permite definir dónde se escribirá el valor generado o recibido por el workflow. Para utilizarlo, el usuario debe seleccionar la variable destino o introducir una clave global donde se almacenará el valor. |

---

# 💡 Guía de Uso

El nodo **Escribir parámetro** está diseñado para almacenar y actualizar valores dentro de workflows de automatización.

Se utiliza principalmente para:

- Escribir valores
- Actualizar variables
- Gestionar parámetros
- Compartir información
- Controlar estados
- Automatizar procesos
- Gestionar datos internos

## ✅ Cómo configurar correctamente el nodo Escribir parámetro

1. Arrastra el nodo al canvas del workflow.
2. Configura el nombre y descripción del nodo.
3. Selecciona la variable o parámetro destino.
4. Conecta el nodo con el resto del workflow.
5. Guarda los cambios realizados.

---

[← Volver a Variables](../Nodos_Workflow.md)
