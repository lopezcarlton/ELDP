# Rapid Grant ELDP — Base de Conocimiento del Proyecto

**Archivo:** `00_README.md`  
**Versión:** 1.0  
**Estado:** Activo  
**Última actualización:** 2026-08-03

---

# ¿Qué es este repositorio?

Este repositorio constituye la **Base de Conocimiento oficial** para el desarrollo de la candidatura de **Voces de las Nubes** al **Rapid Grant** del **Endangered Languages Documentation Programme (ELDP)**.

No es un borrador de la propuesta.

No es un lugar para almacenar ideas.

No es una colección de notas.

Su objetivo es conservar de manera estructurada todo el conocimiento necesario para desarrollar la candidatura sin depender del historial de conversaciones entre modelos de lenguaje.

Todos los documentos de este repositorio cumplen una función específica y deben mantenerse sincronizados.

---

# Objetivo

Construir una candidatura altamente competitiva al Rapid Grant del ELDP mediante un proceso sistemático de investigación, consolidación del conocimiento y diseño del proyecto.

La propuesta final será redactada posteriormente utilizando esta Base de Conocimiento como única fuente de verdad.

---

# Alcance

Esta Base de Conocimiento cubre exclusivamente la preparación de la candidatura al Rapid Grant.

No documenta todo el proyecto Voces de las Nubes.

La visión institucional del proyecto únicamente aparece cuando resulta necesaria para comprender el contexto de la candidatura.

---

# Principios generales

## 1. Una única fuente de verdad

Cada tipo de información existe en un único documento.

Nunca debe duplicarse información entre documentos.

Si una información pertenece a otro archivo, se referencia, pero no se copia.

---

## 2. Las decisiones no viven en los chats

Toda decisión aprobada debe registrarse en:

`02_DECISIONES.md`

Los chats son espacios de trabajo.

La Base de Conocimiento es el registro oficial.

---

## 3. El proyecto no se diseña durante la redacción

La propuesta será redactada únicamente cuando el diseño del proyecto haya sido completamente definido.

La redacción es consecuencia del diseño.

Nunca al revés.

---

## 4. Separación entre conocimiento y creatividad

Esta Base de Conocimiento almacena únicamente información consolidada.

Las ideas nuevas viven temporalmente en:

`10_IDEAS.md`

Una idea solamente pasa a formar parte del proyecto cuando existe una decisión explícita.

---

## 5. La documentación oficial tiene prioridad

Cuando exista una diferencia entre una interpretación previa y la documentación oficial de ELDP, prevalece la documentación oficial.

Las interpretaciones deberán actualizarse en consecuencia.

---

# Arquitectura del repositorio

```text
Rapid Grant ELDP/

00_README.md
01_DASHBOARD.md
02_DECISIONES.md
03_ASSUMPTIONS.md
04_ELDP.md
05_PROYECTO.md
06_BACKLOG.md
07_GLOSARIO.md
08_EVIDENCIAS.md
09_BITACORA.md
10_IDEAS.md
```

---

# Descripción de los documentos

## 00_README.md

Explica cómo utilizar la Base de Conocimiento.

Debe leerse primero.

---

## 01_DASHBOARD.md

Resume el estado actual del proyecto.

Debe responder únicamente:

- ¿Dónde estamos?
- ¿Qué estamos haciendo?
- ¿Cuál es el cuello de botella?
- ¿Cuál es la siguiente decisión importante?

No contiene conocimiento permanente.

---

## 02_DECISIONES.md

Registro oficial de todas las decisiones del proyecto.

Una decisión registrada aquí permanece vigente hasta que otra decisión la modifique explícitamente.

---

## 03_ASSUMPTIONS.md

Contiene todos los supuestos que todavía no han sido demostrados.

Los supuestos nunca deben presentarse como hechos.

Cuando un supuesto se valida pasa a:

- `02_DECISIONES.md`
- `08_EVIDENCIAS.md`

según corresponda.

---

## 04_ELDP.md

Resumen estructurado de la documentación oficial de ELDP.

No contiene opiniones.

No contiene interpretaciones sin identificar.

Debe distinguir claramente entre:

- hechos documentados;
- inferencias del equipo.

---

## 05_PROYECTO.md

Documento donde vive el diseño del proyecto Rapid Grant.

Incluye:

- problema;
- objetivos;
- metodología;
- actividades;
- productos;
- cronograma;
- presupuesto;
- riesgos.

Este documento se desarrolla únicamente después de completar la fase de diseño.

---

## 06_BACKLOG.md

Lista de trabajo activa del proyecto.

Debe mantenerse pequeña.

No más de diez tareas simultáneas.

---

## 07_GLOSARIO.md

Define la terminología oficial utilizada por el proyecto.

Toda definición metodológica debe vivir aquí.

---

## 08_EVIDENCIAS.md

Relaciona todas las afirmaciones importantes del proyecto con sus fuentes.

Cada evidencia debe indicar:

- afirmación;
- respaldo;
- fuente;
- documento donde se utiliza.

---

## 09_BITACORA.md

Registro cronológico del proyecto.

Cada sesión de trabajo debe registrar:

- fecha;
- decisiones tomadas;
- documentos modificados;
- tareas completadas;
- pendientes.

---

## 10_IDEAS.md

Espacio para explorar nuevas ideas.

Las ideas no forman parte del proyecto hasta que exista una decisión formal.

---

# Jerarquía de fuentes

Cuando dos documentos parezcan estar en conflicto, prevalece el que ocupe la posición más alta en el siguiente orden:

1. `05_PROYECTO.md` — representa el estado oficial y consolidado del diseño del proyecto. Una vez que una decisión o un dato se incorpora aquí, esta es la versión vigente.
2. `02_DECISIONES.md` — gobierna todo lo que `05_PROYECTO.md` aún no ha incorporado. Ninguna sección de `05_PROYECTO.md` puede contradecir una decisión activa sin que exista antes una nueva entrada aquí.
3. `04_ELDP.md` — fija los límites y requisitos externos de la convocatoria. `02_DECISIONES.md` y `05_PROYECTO.md` deben ser compatibles con lo registrado aquí.
4. `08_EVIDENCIAS.md` — respalda las afirmaciones utilizadas en `05_PROYECTO.md` y `04_ELDP.md`. Las afirmaciones del proyecto deberían estar respaldadas por evidencia registrada aquí o por una fuente oficial claramente identificada.
5. `03_ASSUMPTIONS.md` — contiene lo que todavía no tiene respaldo suficiente para pasar a `08_EVIDENCIAS.md` o a una decisión.
6. `10_IDEAS.md` — variantes sin aprobar; no puede citarse como si describiera el proyecto real.
7. `01_DASHBOARD.md`, `06_BACKLOG.md`, `09_BITACORA.md`, `07_GLOSARIO.md` — documentos operativos o derivados; reflejan el estado de los documentos anteriores, pero no lo definen.
8. Historial de chats — nunca es fuente vigente una vez que sus conclusiones quedan incorporadas en este repositorio.

---

# Flujo de trabajo recomendado

Toda sesión debería seguir el siguiente orden:

1. Leer el Dashboard.
2. Revisar las Decisiones vigentes.
3. Consultar ELDP cuando exista una duda sobre la convocatoria.
4. Trabajar.
5. Actualizar la Base de Conocimiento.
6. Cerrar la sesión.

---

# Responsabilidades

## ChatGPT

Responsable de:

- investigación;
- análisis;
- revisión crítica;
- consolidación del conocimiento;
- mantenimiento de la Base de Conocimiento;
- control de consistencia documental.

No define el proyecto piloto salvo instrucción expresa.

---

## Claude

Responsable de:

- exploración de alternativas;
- diseño del proyecto piloto;
- desarrollo conceptual;
- redacción de documentos finales.

Claude debe trabajar utilizando esta Base de Conocimiento como contexto principal.

---

# Estado actual del proyecto

Actualmente el proyecto dispone de:

- documentación metodológica;
- documentos institucionales;
- análisis de la convocatoria ELDP;
- principios para el diseño del corpus;
- backlog inicial;
- decisiones estratégicas consolidadas.

Todavía no se han definido:

- proyecto piloto;
- objetivos específicos;
- actividades;
- entregables;
- cronograma;
- presupuesto.

Estas decisiones se desarrollarán posteriormente y se incorporarán a la Base de Conocimiento una vez aprobadas.

---

# Regla fundamental

La Base de Conocimiento constituye la única fuente oficial de verdad del proyecto.

Cuando exista una contradicción entre un chat y estos documentos, prevalecerá siempre la Base de Conocimiento.
