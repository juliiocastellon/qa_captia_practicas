# 🖥️ Auditoría

**Objetivo principal:** Permite al usuario consultar y supervisar el registro de actividad del sistema, visualizando acciones realizadas, accesos, cambios y eventos generados dentro de la plataforma.

## 📸 Mapeo de interfaz
<img width="1223" height="585" alt="image" src="https://github.com/user-attachments/assets/12813df9-7dd4-4a2a-b2a5-247190dfb2bb" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Filtro de rango temporal | Selector de fecha | Filtrar registros | Permite definir el periodo de tiempo sobre el que se consultarán los eventos de auditoría. |
| 2 | Buscador de usuario | Campo de búsqueda | Filtrar por usuario | Permite localizar registros de auditoría asociados a usuarios concretos mediante email o identificador. |
| 3 | Filtro de acción | Filtro desplegable | Filtrar acciones | Permite mostrar únicamente determinados tipos de acciones registradas dentro del sistema. |
| 4 | Filtro de tipo de recurso | Filtro desplegable | Filtrar recursos | Permite visualizar eventos relacionados con recursos o módulos específicos de la plataforma. |
| 5 | Botón "Actualizar" | CTA Secundario | Refrescar auditoría | Permite actualizar manualmente los registros y eventos mostrados en pantalla. |
| 6 | Filtro de resultado | Filtro desplegable | Filtrar resultados | Permite visualizar registros según el resultado de la acción ejecutada, como éxito o error. |
| 7 | Acciones de filtrado | CTA Secundario | Aplicar/Limpiar filtros | Permite aplicar los filtros configurados o limpiar rápidamente la búsqueda actual. |
| 8 | Registro de auditoría | Tabla de eventos | Consultar actividad | Muestra el historial detallado de eventos y acciones realizadas dentro de la plataforma, incluyendo usuario, recurso, resultado y fecha de ejecución. |

## 💡 Guía de uso

La sección de Auditoría permite supervisar toda la actividad registrada dentro de la plataforma, facilitando el seguimiento de accesos, modificaciones y acciones ejecutadas por los usuarios.

Desde la parte superior puedes aplicar filtros por fecha, usuario, acción, recurso o resultado para localizar rápidamente eventos específicos. La tabla principal muestra información detallada de cada registro, incluyendo quién realizó la acción, sobre qué recurso se ejecutó y cuál fue el resultado obtenido.

Esta sección resulta especialmente útil para tareas de supervisión, trazabilidad, seguridad y análisis operativo dentro del entorno industrial.
