# 🖥️ Página de inicio

**Objetivo principal:** Permite al operario obtener de un vistazo el estado actual de la planta, identificar tareas y alarmas prioritarias y acceder a la siguiente acción recomendada por la IA.

## 📸 Mapeo de interfaz
<img width="1918" height="911" alt="image" src="https://github.com/user-attachments/assets/d55076c4-f391-4c19-8b1b-95afa3d1b111" />

## 🧩 Despiece de elementos funcionales

| Nombre del elemento | Tipo | Destino / Acción | Descripción funcional |
| :--- | :--- | :--- | :--- |
| Saludo y turno | Información | — | Muestra el nombre del usuario, turno activo, fecha y última lectura. El enlace "4 tareas" redirige al listado de tareas pendientes. |
| Lectura AI de planta | Bloque informativo | — | Resume el estado de la planta con lenguaje natural. Incluye badges de estado (REVISADO, PENDIENTE, CONFIANZA) y citas numeradas enlazadas a fuentes de datos. |
| Botón "Por qué veo esto" | CTA Secundario | Abre panel explicativo | Muestra los datos y reglas que ha usado la IA para generar el resumen actual. |
| Botón "Revisar tareas vencidas" | CTA Principal | Navega a Tareas | Abre el listado de tareas que han superado su fecha límite. |
| Botón "Analizar con Copilot" | CTA Principal | Abre análisis IA | Lanza un análisis asistido por IA sobre el estado actual de la planta. |
| Radar de atención | Panel informativo | — | Muestra 6 dominios industriales (Safety, Quality, Energy, Production, Maintenance, Data Health) con su prioridad y nivel (BASE/MEDIA/ALTA). Muestra "s/d" si el origen de datos no está conectado. |
| Manufacturing Signal Board | Tabla de métricas | — | Muestra 9 métricas clave de producción con su estado actual. Los valores pueden ser numéricos, "s/d" (sin datos) o "Sin MES" (sistema no conectado). El badge "5 s/d" indica cuántas métricas están sin datos. |
| Siguientes mejores acciones | Carrusel de tarjetas | Varía por tarjeta | Muestra hasta 10 acciones sugeridas por la IA ordenadas por prioridad. Cada tarjeta indica tipo (PREPARAR/NAVEGAR/ANALIZAR), prioridad (Alta/Media/Baja) y motor (Copilot/Navega). |
| Contexto y preparación | Panel informativo | Enlace "Configurar vigilancia" | Muestra los servicios conectados, calidad de datos actual y qué falta para mejorar la cobertura del análisis IA. |
| Toggle Carrusel | Toggle | Activa/desactiva rotación | Activa la rotación automática entre dashboards disponibles. Desactivarlo permite navegación manual. |
| Botón "Vista clásica" | CTA Secundario | Cambia modo de vista | Alterna entre la vista AI y la vista clásica de la plataforma. Funcionalidad pendiente de verificar. |
| Toggle ON (sidebar) | Toggle | Desconocido | Botón verde en la parte inferior del sidebar. Función pendiente de documentar. |
| Navegación lateral | Menú | Navega a cada sección | Acceso a: Inicio, SCADA, Dashboards, Informes, Automatizaciones, Tareas, Calendario, Alarmas, Variables, Auditoría, Cuenta. Puede mostrar solo iconos en resoluciones reducidas. |
| Indicador de conexión | Estado | — | Punto verde en la barra superior que indica que los servicios están operativos ("OPERACION ESTABLE"). |
| Versión (v0.24) | Información | — | Número de versión visible en la esquina inferior izquierda del sidebar. Útil para reportar bugs. |

## 💡 Guía de uso

La página de inicio es tu centro de control al comenzar cada turno. En cuanto accedas, la IA analizará automáticamente el estado de la planta y te mostrará un resumen con las alarmas activas, tareas vencidas y la acción más urgente a tomar. Desde el Radar de atención y el Manufacturing Signal Board podrás ver de un vistazo qué dominios e indicadores requieren tu atención, identificando fácilmente qué tiene datos disponibles y qué está pendiente de conexión. Si necesitas profundizar, las tarjetas de "Siguientes mejores acciones" te guiarán paso a paso hacia la siguiente tarea prioritaria, ya sea preparando un informe, navegando a una sección o lanzando un análisis con Copilot.
