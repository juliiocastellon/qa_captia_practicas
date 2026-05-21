# 🖥️ Alarmas – Auditoría de Alarmas

**Objetivo Principal:** Permite al usuario consultar el registro inmutable de todas las acciones manuales realizadas sobre alarmas e incidentes, y exportarlo en distintos formatos para su análisis o archivo.

## 📸 Mapeo de Interfaz

<img width="1202" height="332" alt="image" src="https://github.com/user-attachments/assets/575e0889-5eb8-496a-bf4a-ce5d1a8d2f86" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Título "Auditoría de Alarmas" | Cabecera informativa | — | — |
| 2 | Botón recargar | Acción | Actualiza el listado de eventos de auditoría | Púlsalo para ver si se han registrado nuevas acciones desde la última vez que consultaste el log. |
| 3 | Botón exportar CSV | Acción | Descarga el log de auditoría en formato CSV | Úsalo para descargar el log y analizarlo en una hoja de cálculo o incluirlo en un informe de cumplimiento. |
| 4 | Botón exportar JSON | Acción | Descarga el log de auditoría en formato JSON | Úsalo cuando necesites procesar el log automáticamente o integrarlo con un sistema externo de auditoría. |
| 5 | Área de log | Listado de eventos | — | Aquí se mostrarán los eventos de auditoría conforme los operadores realicen acciones manuales sobre alarmas. Si aparece vacío, indica que aún no se ha realizado ninguna acción registrable. |

## 💡 Guía de Uso

La pestaña **Auditoría de Alarmas** actúa como el registro de trazabilidad oficial de todas las interacciones manuales con el sistema de alarmas. Cada vez que un operador realiza una acción sobre una alarma —reconocerla, resolverla, aparcarla, comentarla o escalarla— se genera automáticamente una entrada inmutable en este log, garantizando la trazabilidad completa de la gestión operativa. En el estado actual no hay eventos registrados, lo que indica que aún no se ha realizado ninguna acción manual sobre alarmas. Cuando el log contenga entradas, podrás exportarlo en formato **CSV** (3) para su análisis en hojas de cálculo, o en formato **JSON** (4) para su integración con sistemas externos. Utiliza el botón de **recarga** (2) para refrescar el listado y ver los eventos más recientes en cualquier momento.
