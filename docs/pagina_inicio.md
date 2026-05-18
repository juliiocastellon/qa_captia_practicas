# Página de inicio

## Objetivo principal
Permite al operario obtener de un vistazo el estado actual de la planta, identificar tareas y alarmas prioritarias y acceder a la siguiente acción recomendada por la IA.

## 📸 Mapeo de interfaz
<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/d1598a7b-dda0-47f8-9ff0-2b9f70e62062" />

## 🧩 Despiece de elementos funcionales

| Sección | Descripción | Observaciones QA |
|---|---|---|
| Saludo y turno | Muestra el nombre del usuario, turno activo (mañana), fecha y última lectura. Indica tareas pendientes en rojo | "4 tareas" en naranja/rojo actúa como enlace o alerta |
| Lectura AI de planta | Bloque principal de IA que resume el estado de la planta con lenguaje natural. Muestra alarmas activas, tareas vencidas y confianza del análisis | Incluye badges: REVISADO, PENDIENTE, CONFIANZA. Tiene citas numeradas [1][2] con fuentes. Botón "Por qué veo esto" |
| Siguiente mejor acción | Sugiere la acción prioritaria a tomar ("Revisar tareas vencidas") con una descripción breve del impacto | Dos CTAs: "Revisar tareas vencidas" y "Analizar con Copilot" |
| Radar de atención | Panel derecho con 6 dominios industriales (Safety, Quality, Energy, Production, Maintenance, Data Health) con prioridad, estado y nivel (BASE/MEDIA) | Dominios con datos muestran valor numérico. Sin datos muestran "s/d". Etiqueta global "PREVENTIVO" en naranja |
| Manufacturing Signal Board | Tabla de métricas clave: Producción, OEE, Alarmas activas, Tareas GMAO, Calidad, Energía, Paradas, Cuello botella, Cambios | Estados: "Sin MES", "s/d", valores numéricos. Etiquetas: pendiente, base, alta, atención, revisar. Badge "0 críticos = control" |
| Contexto y preparación | Panel derecho con servicios conectados, calidad de datos, qué vigila Captia y qué falta para mejorar | Muestra 3 servicios activos con indicadores de color. Sección "Falta para mejorar" muy útil para el usuario |
| Barra superior | Logo, nombre de plataforma, toggle Carrusel, indicador de conexión (verde), notificaciones, menú de usuario | Toggle "Carrusel" sin documentar su función visible. Indicador verde = operación estable |
| Navegación lateral | Iconos de secciones principales sin etiquetas de texto | Sin labels visibles, depende solo de iconos — posible problema de accesibilidad |
| Versión | v0.24 visible en esquina inferior izquierda | Útil para reportar bugs, confirmar que está visible |

## 💡 Guía de uso

### ¿Qué verás al entrar?
Al iniciar sesión llegarás directamente a la página de inicio. La plataforma detecta automáticamente tu turno activo y genera un resumen del estado de la planta basado en los datos disponibles en ese momento.

### Cómo leer la Lectura AI de planta
El bloque azul central es el resumen más importante de la página. La IA analiza alarmas, tareas y dashboards conectados y te presenta:
- **El estado actual** en una frase directa ("Atención requerida ahora: 4 tareas vencidas")
- **Los badges** indican qué ha revisado la IA (REVISADO), qué está pendiente de datos (PENDIENTE) y el nivel de confianza del análisis (CONFIANZA alta/media/baja)
- **Las citas numeradas** [1][2] enlazan a las fuentes de datos usadas. Haz clic en "Ver fuentes" para consultarlas

### Cómo usar el Radar de atención
El radar muestra 6 dominios industriales ordenados por prioridad. Cada dominio indica:
- Un valor numérico si hay datos disponibles
- **s/d** (sin datos) si el origen de datos no está conectado
- Un nivel de prioridad: BASE (normal), MEDIA (requiere atención), ALTA (acción inmediata)

### Cómo usar el Manufacturing Signal Board
Es la tabla de señales de producción. Cada celda muestra el valor actual de una métrica clave. Los estados posibles son:
- **Sin MES** — el sistema MES no está conectado, no hay datos de producción
- **s/d** — sin datos disponibles en este momento
- Un número — valor actual de la métrica
- Las etiquetas de color (pendiente, atención, revisar, alta, base) indican el nivel de urgencia

### Acciones disponibles desde esta página
- **Revisar tareas vencidas** — abre el listado de tareas que han superado su fecha límite
- **Analizar con Copilot** — lanza un análisis asistido por IA sobre el estado actual
- **Por qué veo esto** — explica qué datos y reglas ha usado la IA para generar el resumen

## ⚠️ Limitaciones conocidas
- Los dominios sin origen de datos conectado (MES, scrap, consumo energético) muestran "s/d" y no generan recomendaciones
- El toggle "Carrusel" de la barra superior rota automáticamente entre dashboards; desactívalo si prefieres navegación manual
- La navegación lateral solo muestra iconos sin etiquetas; pasa el cursor por encima para ver el nombre de cada sección
