# 🖥️ Dato: Variable UDT — Configuración

**Objetivo Principal:** Permite al usuario construir una estructura de datos tipada (UDT) mapeando variables globales de proceso a cada campo, definiendo el asset, tipo UDT y alias local antes de guardar.

## 📸 Mapeo de Interfaz

<img width="321" height="467" alt="image" src="https://github.com/user-attachments/assets/852781e6-16a6-4576-ac21-309864d5e693" />

## 🧩 Despiece de Elementos Funcionales

| # | Nombre del Elemento | Tipo | Destino / Acción | Descripción Funcional |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Bloque "Mapeo global → UDT" | Bloque informativo | — | Describe el propósito del nodo: configurar el asset, el tipo UDT y cómo cada campo se alimenta desde variables globales. |
| 2 | Sección "A. Contexto del binding" | Formulario (3 campos) | Define el contexto base del mapeo | Agrupa tres campos en línea: **Asset ID** (selector del activo concreto del que se obtendrán los datos), **Tipo UDT** (selector del tipo que define la estructura esperada) y **Alias local** (nombre local para acceder al UDT en runtime, ej: `aula`). |
| 3 | Sección "B. Campos detectados" | Bloque de referencia (read-only) | Muestra los campos de la estructura UDT seleccionada | Referencia rápida de los campos de la estructura objetivo. Se activa al seleccionar un Tipo UDT. Muestra placeholder "Selecciona un UDT para ver sus campos." mientras no hay tipo seleccionado. |
| 4 | Sección "C. Mapeo global → UDT" | Área de mapeo + Botón "Auto-map" | Vincula cada campo UDT a su variable global de origen | Permite asignar manualmente cada campo del UDT a una variable global. El botón **Auto-map** intenta realizar el mapeo automáticamente. Muestra contador de estado: `0 correctos · 0 pendientes · 0 inválidos`. |
| 5 | Sección "D. Resumen final" | Bloque de validación (read-only) | Muestra el estado del nodo antes de guardar | Vista previa del resultado del mapeo. Indica campos pendientes o inválidos. Muestra aviso en naranja: "Completa los campos pendientes para habilitar un guardado confiable." cuando la configuración está incompleta. |
| 6 | Botón "Cancelar" | Botón secundario | Cierra el panel sin guardar cambios | Descarta cualquier modificación realizada y devuelve al estado anterior. |
| 7 | Botón "Guardar" | CTA Principal | Persiste la configuración del nodo | Guarda el mapeo configurado y cierra el panel. Se habilita completamente cuando todos los campos requeridos están correctamente definidos. |

## 💡 Guía de Uso

1. Abre la configuración del nodo haciendo clic sobre **Variable UDT** en el canvas del workflow.
2. En la sección **A. Contexto del binding**, selecciona el **Asset ID** del activo, el **Tipo UDT** que define la estructura esperada y define el **Alias local** con el que accederás al UDT en runtime.
3. En la sección **B. Campos detectados**, revisa los campos que componen la estructura UDT seleccionada.
4. En la sección **C. Mapeo global → UDT**, vincula cada campo del UDT a su variable global de origen. Usa el botón **Auto-map** para intentar el mapeo automático.
5. Verifica en la sección **D. Resumen final** que todos los campos están correctos antes de guardar. El aviso naranja indica campos pendientes que deben resolverse.
6. Pulsa **Guardar** para confirmar, o **Cancelar** para descartar.
