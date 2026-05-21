# 🖥️ Alarmas – Correlación de Alarmas

**Objetivo Principal:** Permite al usuario identificar relaciones causales o temporales entre alarmas, agrupándolas automáticamente en incidentes para facilitar el análisis de causa raíz.

## 📸 Mapeo de Interfaz

<img width="1342" height="287" alt="image" src="https://github.com/user-attachments/assets/0db83ab4-5c40-4e53-bcf4-d0fc33d18343" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Título "Correlación de Alarmas" | Cabecera informativa | — | Identifica la vista actual como el panel de correlación y agrupación de alarmas en incidentes. |
| 2 | Estado vacío "Sin incidentes correlacionados" | Mensaje de estado vacío | — | Indica que en el momento actual no existen incidentes generados por correlación de alarmas. |
| 3 | Descripción del mecanismo de correlación | Texto informativo | — | Explica que los incidentes se crean automáticamente cuando varias alarmas comparten un patrón temporal o causal definido mediante el campo incident_key en la regla. |
| 4 | Panel de instrucciones "Para generar correlaciones" | Bloque de ayuda contextual | — | Guía al usuario sobre los pasos necesarios para activar el sistema de correlación, detallando el flujo en tres pasos: crear reglas con incident_key compartido, agrupación automática de alarmas en incidentes y detección automática de candidatos a causa raíz por parte del sistema. |

## 💡 Guía de Uso (Generada por IA)

La pestaña **Correlación de Alarmas** permite al sistema agrupar automáticamente alarmas relacionadas en incidentes, facilitando el análisis de causa raíz sin intervención manual. Para activar esta funcionalidad, es necesario configurar reglas de alarma que compartan el mismo valor de **incident_key**: cuando varias alarmas con el mismo incident_key se disparan, el sistema las agrupa en un único incidente e identifica automáticamente los candidatos a causa raíz. En el estado actual no hay incidentes correlacionados, lo que indica que ninguna regla tiene aún el campo incident_key configurado o que no se han producido disparos simultáneos entre reglas relacionadas. Dirígete a la pestaña **Reglas** para comenzar a configurar este parámetro en tus reglas de alarma.
