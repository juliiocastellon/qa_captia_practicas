# 🖥️ Alarmas – Monitores Operativos

**Objetivo Principal:** Permite al usuario consultar el estado técnico interno del sistema de alarmas, incluyendo el estado del stream SSE, el rendimiento del motor de reglas y los errores internos recientes.

## 📸 Mapeo de Interfaz

<img width="1317" height="425" alt="image" src="https://github.com/user-attachments/assets/9c101735-88b5-4fab-a425-82f41318c3e7" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Panel "Monitores operativos" | Cabecera / Bloque informativo | — | Identifica la vista y describe su alcance: estado interno del stream SSE, buffer, errores recientes y latencia del motor de reglas. |
| 2 | Panel "SSE" | Bloque de estado | — | Revísalo para verificar el estado de la conexión en tiempo real. Muestra: **Clientes conectados** (si aparece "sin clientes conectados", comprueba que el servicio que consume el stream está activo), **Último heartbeat** (confirma que la conexión no lleva tiempo interrumpida), **Buffer** (si se acerca al límite de 10000, puede haber pérdida de eventos) y **Eventos descartados** (si es mayor que 0, investiga la causa). |
| 3 | Panel "Motor de reglas" | Bloque de estado | — | Revísalo para confirmar que el motor está procesando las reglas correctamente. Muestra: **p95 evaluación** (si el valor sube, el motor está tardando demasiado en evaluar las condiciones), **Último error de compilación** (si aparece alguno, revisa la sintaxis de las reglas afectadas) y **Último error de parseo ingest** (si aparece alguno, revisa el formato de los datos de ingesta). |
| 4 | Panel "Errores internos recientes" | Bloque de estado | — | Revísalo regularmente para detectar incidencias técnicas internas antes de que afecten a la detección de alarmas. Si aparece "Sin errores recientes", el sistema funciona con normalidad. |

## 💡 Guía de Uso

La pestaña **Monitores** está orientada a perfiles técnicos y administradores del sistema que necesitan verificar el estado de salud interno de la infraestructura de alarmas. El panel **SSE** (2) permite comprobar si el stream de datos en tiempo real está activo, cuántos clientes están conectados y si se están descartando eventos por saturación del buffer. El panel **Motor de reglas** (3) informa sobre la latencia de evaluación y la ausencia de errores de compilación o parseo, lo que garantiza que las reglas de alarma se están procesando correctamente. Finalmente, el panel **Errores internos recientes** (4) actúa como registro de incidencias técnicas del sistema: si aparece alguna entrada, debe investigarse para evitar degradación en la detección de alarmas.
