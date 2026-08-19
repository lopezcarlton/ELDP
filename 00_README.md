# Small Grant ELDP — Base de Conocimiento del Proyecto

**Archivo:** `00_README.md`  
**Versión:** 1.1  
**Estado:** Activo  
**Última actualización:** 2026-08-19

---

# ¿Qué es este repositorio?

Este repositorio constituye la **Base de Conocimiento oficial** para el desarrollo de la candidatura de **Voces de las Nubes** al **Small Grant** del **Endangered Languages Documentation Programme (ELDP)**.

No es un borrador de la propuesta.

No es un lugar para almacenar ideas.

No es una colección de notas.

Su objetivo es conservar de manera estructurada todo el conocimiento necesario para desarrollar la candidatura sin depender del historial de conversaciones entre modelos de lenguaje.

Todos los documentos de este repositorio cumplen una función específica y deben mantenerse sincronizados.

---

# Objetivo

Construir una candidatura altamente competitiva al Small Grant del ELDP mediante un proceso sistemático de investigación, consolidación del conocimiento y diseño del proyecto.

La propuesta final será redactada posteriormente utilizando esta Base de Conocimiento como fuente oficial para la candidatura.

---

# Alcance

Esta Base de Conocimiento cubre exclusivamente la preparación de la candidatura al Small Grant.

No documenta todo el proyecto Voces de las Nubes.

La visión institucional del proyecto únicamente aparece cuando resulta necesaria para comprender el contexto de la candidatura.

El estado lingüístico, pedagógico, metodológico y operativo permanente de Voces de las Nubes se consulta en `lopezcarlton/vocesdelasnubes`. La relación entre ambos repositorios se regula en `11_FUENTES_EXTERNAS_VOCES.md`.

---

# Principios generales

## 1. Una única fuente de verdad por materia

Cada tipo de información existe en una única fuente autoritativa.

Nunca debe duplicarse información entre documentos o repositorios cuando ambos pretendan describir el mismo estado vigente.

Si una información pertenece a otro archivo o repositorio, se referencia, pero no se mantiene aquí una segunda versión como si fuera fuente permanente.

---

## 2. Las decisiones no viven en los chats

Toda decisión aprobada sobre la candidatura debe registrarse en:

`02_DECISIONES.md`

Los chats son espacios de trabajo.

La Base de Conocimiento es el registro oficial de la candidatura.

---

## 3. El proyecto no se diseña durante la redacción

La propuesta será redactada únicamente cuando el diseño del proyecto haya sido suficientemente definido.

La redacción es consecuencia del diseño.

Nunca al revés.

---

## 4. Separación entre conocimiento y creatividad

Esta Base de Conocimiento almacena únicamente información consolidada para la candidatura.

Las ideas nuevas viven temporalmente en:

`10_IDEAS.md`

Una idea solamente pasa a formar parte del proyecto cuando existe una decisión explícita.

---

## 5. La documentación oficial tiene prioridad

Cuando exista una diferencia entre una interpretación previa y la documentación oficial de ELDP, prevalece la documentación oficial.

Las interpretaciones deberán actualizarse en consecuencia.

---

## 6. Voces de las Nubes gobierna el estado del proyecto principal

Cuando la candidatura necesite afirmar el estado de COR001, COR002, metodología, pedagogía, teoría, audio, validación u otros componentes permanentes de Voces de las Nubes, debe consultar `lopezcarlton/vocesdelasnubes`.

Las decisiones de esta candidatura no modifican automáticamente el proyecto principal.

---

# Arquitectura del repositorio

```text
Small Grant ELDP/

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
11_FUENTES_EXTERNAS_VOCES.md
```

---

# Descripción de los documentos

## 00_README.md

Explica cómo utilizar la Base de Conocimiento.

Debe leerse primero.

---

## 01_DASHBOARD.md

Resume el estado actual de la candidatura.

Debe responder únicamente:

- ¿Dónde estamos?
- ¿Qué estamos haciendo?
- ¿Cuál es el cuello de botella?
- ¿Cuál es la siguiente decisión importante?

No contiene conocimiento permanente.

---

## 02_DECISIONES.md

Registro oficial de todas las decisiones de la candidatura.

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

Documento donde vive el diseño del proyecto Small Grant.

Incluye:

- problema;
- objetivos;
- metodología;
- actividades;
- productos;
- cronograma;
- presupuesto;
- riesgos.

Las afirmaciones que dependen del estado de Voces de las Nubes deben verificarse en el repositorio principal antes de consolidarse aquí.

---

## 06_BACKLOG.md

Lista de trabajo activa de la candidatura.

Debe mantenerse pequeña.

No más de diez tareas simultáneas.

---

## 07_GLOSARIO.md

Define la terminología oficial utilizada por la candidatura.

---

## 08_EVIDENCIAS.md

Relaciona las afirmaciones importantes de la candidatura con sus fuentes.

Cada evidencia debe indicar:

- afirmación;
- respaldo;
- fuente;
- documento donde se utiliza.

Cuando la evidencia sea el estado actual de Voces de las Nubes, debe identificarse el repositorio principal y, cuando sea pertinente, la fecha o versión consultada.

---

## 09_BITACORA.md

Registro cronológico del trabajo de la candidatura.

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

## 11_FUENTES_EXTERNAS_VOCES.md

Define la frontera de autoridad entre esta candidatura y el repositorio principal de Voces de las Nubes.

Debe consultarse antes de incorporar afirmaciones sobre el estado del proyecto principal.

---

# Jerarquía de fuentes

La jerarquía interna de este repositorio gobierna **la candidatura**:

1. `05_PROYECTO.md` — representa el estado oficial y consolidado del diseño de la candidatura, siempre que no contradiga una fuente externa autoritativa sobre una materia que este repositorio no gobierna.
2. `02_DECISIONES.md` — gobierna todo lo que `05_PROYECTO.md` aún no ha incorporado.
3. `04_ELDP.md` — fija los límites y requisitos externos de la convocatoria.
4. `08_EVIDENCIAS.md` — respalda las afirmaciones utilizadas en `05_PROYECTO.md` y `04_ELDP.md`.
5. `03_ASSUMPTIONS.md` — contiene lo que todavía no tiene respaldo suficiente.
6. `10_IDEAS.md` — variantes sin aprobar.
7. `01_DASHBOARD.md`, `06_BACKLOG.md`, `09_BITACORA.md`, `07_GLOSARIO.md` — documentos operativos o derivados.
8. Historial de chats — nunca es fuente vigente una vez que sus conclusiones quedan incorporadas en el repositorio correspondiente.

**Excepción de autoridad externa:** para el estado de Voces de las Nubes, prevalece `lopezcarlton/vocesdelasnubes` conforme a `11_FUENTES_EXTERNAS_VOCES.md`.

---

# Flujo de trabajo recomendado

Toda sesión debería seguir el siguiente orden:

1. Leer el Dashboard.
2. Revisar las Decisiones vigentes.
3. Consultar ELDP cuando exista una duda sobre la convocatoria.
4. Si se utilizarán datos sobre el estado de Voces de las Nubes, consultar `11_FUENTES_EXTERNAS_VOCES.md` y el repositorio principal.
5. Trabajar.
6. Actualizar la Base de Conocimiento.
7. Cerrar la sesión.

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

No define decisiones sustantivas del proyecto salvo instrucción expresa del usuario.

---

## Claude

Puede participar en:

- exploración de alternativas;
- desarrollo conceptual;
- redacción de documentos finales.

Debe trabajar utilizando esta Base de Conocimiento y, cuando corresponda, el repositorio principal de Voces de las Nubes como contexto autoritativo.

---

# Estado actual del proyecto

Actualmente el repositorio dispone de:

- documentación metodológica y estratégica para la candidatura;
- documentos institucionales;
- análisis de la convocatoria ELDP;
- backlog y supuestos;
- decisiones estratégicas consolidadas;
- un mapa explícito de autoridad hacia el repositorio principal de Voces de las Nubes.

El diseño sustantivo del Small Grant permanece en desarrollo y debe consolidarse mediante decisiones explícitas.

---

# Regla fundamental

Esta Base de Conocimiento constituye la fuente oficial de verdad **sobre la candidatura al Small Grant**.

No sustituye al repositorio `lopezcarlton/vocesdelasnubes` como fuente de verdad sobre el proyecto principal.

Cuando exista una contradicción, primero debe determinarse qué repositorio gobierna la materia antes de resolverla.
