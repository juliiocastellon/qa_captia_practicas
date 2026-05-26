# 🖥️ Gestión de Tareas — Vista Kanban

**Objetivo Principal:** Permite al usuario visualizar y gestionar todas las tareas del sistema organizadas por columnas de estado, facilitando el seguimiento del flujo de trabajo y el estado global de las tareas de un vistazo.

---

## 📸 Mapeo de Interfaz

<img width="1546" height="381" alt="image" src="https://github.com/user-attachments/assets/3c4e0f01-f7bf-437c-98a7-6c0b0925fe1c" />

---

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Columna "Pendiente" | Columna de estado | Agrupa tareas pendientes | Muestra todas las tareas en estado Pendiente. El encabezado indica el número de tareas de la columna. Cada tarjeta muestra el título de la tarea, su tipo mediante icono, su prioridad mediante punto de color y la fecha límite, en rojo si está vencida. |
| 2 | Columna "En curso" | Columna de estado | Agrupa tareas en progreso | Muestra todas las tareas en estado En curso. El encabezado indica el número de tareas de la columna. Cada tarjeta muestra el título, tipo, prioridad y fecha límite de la tarea. |
| 3 | Columna "En espera" | Columna de estado | Agrupa tareas en espera | Muestra todas las tareas en estado En espera. El encabezado indica el número de tareas de la columna. Cada tarjeta muestra el título, tipo, prioridad y fecha límite de la tarea. |
| 4 | Columna "Completada" | Columna de estado | Agrupa tareas completadas | Muestra todas las tareas finalizadas. Cuando no hay tareas en este estado, muestra el mensaje "Sin tareas" junto a un icono ilustrativo. |
| 5 | Columna "Cancelada" | Columna de estado | Agrupa tareas canceladas | Muestra todas las tareas canceladas. El encabezado indica el número de tareas de la columna. Cada tarjeta muestra el título, tipo e icono de estado correspondiente. |
| 6 | Selector de vista "Lista / Kanban" | Botones de alternancia | Cambia el modo de visualización | Permite alternar entre la vista en formato Lista y la vista en formato Kanban. Para utilizarlo, el usuario debe pulsar el botón correspondiente al modo de visualización deseado. El botón activo aparece resaltado. |
| 7 | Botón "+ Nueva tarea" | CTA Principal | Abre formulario de creación | Permite iniciar el proceso de creación de una nueva tarea. Para utilizarlo, el usuario debe pulsar el botón y completar los campos del formulario que se mostrará a continuación. |

---

## 💡 Guía de Uso

La vista **Kanban de Tareas** organiza visualmente todas las tareas en columnas según su estado, permitiendo identificar de forma inmediata la distribución del trabajo y detectar cuellos de botella o tareas vencidas.

Se utiliza principalmente para:

- Visualizar el flujo de trabajo global por estados
- Identificar rápidamente tareas vencidas o con prioridad urgente
- Hacer seguimiento del progreso de las tareas
- Detectar columnas sobrecargadas o sin actividad
- Crear nuevas tareas desde el acceso directo
- Alternar a la vista Lista para opciones de filtrado avanzado

### ✅ Cómo utilizar esta vista correctamente

1. Accede a la sección de Tareas desde el menú principal.
2. Pulsa el botón "Kanban" en el selector de vista para activar este modo.
3. Consulta cada columna para conocer el estado y volumen de tareas.
4. Identifica las tarjetas con fecha en rojo para detectar tareas vencidas.
5. Pulsa sobre una tarjeta para acceder al detalle o editar la tarea.
6. Pulsa "+ Nueva tarea" para crear una nueva tarea desde cero.
7. Alterna a la vista Lista si necesitas filtrar o buscar tareas específicas.
