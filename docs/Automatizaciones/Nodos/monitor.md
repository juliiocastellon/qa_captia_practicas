# 🖥️ Monitor

**Objetivo Principal:** Permite al usuario añadir nodos de monitorización al workflow para visualizar en tiempo real el valor actual de una conexión o variable de proceso.

## 📸 Mapeo de Interfaz

<img width="733" height="337" alt="image" src="https://github.com/user-attachments/assets/d5b9e5f4-ae17-4030-8e54-9aa51c139906" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Configuración | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Sección "Monitor" (cabecera) | Contenedor / Acordeón | Expande/colapsa la lista de nodos de monitorización | - | Agrupa el nodo de monitorización disponible bajo un único bloque colapsable. Muestra el contador de items (1). |
| 2 | Visualizador | Opción seleccionable | Abre configuración del nodo visualizador | - | Muestra el valor actual de una conexión o variable de proceso en tiempo real dentro del workflow. |

## 💡 Guía de Uso

1. Accede a la sección **Monitor** dentro del editor de workflow.
2. Selecciona el nodo **Visualizador** para añadirlo al canvas.
3. Configura los parámetros específicos del nodo para indicar qué conexión o variable debe mostrar.
4. El nodo mostrará el valor actual de la conexión durante la ejecución del workflow.
