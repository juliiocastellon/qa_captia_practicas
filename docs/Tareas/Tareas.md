# 🖥️ Gestión de Tareas — Vista Lista

**Objetivo Principal:** Permite al usuario consultar, filtrar y gestionar todas las tareas del sistema mediante una vista en formato lista con opciones de búsqueda, filtrado por estado, prioridad y tipo, y acceso rápido a la creación de nuevas tareas.

---

## 📸 Mapeo de Interfaz

<img width="1626" height="453" alt="image" src="https://github.com/user-attachments/assets/b8321137-014e-4d90-a98b-a84e168c67ab" />

---

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1.1 | Buscador "Buscar tareas…" | Campo de búsqueda | Filtra el listado en tiempo real | Permite localizar tareas escribiendo texto libre. El listado se filtra automáticamente mostrando solo las tareas cuyo título coincide con el término introducido. |
| 1.2 | Filtro "Todos los estados" | Lista desplegable | Filtra por estado de tarea | Permite filtrar el listado mostrando únicamente las tareas que se encuentran en el estado seleccionado (Cancelada, En curso, En espera, Pendiente, etc.). Por defecto muestra todos los estados. |
| 1.3 | Filtro "Todas las prioridades" | Lista desplegable | Filtra por prioridad de tarea | Permite filtrar el listado por nivel de prioridad (Urgente, Alta, Media, Baja). Por defecto muestra todas las prioridades. |
| 1.4 | Filtro "Todos los tipos" | Lista desplegable | Filtra por tipo de tarea | Permite filtrar el listado según la categoría o tipo de tarea definido. Por defecto muestra todos los tipos disponibles. |
| 1.5 | Selector de vista "Lista / Kanban" | Botones de alternancia | Cambia el modo de visualización | Permite alternar entre la vista en formato Lista y la vista en formato Kanban. Para utilizarlo, el usuario debe pulsar el botón correspondiente al modo de visualización deseado. |
| 1.6 | Botón "+ Nueva tarea" | CTA Principal | Abre formulario de creación | Permite iniciar el proceso de creación de una nueva tarea. Para utilizarlo, el usuario debe pulsar el botón y completar los campos del formulario que se mostrará a continuación. |
| 1.7 | Tabla de tareas | Listado interactivo | Muestra y gestiona las tareas | Presenta todas las tareas en formato tabla con las columnas Estado, Prioridad, Tipo, Título, Asignado y Fecha límite. Cada fila incluye acciones de edición (icono lápiz) y eliminación (icono papelera). Las fechas vencidas se muestran en rojo con el texto "Vencida hace X días". |

---

## 💡 Guía de Uso

La vista **Gestión de Tareas** centraliza el seguimiento y control de todas las tareas del sistema en un único listado estructurado.

Se utiliza principalmente para:

- Consultar el estado global de todas las tareas
- Localizar tareas específicas mediante búsqueda o filtros
- Identificar tareas vencidas o con prioridad urgente
- Crear nuevas tareas desde el acceso directo
- Editar o eliminar tareas existentes
- Alternar entre la vista lista y la vista kanban según preferencia

### ✅ Cómo utilizar esta vista correctamente

1. Accede a la sección de Tareas desde el menú principal.
2. Utiliza los filtros de estado, prioridad y tipo para acotar el listado.
3. Usa el buscador para localizar una tarea por su título.
4. Pulsa el icono de lápiz en cualquier fila para editar una tarea existente.
5. Pulsa el icono de papelera para eliminar una tarea (acción irreversible).
6. Pulsa "+ Nueva tarea" para crear una nueva tarea desde cero.
7. Alterna a la vista Kanban si prefieres una visualización por columnas de estado.
