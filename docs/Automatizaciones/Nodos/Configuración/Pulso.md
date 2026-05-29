# ⏱️ TP (Pulso) · Propiedades del Nodo

**Objetivo Principal:** Permite al usuario configurar un nodo de tipo **TP (Pulso)**, utilizado para generar una activación temporal durante un tiempo determinado dentro de workflows de automatización.

---

# 📸 Mapeo de Interfaz

<img width="606" height="538" alt="image" src="https://github.com/user-attachments/assets/14476771-bde0-4f4d-8d8b-f0f92f614068" />

---

# 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Nodo "TP - Pulso temporizado" | Nodo temporizador | Configura pulso temporal | Permite generar una activación temporal durante un tiempo configurado dentro del workflow. |
| 1.1 | Campo "Nombre" | Campo de texto | Renombra el nodo | Permite definir el nombre identificativo del nodo temporizador dentro de la automatización. Para utilizarlo, el usuario debe escribir el nombre deseado para identificar el nodo fácilmente. |
| 1.2 | Campo "PT (Preset Time)" | Campo numérico | Configura duración del pulso | Permite definir el tiempo durante el cual permanecerá activa la salida del nodo. Para utilizarlo, el usuario debe introducir el tiempo en segundos o fracciones de segundo. |
| 1.3 | Campo "Variable de salida (Q)" | Campo de salida | Configura variable de resultado | Permite definir la variable que almacenará el resultado del pulso generado por el nodo. Para utilizarlo, el usuario debe introducir o seleccionar la variable de salida que utilizará posteriormente dentro del workflow. |

---

# 💡 Guía de Uso

El nodo **TP (Pulso)** está diseñado para generar activaciones temporales dentro de workflows de automatización.

Se utiliza principalmente para:

- Generar pulsos temporales
- Controlar activaciones
- Gestionar tiempos
- Automatizar secuencias
- Controlar procesos
- Crear comportamientos temporales
- Organizar lógica operativa

## ✅ Cómo configurar correctamente el nodo TP (Pulso)

1. Arrastra el nodo al canvas del workflow.
2. Configura el nombre del nodo.
3. Define la duración del pulso en el campo “PT”.
4. Configura la variable de salida si es necesario.
5. Guarda los cambios realizados.
6. Conecta el nodo con el resto del workflow.

---

[← Volver a Nodos del Workflow](../logica_control.md)
