# ⏱️ TOF (Off-Delay) · Propiedades del Nodo

**Objetivo Principal:** Permite al usuario configurar un nodo de tipo **TOF (Off-Delay)**, utilizado para retrasar la desactivación de una salida durante un tiempo determinado dentro de workflows de automatización.

---

# 📸 Mapeo de Interfaz

<img width="618" height="537" alt="image" src="https://github.com/user-attachments/assets/48a34a69-cc95-4f41-9b55-6e57d7cacfe6" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Nodo "TOF - Retardo a la desconexión" | Nodo temporizador | Configura temporizador de desactivación | Permite retrasar la desactivación de una salida durante un tiempo configurado dentro del workflow. |
| 1.1 | Campo "Nombre" | Campo de texto | Renombra el nodo | Permite definir el nombre identificativo del nodo temporizador dentro de la automatización. Para utilizarlo, el usuario debe escribir el nombre deseado para identificar el nodo fácilmente. |
| 1.2 | Campo "PT (Preset Time)" | Campo numérico | Configura tiempo de retardo | Permite definir el tiempo que deberá transcurrir antes de desactivar la salida del nodo. Para utilizarlo, el usuario debe introducir el tiempo en segundos o fracciones de segundo. |
| 1.3 | Campo "Variable de salida (Q)" | Campo de salida | Configura variable de resultado | Permite definir la variable que almacenará el resultado de salida del temporizador. Para utilizarlo, el usuario debe introducir o seleccionar la variable de salida que utilizará posteriormente dentro del workflow. |

---

# 💡 Guía de Uso

El nodo **TOF (Off-Delay)** está diseñado para aplicar retardos temporales antes de desactivar acciones dentro de workflows de automatización.

Se utiliza principalmente para:

- Aplicar retardos
- Controlar desactivaciones
- Gestionar tiempos
- Automatizar secuencias
- Controlar procesos
- Crear comportamientos temporales
- Organizar lógica operativa

## ✅ Cómo configurar correctamente el nodo TOF (Off-Delay)

1. Arrastra el nodo al canvas del workflow.
2. Configura el nombre del nodo.
3. Define el tiempo de retardo en el campo “PT”.
4. Configura la variable de salida si es necesario.
5. Guarda los cambios realizados.
6. Conecta el nodo con el resto del workflow.

---

[← Volver a Nodos del Workflow](../logica_control.md)
