# 🖥️ Página de inicio

**Objetivo principal:** Permite al operario obtener de un vistazo el estado actual de la planta, identificar tareas y alarmas prioritarias y acceder a la siguiente acción recomendada por la IA.

## 📸 Mapeo de interfaz

<img width="1677" height="938" alt="image" src="https://github.com/user-attachments/assets/7e2ce1a8-008e-4d5f-85d4-4caa07d8d27c" />

## 🧩 Despiece de elementos funcionales

| # | Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Lectura AI de la instalación | Bloque informativo | — | Resume el estado de la instalación con lenguaje natural. Indica alarmas activas y tareas vencidas del turno actual. Incluye badges de estado. |
| 2 | Citas numeradas [1][2] / "Ver fuentes" | Enlace | Despliega panel "Fuentes consultadas" | Muestra las fuentes de datos usadas por la IA para generar el resumen. [1] corresponde a alarms.list_active (alarmas abiertas con prioridad P1/P2) y [2] a tasks.list (tareas vencidas, las que vencen hoy y total). Accesible tanto desde las citas numeradas como desde el enlace "Ver fuentes (2)". |
| 3 | Siguiente mejor acción | Bloque informativo | — | Muestra la acción prioritaria recomendada por la IA con una descripción breve del impacto esperado. |
| 4 | Botón "Por qué veo esto" | CTA Secundario | Despliega panel en la misma vista | Muestra las reglas aplicadas por la IA para generar el briefing. Parámetros visibles: severity_pill, narrative_mode, kpis, watchlist, reasons y tenant_inventory. Actualmente en formato técnico crudo, no interpretable por un usuario final. |
| 5 | Botón "Revisar tareas vencidas" | CTA Principal | Abre panel lateral "Copiloto CAPTIA" | Abre el panel lateral del asistente IA Copiloto CAPTIA con el contexto de la acción precargado. Muestra automáticamente las razones detectadas (tareas vencidas y alarmas sin reconocer) y el foco prioritario. |
| 6 | Botón "Analizar con Copilot" | CTA Principal | Abre análisis IA | Lanza un análisis asistido por IA sobre el estado actual de la instalación. |
| 7 | Radar de atención | Panel informativo | — | Muestra 6 dominios (Safety, Quality, Energy, Production, Maintenance, Data Health) con su prioridad y nivel (BASE/MEDIA/ALTA). Muestra "s/d" si el origen de datos no está conectado. |
| 8 | Manufacturing Signal Board | Tabla de métricas | — | Muestra 9 métricas clave con su estado actual. Los valores pueden ser numéricos, "s/d" (sin datos) o "Sin MES" (sistema no conectado). El badge "5 s/d" indica cuántas métricas están sin datos en ese momento. |
| 9 | Contexto y preparación | Panel informativo | Enlace "Configurar vigilancia" | Muestra los servicios conectados, calidad de datos actual y qué falta para mejorar la cobertura del análisis IA. |
| 10 | Siguientes mejores acciones | Carrusel de tarjetas | Varía por tarjeta | Muestra hasta 10 acciones sugeridas por la IA ordenadas por prioridad. Cada tarjeta indica tipo (PREPARAR/NAVEGAR/ANALIZAR), prioridad (Alta/Media/Baja) y motor (Copilot/Navega). Contador "4 de 10" visible en la esquina superior derecha. |

## 💡 Guía de uso (generada por IA)

La página de inicio es tu centro de control al comenzar cada turno. En cuanto accedas, la IA analizará automáticamente el estado de la instalación y te mostrará un resumen con las alarmas activas, tareas vencidas y la acción más urgente a tomar. Desde el Radar de atención y el Manufacturing Signal Board podrás ver de un vistazo qué dominios e indicadores requieren tu atención, identificando fácilmente qué tiene datos disponibles y qué está pendiente de conexión. Si necesitas profundizar, las tarjetas de "Siguientes mejores acciones" te guiarán paso a paso hacia la siguiente tarea prioritaria, ya sea preparando un informe, navegando a una sección o lanzando un análisis con Copilot.
