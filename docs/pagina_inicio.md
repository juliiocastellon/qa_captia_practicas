Markdown
#Pagina de inicio

**Objetivo Principal:** [Define en una sola frase qué hace el usuario en esta vista. Ej: Permite al usuario registrar un nuevo proyecto en el sistema.]

## 📸 Mapeo de Interfaz
<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/d1598a7b-dda0-47f8-9ff0-2b9f70e62062" />


## 🧩 Despiece de Elementos Funcionales

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

## 💡 Guía de Uso (Generada por IA)

