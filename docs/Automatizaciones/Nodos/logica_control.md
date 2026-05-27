# 🧠 Lógica y Control · Nodos de Automatización

**Objetivo Principal:** Permite al usuario acceder a nodos orientados a lógica condicional, cálculos y control temporal dentro de workflows de automatización.

---

# 📸 Mapeo de Interfaz

<img width="398" height="583" alt="image" src="https://github.com/user-attachments/assets/f15e1158-7425-430d-9344-58c34d137622" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Configuración | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Categoría "Lógica y Control" | Categoría de nodos | Expande/colapsa el bloque | — | Permite visualizar los nodos relacionados con lógica de automatización, cálculos y control temporal. Para utilizarlo, el usuario debe expandir la categoría y seleccionar el nodo que quiera añadir al workflow. |
| 1.1 | Nodo "Condición" | Nodo lógico | Inserta condición lógica | [Configuración](./Configuración/Condicion.md) | Permite bifurcar el flujo del workflow según reglas o condiciones configuradas. Para utilizarlo, el usuario debe arrastrar el nodo al canvas y definir las condiciones que determinarán cada salida. |
| 1.2 | Nodo "Fórmula" | Nodo de cálculo | Inserta cálculo lógico | [Configuración](./Configuración/Formula.md) | Permite realizar operaciones y cálculos utilizando variables y placeholders dentro del workflow. Para utilizarlo, el usuario debe añadir el nodo y configurar la fórmula que desea ejecutar. |
| 1.3 | Nodo "TON (On-Delay)" | Nodo temporizador | Inserta temporizador de activación | [Configuración](./Configuración/TON.md) | Permite retrasar la activación de una salida durante un tiempo determinado. Para utilizarlo, el usuario debe definir el tiempo de retardo y conectar el nodo dentro de la lógica del workflow. |
| 1.4 | Nodo "TOF (Off-Delay)" | Nodo temporizador | Inserta temporizador de desactivación | [Configuración](./Configuración/TOF.md) | Permite retrasar la desactivación de una salida durante un tiempo determinado. Para utilizarlo, el usuario debe configurar el tiempo de retardo antes de la desconexión. |
| 1.5 | Nodo "TP (Pulso)" | Nodo de pulso | Inserta generador de pulso | [Configuración](./Configuración/Pulso.md) | Permite activar una salida temporalmente durante un periodo definido. Para utilizarlo, el usuario debe configurar la duración del pulso y conectarlo dentro del workflow. |

---

# 💡 Guía de Uso

La categoría **Lógica y Control** está diseñada para construir la lógica principal de automatizaciones dentro del editor de workflows.

Se utiliza principalmente para:

- Crear condiciones
- Gestionar bifurcaciones
- Aplicar temporizadores
- Realizar cálculos
- Controlar activaciones
- Automatizar comportamientos
- Construir lógica operativa

## ✅ Cómo utilizar correctamente los nodos de Lógica y Control

1. Expande la categoría “Lógica y Control”.
2. Arrastra el nodo deseado al canvas.
3. Conecta el nodo con otros elementos del workflow.
4. Configura parámetros y comportamiento desde las propiedades del nodo.
5. Guarda los cambios realizados.

---

[← Volver a Nodos del Workflow](../Nodos_Workflow.md)
