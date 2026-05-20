# Guía simple de validación QA — Issues Sprint 2 en Review

Documento preparado para que un **QA tester** valide en la aplicación las issues del Sprint 2 que están en estado **In review**.

## Cómo usar este documento

Para cada issue:

1. Lee **qué tiene que validar el QA tester**.
2. Ejecuta los **pasos en la aplicación**.
3. Rellena el bloque **Reporte del QA tester**.
4. Marca si la issue está OK, falla, queda bloqueada o no aplica.

> Importante: este documento está pensado para validar comportamiento en la aplicación. No es necesario acceder al repositorio de código.

## Resumen

- Total issues: **31**
- Abiertas en GitHub: **21**
- Cerradas en GitHub: **10**
- Sprint: **Sprint 2**
- Estado de proyecto: **In review**

## Matriz rápida de seguimiento

| Issue | Título | Prioridad | Estado GitHub | Resultado QA |
|---|---|---:|---|---|
| [#190](#issue-190) | [Feature]  Migracion de informes a konva | P0 | OPEN | ⬜ Pendiente |
| [#192](#issue-192) | [Bug] Eliminar widget con alert nativo | P0 | OPEN | ⬜ Pendiente |
| [#189](#issue-189) | [Bug]  Informes no funciona | P0 | OPEN | ⬜ Pendiente |
| [#103](#issue-103) | [FEATURE] Al crear reglas de coloración dinámica, poder duplicar reglas para no tener que crear desde 0, sino modificar lo necesario. Tambien extraer del modal de configuracion de la regla la seleccion de la variable igual como esta en "Estados" | P2 | OPEN | ⬜ Pendiente |
| [#104](#issue-104) | [FEATURE] En scada en las reglas de coloración dinámica, poder exportar y importar reglas | P2 | OPEN | ⬜ Pendiente |
| [#137](#issue-137) | [Feature]  Estandarizar funcionamiento del selector de variables en las reglas de coloración dinámica | P1 | OPEN | ⬜ Pendiente |
| [#140](#issue-140) | [Feature]  Cambiar configuración color forma people_count en Carlos III | P0 | OPEN | ⬜ Pendiente |
| [#119](#issue-119) | [Bug]  Error Typescript al cargar SCADA en Carlos III | P0 | CLOSED | ⬜ Pendiente |
| [#114](#issue-114) | [Bug]  En la pantalla "Cuenta" la accion "Revocar acceso" (intentar eliminar un miembro de tu equipo) no funciona correctamente | P0 | CLOSED | ⬜ Pendiente |
| [#71](#issue-71) | [BUG] En Workflows: Cuando se exporta un workflow de un tenant y se importa en otro tenant diferente (export: simarro → import: carlos iii) el json se lleva datos del tenant del que se exporta y luego hay conflicto cuando se importa en el otro. No muestra variables disponibles, no permite cambiarlas etc. | P0 | CLOSED | ⬜ Pendiente |
| [#68](#issue-68) | [BUG] SCADA: cuando hay mucho widget tarda en cargar la imagen de fondo, primero la carga con un tamaño ampliado, y se ajusta más tarde. O directamente no se carga con la resolución adecuada y se queda ampliada sin respetar la proporción. | P0 | CLOSED | ⬜ Pendiente |
| [#113](#issue-113) | [Bug]  Comprobar implantacion de libreria Chackra UI en la pantalla "Cuenta" | P0 | CLOSED | ⬜ Pendiente |
| [#98](#issue-98) | [CHORE] kpis en tarjeta, auditar y que funcione correctamente | P0 | CLOSED | ⬜ Pendiente |
| [#101](#issue-101) | [CHORE] Mejorar menu derecha widget analytics + elementos scada | P0 | CLOSED | ⬜ Pendiente |
| [#74](#issue-74) | [BUG] No muestra algunos objetos al cargar la pantalla, por ejmplo, en alguna aula no carga el fondo derecho de los widgets del grafico, al recargar la pagina si que se muestra. | P0 | CLOSED | ⬜ Pendiente |
| [#108](#issue-108) | [Bug]  Pantalla Tareas se queda en blanco | P0 | OPEN | ⬜ Pendiente |
| [#93](#issue-93) | [CHORE] Ajustar tamaño boton tres puntos del widget en escena, condiciona el tamaño del header, cuando no esta el header es menos alto | P1 | OPEN | ⬜ Pendiente |
| [#95](#issue-95) | [CHORE] Eliminar 'Plano (borde sutil)' | P0 | CLOSED | ⬜ Pendiente |
| [#102](#issue-102) | [BUG] Hover en widget transparente aparece primero icono tres puntos y despues lupa | P1 | OPEN | ⬜ Pendiente |
| [#107](#issue-107) | [Feature] Al abrir un Dashboard que aparezca la barra superior por defecto | P0 | OPEN | ⬜ Pendiente |
| [#133](#issue-133) | [Bug]  Error al cargar la imagen de SCADA | P0 | CLOSED | ⬜ Pendiente |
| [#141](#issue-141) | [Feature]  Comprobacion de pilotos en SCADA | P0 | OPEN | ⬜ Pendiente |
| [#165](#issue-165) | [Bug]  Error al cargar la pagina /task en Carlos III | P0 | OPEN | ⬜ Pendiente |
| [#169](#issue-169) | [Bug]  Arreglar selector de Rol en pestaña cuenta | P1 | OPEN | ⬜ Pendiente |
| [#181](#issue-181) | [Bug]  Se puede elegir variables de otro tennant | P0 | OPEN | ⬜ Pendiente |
| [#182](#issue-182) | [Feature]  Añadir un pop-up en el selector de rol en Cuenta para que pregunte al hacer un cambio de rol | P2 | OPEN | ⬜ Pendiente |
| [#183](#issue-183) | [Feature]  Crear un widget Slider para representar las consignas | P1 | OPEN | ⬜ Pendiente |
| [#187](#issue-187) | Auditar prioridad de reglas de coloración en SCADA para descartar solapamientos de rangos | P1 | OPEN | ⬜ Pendiente |
| [#191](#issue-191) | [Bug] No se pueden elegir todos los widgets disponibles del listado | P0 | OPEN | ⬜ Pendiente |
| [#193](#issue-193) | [Feature] Los graficos en informes no deberian tener tooltip en el hover | P0 | OPEN | ⬜ Pendiente |
| [#194](#issue-194) | [Feature]  Estandarizar el campo "Descripcion" en los diferentes menús de captia.ai | P2 | OPEN | ⬜ Pendiente |

---

<a id="issue-190"></a>
## 1. #190 — [Feature]  Migracion de informes a konva

**URL:** https://github.com/captia-technology/captia.ai/issues/190
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** XL
**Assignees:** pascuord
**Labels:** enhancement
**Área:** Frontend / UI
**Severidad/Prioridad:** Crítica (bloqueador de negocio)

### Qué tiene que validar el QA tester

Que la migración de Informes a Konva no rompe las acciones principales de la pantalla de Informes.

### Pasos en la aplicación

1. Entrar en la sección **Informes**.
2. Abrir un informe existente y, si es posible, crear o editar un informe de prueba.
3. Probar acciones básicas: mover elementos, redimensionar, editar configuración, guardar cambios y recargar la página.
4. Comprobar que no aparecen errores visuales ni errores en consola.

### Resultado esperado

Informes funciona de forma estable tras la migración: los elementos se ven correctamente, se pueden editar y guardar sin errores.

### Contexto original útil

**Problema o necesidad:**

Migracion de informes a konva

**Solución propuesta:**

Migracion de informes a konva

**Alternativas consideradas:**

Migracion de informes a konva

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-192"></a>
## 2. #192 — [Bug] Eliminar widget con alert nativo

**URL:** https://github.com/captia-technology/captia.ai/issues/192
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** XS
**Assignees:** pascuord
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Crítico (bloquea funcionalidad principal)

### Qué tiene que validar el QA tester

Que al eliminar un widget no aparece el alert nativo del navegador y se usa un modal de Chakra.

### Pasos en la aplicación

1. Entrar en una pantalla donde se puedan editar widgets.
2. Crear o localizar un widget de prueba.
3. Pulsar la acción de eliminar.
4. Comprobar qué tipo de confirmación aparece.
5. Probar cancelar y confirmar la eliminación.

### Resultado esperado

Debe aparecer un modal integrado en la UI, no un `alert` nativo del navegador. Cancelar no elimina el widget y confirmar sí lo elimina.

### Contexto original útil

**Descripción del problema:**

Al eliminar un widget muestra un alert nativo

**Comportamiento esperado:**

Modal de chackra

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-189"></a>
## 3. #189 — [Bug]  Informes no funciona

**URL:** https://github.com/captia-technology/captia.ai/issues/189
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Crítico (bloquea funcionalidad principal)

### Qué tiene que validar el QA tester

Que la pantalla de Informes permite trabajar sin quedarse bloqueada.

### Pasos en la aplicación

1. Entrar en **Informes**.
2. Abrir un informe existente.
3. Cambiar algún filtro o configuración.
4. Realizar varias acciones normales: navegar, editar, guardar o interactuar con gráficos/widgets.
5. Comprobar consola y comportamiento visual.

### Resultado esperado

La pantalla de Informes debe responder correctamente y no debe fallar al realizar acciones normales.

### Contexto original útil

**Descripción del problema:**

Al entrar a informes y realizar cualquier accion no funciona

**Comportamiento esperado:**

Debe funcionar informes sin problema

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-103"></a>
## 4. #103 — [FEATURE] Al crear reglas de coloración dinámica, poder duplicar reglas para no tener que crear desde 0, sino modificar lo necesario. Tambien extraer del modal de configuracion de la regla la seleccion de la variable igual como esta en "Estados"

**URL:** https://github.com/captia-technology/captia.ai/issues/103
**Estado GitHub:** OPEN
**Prioridad proyecto:** P2
**Size:** M
**Assignees:** Yordaw
**Labels:** enhancement, area:frontend, priority:medium

### Qué tiene que validar el QA tester

Que en SCADA se pueden duplicar reglas de coloración dinámica y que el selector de variable queda fuera del modal de cada regla.

### Pasos en la aplicación

1. Entrar en un SCADA editable.
2. Seleccionar una forma o elemento con coloración dinámica.
3. Abrir la configuración de **Reglas**.
4. Crear una regla y probar si se puede duplicar.
5. Modificar la regla duplicada.
6. Comprobar si la variable se selecciona una vez fuera del modal, igual que en **Estados** o **Escala**.

### Resultado esperado

El QA tester debe poder duplicar reglas y modificar solo lo necesario. La variable debe seleccionarse de forma externalizada, sin tener que elegirla en cada regla.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-104"></a>
## 5. #104 — [FEATURE] En scada en las reglas de coloración dinámica, poder exportar y importar reglas

**URL:** https://github.com/captia-technology/captia.ai/issues/104
**Estado GitHub:** OPEN
**Prioridad proyecto:** P2
**Size:** M
**Assignees:** Yordaw
**Labels:** enhancement, area:frontend, priority:medium

### Qué tiene que validar el QA tester

Que las reglas de coloración dinámica de SCADA se pueden exportar e importar entre SCADAs.

### Pasos en la aplicación

1. Entrar en un SCADA con reglas de coloración dinámica configuradas.
2. Buscar la opción de exportar reglas.
3. Exportar las reglas.
4. Entrar en otro SCADA de prueba.
5. Importar las reglas exportadas.
6. Comprobar que las reglas importadas mantienen configuración, variable, colores, rangos y prioridad si aplica.

### Resultado esperado

Las reglas se exportan e importan correctamente y quedan utilizables en el SCADA destino.

### Contexto original útil

**Descripción:**

Investigar la exportacion de las reglas para poder extraerlas de un SCADA y llevarlo a otro diferente. Por ejemplo, una regla que se aplique a un SCADA aula y se necesite en un SCADA planta. Deberiamos analizar su viabilidad y dificultad para aplicar antes de implantar para valorar.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-137"></a>
## 6. #137 — [Feature]  Estandarizar funcionamiento del selector de variables en las reglas de coloración dinámica

**URL:** https://github.com/captia-technology/captia.ai/issues/137
**Estado GitHub:** OPEN
**Prioridad proyecto:** P1
**Size:** M
**Assignees:** Yordaw
**Labels:** enhancement, area:frontend, priority:high, Scada, frontend
**Área:** Frontend / UI
**Severidad/Prioridad:** Alta (necesidad importante)

### Qué tiene que validar el QA tester

Que el selector de variables en reglas de coloración dinámica funciona igual que en Estados y Escala.

### Pasos en la aplicación

1. Entrar en un SCADA editable.
2. Seleccionar una forma con coloración dinámica.
3. Abrir **Reglas**.
4. Comprobar que existe un selector de variable fuera del modal de creación/edición de reglas.
5. Crear varias reglas usando una misma variable.
6. Cambiar la variable seleccionada y verificar que las reglas no desaparecen.
7. Quitar la variable seleccionada, si la UI lo permite, y comprobar que las reglas siguen existiendo.

### Resultado esperado

La variable se selecciona una sola vez fuera del modal. Las reglas no se pierden al cambiar o quitar la variable.

### Contexto original útil

**Problema o necesidad:**

En SCADA, en la coloración dinámica de una forma, tenemos 3 opciones: Reglas, Estados y Escala.

- Actualmente en "Estados" y "Escala" se puede seleccionar una variable de manera "externalizada", es decir, dentro de ese menú seleccionas la variable X y luego aplicas todos los estados o escalas a esa misma variable sin tener que seleccionar la misma variable por cada nuevo estado o escala que crees.

- En cambio, en "Reglas" no existe selector "externalizado", sino que cuando decides crear una regla nueva, debes selecionar la variable dentro del modal, y debes hacerlo por cada regla nueva que quieras crear. Esto genera una ralentización a la hora de crear nuevas reglas y además da pie a poder hacer errores al tener que seleccionar muchas veces la misma variable.

**Solución propuesta:**

El selector de la variable debe ser externalizado del modal actual, igual que en Estados y Escala y así poder seleccionar la variable sobre la que queremos aplicar las reglas una única vez y luego solo tener que crear/editar las reglas. Esto supondría una mejora en velocidad y precisión a la hora de generar nuevos SCADA, nuevas reglas y nuevas formas con coloración dinámica.

**Criterios de aceptación:**

- El selector de variables ha sido externalizado.
- En "Reglas" se puede seleccionar una variable antes de generar una regla.
- Cuando ya tienes X reglas generadas, puedes cambiar la variable sin afectar a las reglas.
- Las reglas no desaparecen si no tienes variable seleccionada.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-140"></a>
## 7. #140 — [Feature]  Cambiar configuración color forma people_count en Carlos III

**URL:** https://github.com/captia-technology/captia.ai/issues/140
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** S
**Assignees:** Yordaw
**Labels:** enhancement
**Área:** Frontend / UI
**Severidad/Prioridad:** Baja (nice-to-have)

### Qué tiene que validar el QA tester

Que la forma `people_count` en Carlos III no muestra un color verde por defecto cuando no hay valor.

### Pasos en la aplicación

1. Entrar en el entorno/tenant de **Carlos III**.
2. Abrir las aulas o SCADAs donde exista la forma `people_count`.
3. Revisar la configuración de color de esa forma.
4. Comprobar el comportamiento cuando no hay valor disponible.
5. Comparar el color mostrado con el comportamiento esperado por la configuración.

### Resultado esperado

Cuando no hay valor, la forma no debe mostrarse en verde de forma confusa. Debe mostrarse según la configuración corregida.

### Contexto original útil

**Problema o necesidad:**

La forma tiene por defecto el valor de verde y cuando no hay valor se representa de esta manera dando lugar a confusión.

**Solución propuesta:**

Cambiar la configuración de este widget en las aulas necesarias

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-119"></a>
## 8. #119 — [Bug]  Error Typescript al cargar SCADA en Carlos III

**URL:** https://github.com/captia-technology/captia.ai/issues/119
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Crítico (bloquea funcionalidad principal)

### Qué tiene que validar el QA tester

Que al cargar un SCADA de aula en Carlos III no aparece el error de TypeScript/JavaScript indicado.

### Pasos en la aplicación

1. Abrir la consola del navegador.
2. Entrar en el entorno/tenant de **Carlos III**.
3. Cargar un SCADA de aula.
4. Esperar a que cargue completamente.
5. Revisar si aparece `RangeError: Invalid array length` u otro error relacionado.

### Resultado esperado

El SCADA carga sin errores en consola y sin romper la pantalla.

### Contexto original útil

**Descripción del problema:**

Al cargar un SCADA de aula me aparece este error en la consola:

Uncaught (in promise) RangeError: Invalid array length
    at Array.push (<anonymous>)
    at t2.value (chunk-NKPBUHS7.js?v=4235e6bf:5455:24)
    at t2.value (chunk-NKPBUHS7.js?v=4235e6bf:5483:406)
    at t2.value (chunk-NKPBUHS7.js?v=4235e6bf:5605:101)
    at t2.value (chunk-NKPBUHS7.js?v=4235e6bf:5547:14)
    at t2.value (chunk-NKPBUHS7.js?v=4235e6bf:9289:26)
    at t2.value (chunk-NKPBUHS7.js?v=4235e6bf:9915:462)
    at t2.create (chunk-NKPBUHS7.js?v=4235e6bf:474:21)
    at chunk-NKPBUHS7.js?v=4235e6bf:9980:23
    at new Promise (<anonymous>)

**Comportamiento esperado:**

No debería dar error

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-114"></a>
## 9. #114 — [Bug]  En la pantalla "Cuenta" la accion "Revocar acceso" (intentar eliminar un miembro de tu equipo) no funciona correctamente

**URL:** https://github.com/captia-technology/captia.ai/issues/114
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Crítico (bloquea funcionalidad principal)

### Qué tiene que validar el QA tester

Que la acción **Revocar acceso** en Cuenta funciona correctamente.

### Pasos en la aplicación

1. Entrar en **Cuenta**.
2. Ir al bloque **Tu equipo**.
3. Usar un usuario de prueba si está disponible.
4. Pulsar **Revocar acceso**.
5. Comprobar si el usuario desaparece o si la UI refleja correctamente el cambio.
6. Revisar si el contador de miembros se actualiza.

### Resultado esperado

La acción debe reflejar correctamente la revocación en la UI y actualizar el estado del equipo sin dejar datos inconsistentes.

### Contexto original útil

**Descripción del problema:**

Al intentar eliminar un miembro en la pantalla Cuenta en la parte de "Tu equipo" no desaparece y actualiza el contador de miembros actualizando el estado del botón.

Debería eliminar el usuario?, que funcionalidad debería implementar esta acción?

El caso en el que hemos descubierto el mal funcionamiento ha sido al añadir usuarios de prueba para comprobar el cambio de estado en el botón de invitar. Después no hemos podido eliminar las pruebas para dejarlo como estaba anteriormente.

**Comportamiento esperado:**

Hay que investigar sobre el comportamiento deseado: eliminar directamente el usuario?, enviarle un correo electronico para informar de que no tiene acceso y eliminarlo, etc.

**Screenshots / Videos:**

Peticion que envia el boton Revocar acceso:

<img width="523" height="118" alt="Image" src="https://github.com/user-attachments/assets/c1fa2d07-0b8e-4afe-9d68-0d7a645c226e" />

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-71"></a>
## 10. #71 — [BUG] En Workflows: Cuando se exporta un workflow de un tenant y se importa en otro tenant diferente (export: simarro → import: carlos iii) el json se lleva datos del tenant del que se exporta y luego hay conflicto cuando se importa en el otro. No muestra variables disponibles, no permite cambiarlas etc.

**URL:** https://github.com/captia-technology/captia.ai/issues/71
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** bug, area:backend, priority:high

### Qué tiene que validar el QA tester

Que al exportar un workflow de un tenant e importarlo en otro no se arrastran datos del tenant origen.

### Pasos en la aplicación

1. Entrar en un tenant origen con un workflow de prueba.
2. Exportar el workflow.
3. Entrar en un tenant destino distinto.
4. Importar el workflow.
5. Abrir la configuración del workflow importado.
6. Comprobar que se pueden seleccionar variables del tenant destino y que no aparecen datos bloqueantes del tenant origen.

### Resultado esperado

El workflow importado debe poder configurarse con variables del tenant destino, sin conflictos ni referencias incorrectas al tenant origen.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-68"></a>
## 11. #68 — [BUG] SCADA: cuando hay mucho widget tarda en cargar la imagen de fondo, primero la carga con un tamaño ampliado, y se ajusta más tarde. O directamente no se carga con la resolución adecuada y se queda ampliada sin respetar la proporción.

**URL:** https://github.com/captia-technology/captia.ai/issues/68
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** bug, area:frontend, priority:medium

### Qué tiene que validar el QA tester

Que la imagen de fondo en SCADA carga con tamaño y proporción correctos aunque haya muchos widgets.

### Pasos en la aplicación

1. Abrir un SCADA con muchos widgets.
2. Observar la carga inicial de la imagen de fondo.
3. Recargar varias veces la página.
4. Comprobar si la imagen aparece ampliada, deformada o tarda en ajustarse.
5. Probar con conexión normal y, si es posible, con recarga forzada.

### Resultado esperado

La imagen de fondo debe cargar con la resolución y proporción correctas desde el inicio o sin producir una experiencia visual incorrecta.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-113"></a>
## 12. #113 — [Bug]  Comprobar implantacion de libreria Chackra UI en la pantalla "Cuenta"

**URL:** https://github.com/captia-technology/captia.ai/issues/113
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** Yordaw
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Bajo (problema cosmético o menor)

### Qué tiene que validar el QA tester

Que la pantalla Cuenta usa correctamente los componentes de Chakra UI.

### Pasos en la aplicación

1. Entrar en **Cuenta**.
2. Revisar el bloque **Tu equipo**.
3. Comprobar el tooltip del botón **Límite alcanzado** si aparece.
4. Revisar botones, modales, tooltips, selects y estados visuales de la pantalla.
5. Anotar cualquier componente que se vea desalineado, roto o con comportamiento extraño.

### Resultado esperado

Los componentes de Chakra UI deben verse y comportarse correctamente en toda la pantalla Cuenta.

### Contexto original útil

**Descripción del problema:**

Al trabajar sobre la pantalla Cuenta se identifica que no se usan correctamente los componentes de la libreria Chackra UI.

Por ejemplo: El tooltip del boton "Limite alcanzado" no se visualiza correctamente

Comprobar toda la pantalla y corregir su implantacion en ella.

Es posible mejorar las rules, specs, skills para que lo aplique siempre?. Buen momento para investigarlo.

**Comportamiento esperado:**

La libreria chackra UI debe estar bien implantada en la pantalla

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-98"></a>
## 13. #98 — [CHORE] kpis en tarjeta, auditar y que funcione correctamente

**URL:** https://github.com/captia-technology/captia.ai/issues/98
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** area:frontend, priority:medium, chore

### Qué tiene que validar el QA tester

Que los KPIs en tarjeta se muestran y funcionan correctamente.

### Pasos en la aplicación

1. Entrar en la zona donde se configuran o visualizan tarjetas KPI.
2. Abrir una tarjeta KPI existente o crear una de prueba.
3. Comprobar que carga el valor correcto.
4. Cambiar configuración si está disponible.
5. Recargar la pantalla y verificar que el KPI sigue funcionando.

### Resultado esperado

Las tarjetas KPI deben mostrar datos correctos y mantener un comportamiento estable.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-101"></a>
## 14. #101 — [CHORE] Mejorar menu derecha widget analytics + elementos scada

**URL:** https://github.com/captia-technology/captia.ai/issues/101
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** area:frontend, priority:medium, chore

### Qué tiene que validar el QA tester

Que el menú derecho de widgets analytics y elementos SCADA funciona correctamente.

### Pasos en la aplicación

1. Entrar en una pantalla editable con widgets analytics o elementos SCADA.
2. Seleccionar un widget o elemento.
3. Abrir el menú derecho de configuración.
4. Revisar opciones, tamaños, scroll, botones y estados.
5. Aplicar algún cambio de prueba y comprobar que se guarda correctamente.

### Resultado esperado

El menú derecho debe ser usable, claro y no romper la configuración de widgets o elementos.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-74"></a>
## 15. #74 — [BUG] No muestra algunos objetos al cargar la pantalla, por ejmplo, en alguna aula no carga el fondo derecho de los widgets del grafico, al recargar la pagina si que se muestra.

**URL:** https://github.com/captia-technology/captia.ai/issues/74
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** S
**Assignees:** pascuord
**Labels:** bug, area:frontend, priority:medium

### Qué tiene que validar el QA tester

Que al cargar una pantalla SCADA se muestran todos los objetos sin necesidad de recargar.

### Pasos en la aplicación

1. Entrar en un SCADA donde se haya detectado el problema.
2. Observar la primera carga completa.
3. Comprobar si faltan fondos, objetos o partes de widgets.
4. Recargar la página y comparar el resultado.
5. Repetir la prueba varias veces.

### Resultado esperado

Todos los objetos deben mostrarse correctamente en la primera carga.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-108"></a>
## 16. #108 — [Bug]  Pantalla Tareas se queda en blanco

**URL:** https://github.com/captia-technology/captia.ai/issues/108
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** XS
**Assignees:** pascuord
**Labels:** bug, Tareas
**Área:** Frontend / UI
**Severidad/Prioridad:** Crítico (bloquea funcionalidad principal)

### Qué tiene que validar el QA tester

Que la pantalla Tareas no se queda en blanco en producción.

### Pasos en la aplicación

1. Entrar en producción.
2. Abrir la pantalla **Tareas**.
3. Esperar a la carga completa.
4. Comprobar si aparece pantalla en blanco.
5. Revisar consola del navegador si falla.

### Resultado esperado

La pantalla Tareas debe cargar contenido y no quedarse en blanco.

### Contexto original útil

**Descripción del problema:**

Al entrar a la pantalla Tareas se queda en blanco pero solo en producción.

**Comportamiento esperado:**

No tiene que mostrar pantalla en blanco, deberia de cargar la pantalla de Tareas

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-93"></a>
## 17. #93 — [CHORE] Ajustar tamaño boton tres puntos del widget en escena, condiciona el tamaño del header, cuando no esta el header es menos alto

**URL:** https://github.com/captia-technology/captia.ai/issues/93
**Estado GitHub:** OPEN
**Prioridad proyecto:** P1
**Size:** M
**Assignees:** Yordaw
**Labels:** area:frontend, priority:low, chore

### Qué tiene que validar el QA tester

Que el botón de tres puntos del widget no provoca problemas de tamaño en el header del widget.

### Pasos en la aplicación

1. Entrar en una escena con widgets.
2. Localizar widgets con header y sin header.
3. Revisar el tamaño del botón de tres puntos.
4. Comprobar si el header cambia de altura por culpa del botón.
5. Comparar el comportamiento en distintos tamaños de widget.

### Resultado esperado

El botón de tres puntos debe tener un tamaño coherente y no debe alterar indebidamente la altura del header.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-95"></a>
## 18. #95 — [CHORE] Eliminar 'Plano (borde sutil)'

**URL:** https://github.com/captia-technology/captia.ai/issues/95
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** S
**Assignees:** pascuord
**Labels:** area:frontend, priority:low, chore

### Qué tiene que validar el QA tester

Que la opción **Plano (borde sutil)** ya no aparece o no se puede usar.

### Pasos en la aplicación

1. Entrar en la configuración visual donde existía la opción.
2. Abrir el selector de estilos o variantes.
3. Buscar **Plano (borde sutil)**.
4. Comprobar que no aparece o que ha sido sustituida correctamente.
5. Verificar que no quedan elementos existentes usando esa opción de forma incorrecta.

### Resultado esperado

La opción **Plano (borde sutil)** debe estar eliminada o correctamente sustituida.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-102"></a>
## 19. #102 — [BUG] Hover en widget transparente aparece primero icono tres puntos y despues lupa

**URL:** https://github.com/captia-technology/captia.ai/issues/102
**Estado GitHub:** OPEN
**Prioridad proyecto:** P1
**Size:** M
**Assignees:** Yordaw
**Labels:** bug, area:frontend, priority:low

### Qué tiene que validar el QA tester

Que el hover en widgets transparentes muestra los iconos en el orden y momento correctos.

### Pasos en la aplicación

1. Entrar en una pantalla con un widget transparente.
2. Mover el ratón sobre el widget.
3. Observar qué iconos aparecen primero.
4. Comprobar el comportamiento del icono de tres puntos y de la lupa.
5. Repetir la prueba en distintos widgets transparentes.

### Resultado esperado

El hover debe mostrar los iconos de forma consistente y sin aparición incorrecta del menú de tres puntos antes de la lupa.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-107"></a>
## 20. #107 — [Feature] Al abrir un Dashboard que aparezca la barra superior por defecto

**URL:** https://github.com/captia-technology/captia.ai/issues/107
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** S
**Assignees:** Yordaw
**Labels:** enhancement, area:frontend, priority:low, Dashboard
**Área:** Frontend / UI
**Severidad/Prioridad:** Baja (nice-to-have)

### Qué tiene que validar el QA tester

Que al abrir un Dashboard se muestra la barra superior por defecto.

### Pasos en la aplicación

1. Entrar en la sección **Dashboards**.
2. Abrir un dashboard existente.
3. Comprobar si la barra superior aparece desde el inicio.
4. Verificar que el botón de editar está visible o accesible como en SCADA.

### Resultado esperado

Al abrir un Dashboard debe verse la barra superior por defecto.

### Contexto original útil

**Problema o necesidad:**

Al abrir un dashboard no aparece la barra superior y para editar hay que abrir la barra y despues click en el boton de editar. Esto no lo queremos. El funcionamiento en SCADA es diferente. Los tenemos que igualar cogiendo como referencia a SCADA. En SCADA al abrir se visualiza el boton editar.

**Solución propuesta:**

Igualar funcionamiento como en SCADA. Es decir que al abrir Dashboard que se visualice la barra superior.

**Criterios de aceptación:**

- [x] Al abrir dashboard se visualiza la barra superior

**Alternativas consideradas:**

Comprobar si la unificacion de visualizacion entre barras SCADA y Dashboard esta realizada

**Contexto adicional:**

<img width="3183" height="106" alt="Image" src="https://github.com/user-attachments/assets/ae1b5985-d7e9-4168-a119-8bdd6efc59d8" />

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-133"></a>
## 21. #133 — [Bug]  Error al cargar la imagen de SCADA

**URL:** https://github.com/captia-technology/captia.ai/issues/133
**Estado GitHub:** CLOSED
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Medio (afecta UX pero hay workaround)

### Qué tiene que validar el QA tester

Que al cargar la imagen de SCADA no aparece el error `ERR_FILE_NOT_FOUND`.

### Pasos en la aplicación

1. Abrir la consola del navegador.
2. Entrar en un SCADA con imagen de fondo.
3. Recargar la pantalla.
4. Observar si la imagen carga correctamente.
5. Revisar si aparece `GET blob... net::ERR_FILE_NOT_FOUND`.

### Resultado esperado

La imagen de SCADA debe cargar sin mostrar ese error en consola.

### Contexto original útil

**Descripción del problema:**

Error al cargar la imagen de SCADA

Despues la carga correctamente

Error en consola:

GET blob:http://127.0.0.1:5173/b612c1ca-393c-4d0a-8cdf-ed448928a0a9 net::ERR_FILE_NOT_FOUND

**Comportamiento esperado:**

Eliminar el error

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-141"></a>
## 22. #141 — [Feature]  Comprobacion de pilotos en SCADA

**URL:** https://github.com/captia-technology/captia.ai/issues/141
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** Yordaw
**Labels:** enhancement
**Área:** Frontend / UI
**Severidad/Prioridad:** Media (mejora valiosa)

### Qué tiene que validar el QA tester

Que los pilotos en SCADA representan correctamente su estado y que la mejora propuesta es usable.

### Pasos en la aplicación

1. Entrar en un SCADA con pilotos.
2. Identificar pilotos con diferentes estados.
3. Comprobar si el estado visual coincide con el estado real.
4. Si existe configuración de imágenes por estado, probarla.
5. Anotar si el comportamiento actual es suficiente o si faltan casos.

### Resultado esperado

Los pilotos deben representar claramente el estado. Si hay imágenes por estado, deben cambiar correctamente.

### Contexto original útil

**Problema o necesidad:**

Comprobar el funcionamiento de los pilotos y añadir posible mejora para poder utilizar diferentes imagenes dependiendo del estado

**Solución propuesta:**

Auditar el componente y aplicar la mejora teniendo en cuenta el estado del arte de esta nueva propiedad. Es decir, investigar si existe algún procedimiento ya existente utilizado en otro sistema para este tipo de representaciones de la información.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-165"></a>
## 23. #165 — [Bug]  Error al cargar la pagina /task en Carlos III

**URL:** https://github.com/captia-technology/captia.ai/issues/165
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** S
**Assignees:** pascuord
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Bajo (problema cosmético o menor)

### Qué tiene que validar el QA tester

Que la página `/task` o la pantalla de inicio relacionada no lanza el error minificado de React.

### Pasos en la aplicación

1. Abrir la consola del navegador.
2. Entrar en el entorno de **Carlos III**.
3. Cargar la página `/task` y también la página de inicio si está relacionada.
4. Esperar a que cargue completamente.
5. Revisar si aparece `Minified React error #310` u otro error similar.

### Resultado esperado

La página debe cargar sin errores de React y sin romper componentes.

### Contexto original útil

**Descripción del problema:**

Error al cargar la pagina tareas desde el servidor Carlos III

Error:

Uncaught Error: Minified React error #310; visit https://reactjs.org/docs/error-decoder.html?invariant=310 for the full message or use the non-minified dev environment for full errors and additional helpful warnings.
    at Le (vendor-react-DrGIB4uI.js:30:17533)
    at Object.ec [as useMemo] (vendor-react-DrGIB4uI.js:30:21195)
    at O.useMemo (vendor-react-DrGIB4uI.js:9:6193)
    at ne (AssetSummaryTableWidget-BlzQ1fqn.js:1:2878)
    at $u (vendor-react-DrGIB4uI.js:30:16959)
    at Qo (vendor-react-DrGIB4uI.js:32:3134)
    at Nc (vendor-react-DrGIB4uI.js:32:44485)
    at _c (vendor-react-DrGIB4uI.js:32:39513)
    at op (vendor-react-DrGIB4uI.js:32:39444)
    at hl (vendor-react-DrGIB4uI.js:32:39302)

**Comportamiento esperado:**

Eliminar el error en inicio

**Screenshots / Videos:**

<img width="800" height="201" alt="Image" src="https://github.com/user-attachments/assets/6b8d8b93-d8de-4079-b316-85f9c3de224d" />

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-169"></a>
## 24. #169 — [Bug]  Arreglar selector de Rol en pestaña cuenta

**URL:** https://github.com/captia-technology/captia.ai/issues/169
**Estado GitHub:** OPEN
**Prioridad proyecto:** P1
**Size:** XS
**Assignees:** Yordaw
**Labels:** bug, priority:low, frontend
**Área:** Frontend / UI
**Severidad/Prioridad:** Bajo (problema cosmético o menor)

### Qué tiene que validar el QA tester

Que el selector de rol en Cuenta muestra correctamente el rol actual cuando Firebase contiene `ADMIN_TENANT`.

### Pasos en la aplicación

1. Entrar en **Cuenta**.
2. Ir a **Tu equipo**.
3. Localizar un usuario con rol `ADMIN_TENANT` si existe.
4. Comprobar el valor mostrado en el selector de rol.
5. Verificar que aparece como **Administrador** o el nombre correcto definido por la UI.

### Resultado esperado

Los usuarios con `ADMIN_TENANT` deben aparecer con el rol correcto seleccionado.

### Contexto original útil

**Descripción del problema:**

En la pestaña Cuenta de captia.ai, cuanto vamos  al bloque "Tu Equipo", el selector de Rol no muestra rol actual si es TENANT_ADMIN ya que en firebase es ADMIN_TENANT. Es decir, al no coincidir exactamente el Rol, no muestra correctamente

**Comportamiento esperado:**

Al abrir Cuenta, los roles con ADMIN_TENANT en firebase, deberian tener seleccionado "Administrador" en el selector de rol.

**Screenshots / Videos:**

Firebase:

<img width="262" height="46" alt="Image" src="https://github.com/user-attachments/assets/fcbad846-83c0-43a6-8c19-494a5c49e90d" />

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-181"></a>
## 25. #181 — [Bug]  Se puede elegir variables de otro tennant

**URL:** https://github.com/captia-technology/captia.ai/issues/181
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** S
**Assignees:** pascuord
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Crítico (bloquea funcionalidad principal)

### Qué tiene que validar el QA tester

Que al seleccionar variables desde un widget solo aparecen variables del tenant actual.

### Pasos en la aplicación

1. Entrar con un tenant de prueba.
2. Abrir la configuración de un widget que permita seleccionar variables.
3. Abrir el selector de variables.
4. Comprobar las aulas/variables disponibles.
5. Verificar que no aparecen variables ni aulas de otros tenants.

### Resultado esperado

El selector debe mostrar solo variables del tenant actual.

### Contexto original útil

**Descripción del problema:**

Al seleccionar una variable desde un widget se pueden seleccionar variables de otro tennat

**Comportamiento esperado:**

Solo mostramos las variables del tennant. Lo esta haciendo bien en la pantalla variables, dentro de realtime cuando seleccionas

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-182"></a>
## 26. #182 — [Feature]  Añadir un pop-up en el selector de rol en Cuenta para que pregunte al hacer un cambio de rol

**URL:** https://github.com/captia-technology/captia.ai/issues/182
**Estado GitHub:** OPEN
**Prioridad proyecto:** P2
**Size:** S
**Assignees:** Yordaw
**Labels:** enhancement, priority:medium, frontend
**Área:** Frontend / UI
**Severidad/Prioridad:** Media (mejora valiosa)

### Qué tiene que validar el QA tester

Que al cambiar un rol en Cuenta aparece un pop-up de confirmación y se respeta confirmar/cancelar.

### Pasos en la aplicación

1. Entrar en **Cuenta > Tu equipo**.
2. Abrir el selector de rol de un usuario de prueba.
3. Seleccionar un rol diferente al actual.
4. Comprobar que aparece un pop-up de confirmación.
5. Probar **Cancelar** y verificar que no cambia el rol.
6. Repetir y probar **Confirmar** para verificar que sí cambia el rol.

### Resultado esperado

El cambio de rol no debe aplicarse directamente sin confirmación. Cancelar no cambia nada y confirmar solo afecta al usuario seleccionado.

### Contexto original útil

**Problema o necesidad:**

En captia.ai, en la ventana de Cuenta/Tu Equipo, cuando se despliega el selector de rol, si se pulsa sobre un rol que no es el actual, se aplica el cambio directamente. No hay una pregunta de seguridad del estilo: "Vas a cambiar el Rol X a Rol Y, estás seguro de esto?"
Esto produce que se pueda hacer un cambio el cual suponga perdida de permisos y utilidades por culpa de un error.

**Solución propuesta:**

Al seleccionar un rol diferente al actual, deberia salir un pop-up que te pregunte si estás seguro. Si hay confirmación aplicar los cambios y si hay negación, dejar el rol actual y no hacer nada.

**Criterios de aceptación:**

- [ ] Al cambiar de rol desde el selector, aparece un pop up
- [ ] Al confirmar, hace el cambio
- [ ] Al cancelar, cierra el pop up y no aplica cambios sobre el rol
- [ ] Solo afecta al usuario elegido, el resto no se ven afectados

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-183"></a>
## 27. #183 — [Feature]  Crear un widget Slider para representar las consignas

**URL:** https://github.com/captia-technology/captia.ai/issues/183
**Estado GitHub:** OPEN
**Prioridad proyecto:** P1
**Size:** L
**Assignees:** Yordaw
**Labels:** enhancement, priority:high, Scada, chore
**Área:** Backend / API
**Severidad/Prioridad:** Alta (necesidad importante)

### Qué tiene que validar el QA tester

Que el widget Slider para consignas funciona sin saturar el sistema.

### Pasos en la aplicación

1. Entrar en un SCADA donde esté disponible el widget Slider o los controles de consigna.
2. Crear o localizar un Slider de prueba.
3. Mover el Slider y comprobar cómo se envía la consigna.
4. Verificar si existe confirmación, debounce, bloqueo temporal o feedback de “Aplicando…”.
5. Comprobar que la variable de lectura refleja el estado real.
6. Intentar cambios rápidos repetidos y verificar que el sistema no se satura.

### Resultado esperado

El Slider debe enviar consignas de forma controlada, reflejar el estado real y evitar spam de peticiones.

### Contexto original útil

**Problema o necesidad:**

En SCADA actualmente las consignas funcionan con input numerico. Se necesita un slider (barra de progreso) la cual simbolice el % o valor igual que lo hace la consigna de input pero deslizando.
Deberia enviar un valor a la variable de escritura y deberia tener una variable de lectura la cual represente el % en ese momento y siempre.

**Solución propuesta:**

Auditar completamente el sistema de acciones en SCADA.
Actualmente está el problema del "delay" al enviar una acción. Esto hace que al pulsar un toggle, la respuesta no sea inmediata, con lo cual esto combinado con un "slider" puede convertirse en un problema.
Hay que auditar todo para ver si se puede adaptar los controles de scada de manera que no haya "pulling" sino que sea un "websocket" o "suscripcion" la cual haga un efecto inmediato frente a un cambio. Es decir, actualmente parece haber un pulling constante cada X tiempo, pero al haber una accion deberia ser otro thread el cual haga que el cambio sea inmediato.

**Criterios de aceptación:**

- [ ] Los slider-botones funcionan y envian consigna
- [ ] Los usuarios no pueden saturar el sistema con peticiones tipo: on, off , on , on , off, off , de manera seguida y constante

**Alternativas consideradas:**

## Ventiladores (3 velocidades)

Para ventiladores con 3 velocidades, no tiene sentido un control continuo.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-187"></a>
## 28. #187 — Auditar prioridad de reglas de coloración en SCADA para descartar solapamientos de rangos

**URL:** https://github.com/captia-technology/captia.ai/issues/187
**Estado GitHub:** OPEN
**Prioridad proyecto:** P1
**Size:** M
**Assignees:** Yordaw
**Labels:** priority:medium, Tareas, frontend

### Qué tiene que validar el QA tester

Que la prioridad de reglas de coloración en SCADA resuelve correctamente rangos solapados.

### Pasos en la aplicación

1. Entrar en un SCADA editable.
2. Configurar o localizar reglas con rangos solapados, por ejemplo `temp > 20` y `temp > 26`.
3. Asignar prioridades diferentes a esas reglas.
4. Probar valores que entren en ambos rangos.
5. Comprobar qué color/regla se aplica.
6. Cambiar prioridades y repetir la prueba.

### Resultado esperado

Cuando varias reglas coinciden, debe aplicarse la regla con la prioridad correcta y sin comportamiento ambiguo.

### Contexto original útil

**Descripción:**

En SCADA actualmente hay reglas que contienen rangos los cuales podrian entrar en conflicto con otras reglas. Ej: (temp > 20º = OPTIMA), pero a la vez (temp > 26º = ALTA) aquí la segunda engloba tambien a la primera, con lo cual podria haber un conflicto de coloración y aplicación de la regla correcta. Hay que auditar para ver si se aplicacan bien o no. Además, hay que auditar si la "prioridad" en las reglas funciona correctamente y si el hecho de dar más prioridad a una que a otra genera correctamente esa prioridad o no.

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-191"></a>
## 29. #191 — [Bug] No se pueden elegir todos los widgets disponibles del listado

**URL:** https://github.com/captia-technology/captia.ai/issues/191
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** S
**Assignees:** pascuord
**Labels:** bug
**Área:** Frontend / UI
**Severidad/Prioridad:** Crítico (bloquea funcionalidad principal)

### Qué tiene que validar el QA tester

Que se pueden seleccionar e insertar todos los widgets del listado.

### Pasos en la aplicación

1. Entrar en una pantalla donde se puedan añadir widgets.
2. Abrir el listado de widgets disponibles.
3. Probar varios tipos, especialmente **Rich Text**.
4. Añadir cada widget de prueba a la pantalla.
5. Comprobar que el widget insertado corresponde al tipo seleccionado.

### Resultado esperado

Al elegir un tipo de widget, debe insertarse ese tipo exacto. Por ejemplo, Rich Text no debe convertirse en Text.

### Contexto original útil

**Descripción del problema:**

Al añadir widgets del listado, hay algunos que no se pueden insertar. Por ejemplo si añdes rich text te lo pasa a text.

**Comportamiento esperado:**

Se tiene que poder elegir todo tipo de widgets

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-193"></a>
## 30. #193 — [Feature] Los graficos en informes no deberian tener tooltip en el hover

**URL:** https://github.com/captia-technology/captia.ai/issues/193
**Estado GitHub:** OPEN
**Prioridad proyecto:** P0
**Size:** M
**Assignees:** pascuord
**Labels:** enhancement
**Área:** Frontend / UI
**Severidad/Prioridad:** Media (mejora valiosa)

### Qué tiene que validar el QA tester

Que los gráficos de Informes no muestran tooltip en hover cuando no corresponde.

### Pasos en la aplicación

1. Entrar en **Informes**.
2. Abrir un informe con gráficos.
3. Pasar el ratón por encima de los gráficos.
4. Comprobar si aparece tooltip.
5. Si existe configuración para mostrar/ocultar tooltip, cambiarla y repetir la prueba.

### Resultado esperado

Los gráficos no deben mostrar tooltip en contextos donde se haya definido que no corresponde, o deben respetar la configuración del widget.

### Contexto original útil

**Problema o necesidad:**

En algunos contextos no tiene sentido que aparezca el tooltip de los graficos

**Solución propuesta:**

Investigar si crear la restriccion en cada pantalla o añadir una opcion a la configuracion del widget donde puedas elegir mostrar o no el tooltip

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---

<a id="issue-194"></a>
## 31. #194 — [Feature]  Estandarizar el campo "Descripcion" en los diferentes menús de captia.ai

**URL:** https://github.com/captia-technology/captia.ai/issues/194
**Estado GitHub:** OPEN
**Prioridad proyecto:** P2
**Size:** S
**Assignees:** Yordaw
**Labels:** enhancement, area:backend, frontend
**Área:** Frontend / UI
**Severidad/Prioridad:** Baja (nice-to-have)

### Qué tiene que validar el QA tester

Que el campo **Descripción** está estandarizado y que no aparece “Sin descripción” cuando está vacío.

### Pasos en la aplicación

1. Revisar elementos en SCADA, Dashboards, Informes y Automatizaciones.
2. Abrir elementos con descripción y sin descripción.
3. Comprobar cómo se muestra el campo **Descripción**.
4. Verificar que si hay descripción se muestra correctamente.
5. Verificar que si está vacía no aparece el texto **Sin descripción**.

### Resultado esperado

Todos los menús deben tratar la descripción de forma coherente: mostrarla si existe y no mostrar nada si está vacía.

### Contexto original útil

**Problema o necesidad:**

Actualmente todos los elementos sea en SCADA, Dashboards, Informes, Automatizaciones etc. tienen diferentes opciones en el campo Descripcion. Algunos lo tienen otros no.

**Solución propuesta:**

Auditar y estandarizar este campo. Para que todos los elementos lo tengan. Además, si está vación no queremos mostrar "Sin descripcion" sino directamente no mostrar nada. Si la hay, se muestra.

**Criterios de aceptación:**

- [ ] Si el elemento tiene descripción, se muestra.
- [ ] Si el elemento no tiene descripción, no muestra nada.
- [ ] No existe "Sin descripción"

**Contexto adicional:**

<img width="347" height="151" alt="Image" src="https://github.com/user-attachments/assets/be5d2a40-62ea-4d59-91ab-2461045f99f5" />

---

### Reporte del QA tester

- **Resultado:** [ ] OK / Validada  [ ] Falla  [ ] Bloqueada  [ ] No aplica
- **Entorno probado:**
- **Tenant / cliente usado:**
- **Usuario / rol usado:**
- **Fecha de prueba:**
- **Pasos ejecutados:**
- **Resultado observado:**
- **Evidencias:** enlace a captura, vídeo, logs o descripción
- **Observaciones:**
- **Recomendación:** [ ] cerrar issue  [ ] devolver a desarrollo  [ ] necesita aclaración

---
