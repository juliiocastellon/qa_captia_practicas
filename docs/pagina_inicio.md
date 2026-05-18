# 🖥️ Página de inicio

**Objetivo principal:** Permite al operario obtener de un vistazo el estado actual de la planta, identificar tareas y alarmas prioritarias y acceder a la siguiente acción recomendada por la IA.

## 📸 Mapeo de interfaz

<img width="1836" height="856" alt="image" src="https://github.com/user-attachments/assets/88e3abea-430c-4db4-ae31-3ca6214b3870" />

## 🧩 Despiece de elementos funcionales

| Nº | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :---: | :--- | :--- | :--- | :--- |
| 1 | Saludo y turno | Información | — | Muestra el nombre del usuario, turno activo, fecha y última lectura. El enlace "4 tareas" redirige al listado de tareas pendientes. |
| 2 | Lectura AI de planta | Bloque informativo | — | Resume el estado de la planta con lenguaje natural. Incluye badges de estado (REVISADO, PENDIENTE, CONFIANZA) y citas numeradas enlazadas a fuentes de datos. |
| 3 | Botón "Por qué veo esto" | CTA Secundario | Abre panel explicativo | Muestra los datos y reglas que ha usado la IA para generar el resumen actual. |
| 4 | Botón "Revisar tareas vencidas" | CTA Principal | Navega a Tareas | Abre el listado de tareas que han superado su fecha límite. |
| 5 | Botón "Analizar con Copilot" | CTA Principal | Abre análisis IA | Lanza un análisis asistido por IA sobre el estado actual de la planta. |
| 6 | Radar de atención | Panel informativo | — | Muestra 6 dominios industriales (Safety, Quality, Energy, Production, Maintenance, Data Health) con su prioridad y nivel (BASE/MEDIA/ALTA). Muestra "s/d" si el origen de datos no está conectado. |
| 7 | Manufacturing Signal Board | Tabla de métricas | — | Muestra 9 métricas clave de producción con su estado actual. Los valores pueden ser numéricos, "s/d" (sin datos) o "Sin MES" (sistema no conectado). El badge "5 s/d" indica cuántas métricas están sin datos. |
| 8 | Contexto y preparación | Panel informativo | Enlace "Configurar vigilancia" | Muestra los servicios conectados, calidad de datos actual y qué falta para mejorar la cobertura del análisis IA. |
| 9 | Siguientes mejores acciones | Carrusel de tarjetas | Varía por tarjeta | Muestra hasta 10 acciones sugeridas por la IA ordenadas por prioridad. Cada tarjeta indica tipo (PREPARAR/NAVEGAR/ANALIZAR), prioridad (Alta/Media/Baja) y motor (Copilot/Navega). |

## 💡 Guía de uso (generada por IA)

La página de inicio es tu centro de control al comenzar cada turno. En cuanto accedas, la IA analizará automáticamente el estado de la planta y te mostrará un resumen con las alarmas activas, tareas vencidas y la acción más urgente a tomar. Desde el Radar de atención y el Manufacturing Signal Board podrás ver de un vistazo qué dominios e indicadores requieren tu atención, identificando fácilmente qué tiene datos disponibles y qué está pendiente de conexión. Si necesitas profundizar, las tarjetas de "Siguientes mejores acciones" te guiarán paso a paso hacia la siguiente tarea prioritaria, ya sea preparando un informe, navegando a una sección o lanzando un análisis con Copilot.
