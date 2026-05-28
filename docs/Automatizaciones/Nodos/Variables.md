# 🟣 Variables · Nodos de Automatización

**Objetivo Principal:** Permite al usuario acceder a nodos relacionados con gestión de variables, referencias y valores utilizados dentro de workflows de automatización.

---

# 📸 Mapeo de Interfaz

<img width="291" height="318" alt="image" src="https://github.com/user-attachments/assets/c5c6eafc-a72c-4e19-a977-cc8664817395" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Configuración | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Categoría "Variables" | Categoría de nodos | Expande/colapsa el bloque | — | Permite visualizar los nodos relacionados con gestión de variables y datos dentro del workflow. Para utilizarlo, el usuario debe expandir la categoría y seleccionar el nodo que quiera añadir al canvas. |
| 1.1 | Nodo "Escribir parámetro" | Nodo de acción | Inserta escritura de variables | [Configuración](./Configuración/Escribir.md) | Permite escribir valores dentro de variables, parámetros o salidas utilizadas por el workflow. Para utilizarlo, el usuario debe arrastrar el nodo al canvas y configurar la variable destino correspondiente. |
| 1.2 | Nodo "Variable" | Nodo de referencia | Inserta referencia de variable | [Configuración](./Configuración/Variable.md) | Permite utilizar referencias a variables globales, estáticas o de entrada dentro del workflow. Para utilizarlo, el usuario debe seleccionar la variable que quiera utilizar dentro de la automatización. |
| 1.3 | Nodo "Constante" | Nodo de valor fijo | Inserta valor constante | [Configuración](./Configuración/Constante.md) | Permite utilizar valores fijos dentro del workflow, como números, textos o booleanos. Para utilizarlo, el usuario debe introducir el valor constante que quiera utilizar dentro de la automatización. |

---

# 💡 Guía de Uso

La categoría **Variables** está diseñada para gestionar información y valores utilizados dentro de workflows de automatización.

Se utiliza principalmente para:

- Gestionar variables
- Compartir datos
- Utilizar referencias
- Configurar constantes
- Actualizar valores
- Organizar información
- Automatizar comportamientos

## ✅ Cómo utilizar correctamente los nodos de Variables

1. Expande la categoría “Variables”.
2. Arrastra el nodo deseado al canvas.
3. Configura variables, referencias o constantes según sea necesario.
4. Conecta el nodo con el resto del workflow.
5. Guarda los cambios realizados.

---

[← Volver a Nodos del Workflow](../Automatizaciones.md)
