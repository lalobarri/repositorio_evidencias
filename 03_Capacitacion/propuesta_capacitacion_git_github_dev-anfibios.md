# 🐸 Operación: GitSwamp
### Programa de Capacitación en Git y GitHub — Equipo dev-anfibios

> **Materia:** Desarrollo y Gestión de Software
> **Universidad:** Tecnológica del Norte de Guanajuato (UTNG)
> **Equipo:** dev-anfibios
> **Fecha:** Junio 2026

---

## 🌿 Bienvenida al Pantano Digital

```
╔══════════════════════════════════════════════════════════════╗
║          TRANSMISIÓN ENTRANTE — CUARTEL GENERAL ANFIBIO      ║
║══════════════════════════════════════════════════════════════║
║                                                              ║
║   Bienvenido/a, Desarrollador/a.                             ║
║                                                              ║
║   Los anfibios sobreviven en dos mundos: tierra y agua.      ║
║   Un buen desarrollador también domina dos entornos:         ║
║   el local y el remoto.                                      ║
║                                                              ║
║   Para unirte al escuadrón dev-anfibios deberás superar      ║
║   4 zonas del pantano digital, cada una más profunda         ║
║   que la anterior.                                           ║
║                                                              ║
║   Navega con cuidado. Haz commits frecuentes.                ║
║   El pantano no perdona los cambios sin registrar.           ║
║                                                              ║
║   — Comando Anfibio, Base Remota                             ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 📑 Tabla de Contenidos

1. [Objetivo de Aprendizaje](#1-objetivo-de-aprendizaje)
2. [Descripción de la Dinámica — Operación GitSwamp](#2-descripción-de-la-dinámica--operación-gitswamp)
3. [Zonas del Pantano (Misiones)](#3-zonas-del-pantano-misiones)
4. [Evidencias de Aprendizaje](#4-evidencias-de-aprendizaje)
5. [Criterios de Evaluación](#5-criterios-de-evaluación)
6. [Preguntas de Reflexión](#6-preguntas-de-reflexión)
7. [Desafío Extra — Arsenal Avanzado](#7-desafío-extra--arsenal-avanzado)

---

## 1. Objetivo de Aprendizaje

Al completar la **Operación GitSwamp**, el nuevo Programador Junior será capaz de:

- 🐸 **Configurar su entorno Git** y clonar repositorios remotos de GitHub.
- 🌿 **Crear y gestionar ramas** de desarrollo de forma aislada y organizada.
- 📋 **Registrar cambios incrementales** mediante commits con mensajes descriptivos y convencionales.
- 🔄 **Sincronizar su trabajo** con el repositorio remoto usando `push`, `pull` y `fetch`.
- ⚔️ **Identificar y resolver conflictos de fusión** de manera autónoma en escenarios colaborativos reales.
- 🔀 **Crear Pull Requests completos** con título, descripción, contexto y referencias a cambios.
- 🔍 **Revisar el código de otros desarrolladores** mediante Code Reviews con comentarios constructivos.
- 🗺️ **Comprender el flujo de trabajo Git Flow** básico aplicado en equipos ágiles de desarrollo.

---

## 2. Descripción de la Dinámica — Operación GitSwamp

### 🌊 El universo de la misión

La **Operación GitSwamp** transforma el aprendizaje de Git en una expedición colaborativa por un pantano digital. El Programador Junior toma el rol de un **Desarrollador Anfibio** recién reclutado por el escuadrón **dev-anfibios**, cuya misión es mantener vivo el sistema `swamp-app` — una aplicación web de gestión de expediciones que el equipo desarrolla de forma colaborativa.

> El repositorio es el **pantano**. Las ramas son **caminos propios** por el terreno. Los commits son **huellas registradas** en el barro. Los Pull Requests son **reportes de expedición** que el escuadrón revisa antes de integrar cualquier ruta al mapa principal.

### 👥 Modalidad

| Aspecto | Detalle |
|---------|---------|
| **Participantes** | Equipo dev-anfibios (mínimo 2 integrantes) |
| **Proyecto base** | `swamp-app` — aplicación web ficticia en HTML/CSS/JS |
| **Plataforma** | GitHub (repositorio compartido del equipo) |
| **Formato** | 4 zonas progresivas con sistema de medallas |
| **Rol del facilitador** | Comandante Anfibio (líder técnico del equipo) |
| **Modalidad de trabajo** | Colaborativa — cada integrante tiene su propia rama |

### 🏅 Sistema de Medallas

Cada zona superada otorga una medalla que se registra en el `README.md` del repositorio como historial de logros del escuadrón:

| Medalla | Zona | Nombre |
|---------|------|--------|
| 🐸 | Zona 1 | Renacuajo Digital |
| 🌿 | Zona 2 | Anfibio Constructor |
| 🌊 | Zona 3 | Navegante del Conflicto |
| 🦅 | Zona 4 | Guardián del Repositorio |

### 🏗️ Estructura del proyecto base

```
swamp-app/
├── README.md               ← incompleto, el desarrollador lo termina en Zona 2
├── index.html              ← página principal del sistema
├── css/
│   └── style.css           ← hoja de estilos del proyecto
├── js/
│   ├── expeditions.js      ← módulo con bug intencional (Zona 3)
│   └── members.js          ← módulo vacío para implementar (Zona 2)
├── .gitignore
└── CONTRIBUTING.md         ← protocolo oficial del escuadrón dev-anfibios
```

### 📜 Protocolo del Escuadrón dev-anfibios

```
REGLAS DE OPERACIÓN — ESCUADRÓN dev-anfibios
────────────────────────────────────────────
1. Nadie toca directamente la rama main.
   main es el terreno seguro. Todo pasa por revisión primero.

2. Cada desarrollador trabaja en su propia rama:
   feature/nombre-funcionalidad

3. Los commits deben ser claros y seguir el formato:
   tipo(scope): descripción breve en español

   Tipos válidos: feat, fix, docs, style, refactor, test

4. Ningún cambio llega a main sin un Pull Request aprobado
   por al menos un compañero del escuadrón.

5. Los conflictos se resuelven con comunicación, no con fuerza.
────────────────────────────────────────────
```

---

## 3. Zonas del Pantano (Misiones)

---

### 🐸 ZONA 1 — Renacuajo Digital

> *"Antes de cruzar el pantano, debes conocer el terreno."*

**Objetivo:** Configurar el entorno local y explorar la estructura del proyecto `swamp-app`.

#### Misiones

| # | Misión | Comando principal |
|---|--------|-------------------|
| 1.1 | Crear o iniciar sesión en GitHub. Configurar Git local con nombre de usuario y correo institucional. | `git config --global user.name` `git config --global user.email` |
| 1.2 | Clonar el repositorio `swamp-app` desde la URL compartida por el Comandante Anfibio. | `git clone <url>` |
| 1.3 | Explorar la estructura del proyecto: leer `README.md` y `CONTRIBUTING.md`. Identificar todos los archivos y su propósito. | `ls`, `cat` / explorador de archivos |
| 1.4 | Consultar el historial de cambios del repositorio para entender su evolución. | `git log --oneline --graph` |
| 1.5 | Crear el archivo `bitacora/bitacora_zona1_[tu-nombre].md` con: (a) 3 observaciones del proyecto, (b) 2 comandos Git aprendidos y su utilidad. Registrar ese archivo con un commit. | `git add`, `git commit` |

#### Formato de mensaje de commit esperado

```
docs(bitacora): agrega bitacora de observaciones zona 1 - [nombre]
```

#### Evidencias para la medalla 🐸

- [ ] Captura de terminal mostrando la configuración de Git (`git config --list`).
- [ ] Captura de la clonación exitosa del repositorio.
- [ ] Captura de `git log --oneline --graph` ejecutado en el proyecto.
- [ ] Archivo `bitacora_zona1_[nombre].md` visible en la rama correspondiente de GitHub.

---

### 🌿 ZONA 2 — Anfibio Constructor

> *"El pantano crece con cada contribución. Es tu turno de construir."*

**Objetivo:** Crear una rama propia, implementar funcionalidades reales y mantener un historial limpio de commits.

#### Misiones

| # | Misión | Comando principal |
|---|--------|-------------------|
| 2.1 | Crear y cambiar a una nueva rama con el nombre `feature/[tu-nombre]-members`. | `git checkout -b feature/[nombre]-members` |
| 2.2 | Completar el `README.md`: agregar descripción del proyecto, tecnologías utilizadas, instrucciones de instalación y uso básico. | Editor de texto |
| 2.3 | Implementar en `js/members.js` la función `getMembers()` que retorne un arreglo de al menos 4 miembros ficticios del escuadrón (cada uno con nombre, rol y experiencia). | Editor de texto |
| 2.4 | Registrar los cambios mediante **mínimo 3 commits** atómicos, cada uno enfocado en un cambio específico y siguiendo el protocolo de mensajes. | `git add`, `git commit -m` |
| 2.5 | Publicar la rama en el repositorio remoto para que el escuadrón pueda verla. | `git push origin feature/[nombre]-members` |

#### Ejemplos de commits válidos

```
docs(readme): agrega descripcion general del proyecto swamp-app
feat(members): implementa funcion getMembers con datos del escuadron
docs(readme): completa seccion de instalacion y uso
```

#### Evidencias para la medalla 🌿

- [ ] Captura o enlace al historial de GitHub con 3+ commits siguiendo el protocolo.
- [ ] Captura de la rama publicada visible en la pestaña *Branches* del repositorio.
- [ ] Código de `js/members.js` con la función `getMembers()` implementada.
- [ ] `README.md` completo con las secciones requeridas.

---

### 🌊 ZONA 3 — Navegante del Conflicto

> *"Dos senderos convergieron en el mismo punto. Solo el escuadrón puede elegir el camino correcto."*

**Objetivo:** Sincronizar con el repositorio remoto, resolver un conflicto de fusión y crear un Pull Request completo.

#### Escenario de la misión

Otro integrante del equipo (o el Comandante Anfibio) también realizó cambios en `js/expeditions.js` simultáneamente. Al intentar fusionar los cambios de `main` en tu rama, el sistema detecta un **conflicto**: dos versiones distintas del mismo bloque de código. El sistema no puede elegir por sí solo — esa decisión corresponde al escuadrón.

Además, `js/expeditions.js` contiene un **bug intencional**: la función `calcularDistanciaTotal()` concatena strings en lugar de sumar números. Deberás identificarlo y corregirlo.

#### Misiones

| # | Misión | Comando principal |
|---|--------|-------------------|
| 3.1 | Actualizar tu repositorio local con los últimos cambios del remoto. | `git fetch origin` + `git pull origin main` |
| 3.2 | Fusionar los cambios de `main` hacia tu rama local y observar el conflicto generado. | `git merge main` |
| 3.3 | Abrir el archivo en conflicto, analizar ambas versiones (`HEAD` vs. `main`) y resolverlo manualmente conservando lo correcto de cada versión. | Editor de texto |
| 3.4 | Corregir el bug en `calcularDistanciaTotal()`: la operación debe sumar números, no concatenar. Agregar el archivo al staging y registrar los cambios. | `git add`, `git commit` |
| 3.5 | Crear un **Pull Request** en GitHub con título descriptivo, descripción detallada de los cambios y referencia a los archivos modificados. | GitHub — interfaz web |

#### Anatomía de un Pull Request bien hecho

```markdown
TÍTULO: fix(expeditions): corrige calcularDistanciaTotal y resuelve conflicto de merge

DESCRIPCIÓN:
## ¿Qué cambia este PR?
- Se corrigió la función `calcularDistanciaTotal()` que concatenaba strings
  en lugar de sumar los valores numéricos de cada expedición.
- Se resolvió el conflicto de merge en `js/expeditions.js` conservando
  la lógica actualizada de ambas ramas.

## Archivos modificados
- `js/expeditions.js` — corrección de bug y resolución de conflicto.

## Evidencia
![Captura del conflicto resuelto](capturas/conflicto_resuelto.png)

## Notas adicionales
El bug causaba que el total se mostrara como "102030" en lugar de "60".
```

#### Evidencias para la medalla 🌊

- [ ] Captura del conflicto en el editor antes de resolverlo (marcadores `<<<<<<`, `======`, `>>>>>>`).
- [ ] Captura del archivo con el conflicto ya resuelto.
- [ ] Enlace al Pull Request creado en GitHub con descripción completa.
- [ ] Historial de commits que muestre la resolución del conflicto y la corrección del bug.

---

### 🦅 ZONA 4 — Guardián del Repositorio

> *"No eres solo un constructor. El escuadrón necesita guardianes que cuiden la calidad del código."*

**Objetivo:** Revisar el Pull Request de otro integrante del equipo con criterio técnico y aprobar o solicitar mejoras.

#### Misiones

| # | Misión | Acción en GitHub |
|---|--------|-----------------|
| 4.1 | Revisar el Pull Request asignado por el Comandante Anfibio. Examinar todos los archivos modificados. | Pestaña *Files changed* |
| 4.2 | Dejar **al menos 2 comentarios de revisión** en líneas específicas del código: uno positivo (reconocimiento) y uno con sugerencia concreta de mejora. | Botón *Add comment* en una línea específica |
| 4.3 | Tomar una decisión de revisión formal: Aprobar ✅ si el código cumple los estándares, o solicitar cambios 🔄 con justificación clara. | *Review changes* → Submit review |
| 4.4 | Una vez aprobado tu propio PR por un compañero, ejecutar el merge hacia `main`. | *Merge pull request* → *Confirm merge* |
| 4.5 | Verificar localmente que `main` contiene todos los cambios integrados del equipo. | `git checkout main` + `git pull` + `git log --oneline` |

#### ¿Cómo es un comentario de revisión de calidad?

```diff
- "Está bien, funciona."
  ↑ ❌ No aporta valor. Es genérico e inútil para el crecimiento del desarrollador.

+ "La función getMembers() retorna correctamente el arreglo.
+  Sugerencia: considera agregar un campo 'email' a cada objeto para
+  que el perfil del miembro sea más completo y reutilizable en otras
+  partes de la aplicación."
  ↑ ✅ Reconoce lo correcto, propone mejora específica y explica el porqué.
```

#### Evidencias para la medalla 🦅

- [ ] Capturas de los 2+ comentarios de revisión realizados en el PR ajeno (con el código al que refieren).
- [ ] Captura de la decisión de revisión (Approved o Changes requested).
- [ ] Captura del PR propio con estado **Approved** y luego **Merged**.
- [ ] Captura de `git log --oneline main` con los commits del equipo integrados.

---

## 4. Evidencias de Aprendizaje

Todas las evidencias se organizan en una carpeta `evidencias/[tu-nombre]/` dentro del repositorio, o en un documento `evidencias_[tu-nombre].md` adjunto al PR final.

| Zona | Evidencia requerida | Formato |
|------|---------------------|---------|
| 🐸 Zona 1 | Configuración de Git (`git config --list`) | Captura de pantalla |
| 🐸 Zona 1 | Clonación exitosa del repositorio | Captura de pantalla |
| 🐸 Zona 1 | Historial `git log --oneline --graph` ejecutado | Captura de pantalla |
| 🐸 Zona 1 | Archivo `bitacora_zona1_[nombre].md` en GitHub | Enlace al archivo |
| 🌿 Zona 2 | Historial de 3+ commits con protocolo de mensajes | Enlace al historial en GitHub |
| 🌿 Zona 2 | Rama publicada visible en *Branches* | Captura de pantalla |
| 🌿 Zona 2 | Función `getMembers()` implementada | Captura o enlace al archivo |
| 🌊 Zona 3 | Conflicto visible en el editor (antes de resolver) | Captura de pantalla |
| 🌊 Zona 3 | Conflicto resuelto en el editor (después) | Captura de pantalla |
| 🌊 Zona 3 | Pull Request creado con descripción completa | Enlace al PR |
| 🦅 Zona 4 | Comentarios de Code Review en PR ajeno | Capturas de pantalla |
| 🦅 Zona 4 | Decisión de revisión (Approved / Changes requested) | Captura de pantalla |
| 🦅 Zona 4 | PR propio con estado Merged | Captura de pantalla |
| 🦅 Zona 4 | `git log --oneline main` con todos los merges | Captura de pantalla |

---

## 5. Criterios de Evaluación

Rúbrica del escuadrón dev-anfibios — puntuación máxima: **30 puntos**.

| Criterio | 🟢 Excelente (5) | 🔵 Bueno (3) | 🟡 Suficiente (2) | 🔴 Insuficiente (1) |
|----------|-----------------|-------------|------------------|---------------------|
| **Configuración y clonación** | Entorno configurado correctamente, SSH o HTTPS funcional | Clonación correcta con configuración básica | Lograda con ayuda del equipo | No logró clonar el repositorio |
| **Uso de ramas** | Nombre descriptivo, commits aislados por funcionalidad | Rama creada y usada correctamente | Rama creada sin seguir convención de nombres | Trabajó directamente en `main` |
| **Calidad de commits** | Mensajes convencionales, commits atómicos y frecuentes | Mensajes claros y frecuencia aceptable | Mensajes genéricos o commits agrupados | Sin mensajes o commits inexistentes |
| **Resolución de conflictos** | Resuelta de forma autónoma con comprensión del proceso | Resuelta con orientación mínima del equipo | Parcialmente resuelta o con errores | No logró resolver el conflicto |
| **Pull Request** | Descripción completa, título convencional, evidencia incluida | PR con descripción básica y funcional | PR sin descripción o con errores | No creó el Pull Request |
| **Code Review** | Comentarios específicos, constructivos y en líneas concretas | Revisión con comentarios relevantes | Revisión superficial o genérica | No realizó la revisión de código |

**Escala de calificación final:**
```
27–30 pts → 🏆 Maestro Anfibio    (Excelente)
21–26 pts → 🐸 Anfibio Completo   (Bueno)
15–20 pts → 🌱 Renacuajo Activo   (Suficiente)
 < 15 pts → 📋 En Adaptación      (Necesita refuerzo)
```

---

## 6. Preguntas de Reflexión

### 1. ¿Qué ventajas ofrece Git frente a guardar múltiples versiones de un archivo manualmente?

Guardar versiones de forma manual (como `codigo_v1.js`, `codigo_v2_bueno.js`, `codigo_FINAL_FINAL.js`) genera un caos inevitable: archivos duplicados, espacio desperdiciado, ausencia de metadatos (quién cambió qué y por qué) y riesgo constante de sobreescribir trabajo de otra persona.

Git resuelve esto almacenando únicamente los **cambios diferenciales (deltas)** entre versiones, no copias completas, lo que hace el historial compacto y eficiente. Cada versión registrada incluye autor, fecha precisa y descripción del cambio, convirtiendo el historial en una **bitácora auditable del proyecto**. Si se introduce un error, `git revert` o `git checkout` permiten regresar a cualquier estado anterior en segundos. En proyectos colaborativos, la coordinación manual es imposible: dos personas modificando el mismo archivo simultáneamente en Git se gestiona mediante ramas y algoritmos de fusión automática, evitando pérdida de trabajo.

### 2. ¿Por qué es importante trabajar mediante ramas?

Las ramas permiten **desarrollo paralelo y completamente aislado**. Cuando un desarrollador crea una rama, obtiene una copia de trabajo independiente del código estable de producción (`main`), lo que le permite experimentar, construir funcionalidades o corregir bugs sin poner en riesgo el trabajo del resto del equipo.

Este aislamiento es crítico en proyectos activos: `main` siempre debe estar en un estado funcional y desplegable. Sin ramas, cualquier error de un desarrollador afectaría inmediatamente a todos. Las ramas también facilitan revisiones de código más precisas (el PR muestra exactamente qué cambió), permiten revertir funcionalidades completas si son necesario y son la base de flujos de trabajo profesionales como **Git Flow** o **GitHub Flow**, que estructuran el ciclo de vida del código desde desarrollo hasta producción.

### 3. ¿Qué beneficios aportan los Pull Requests en un equipo de desarrollo?

Los Pull Requests son el principal **mecanismo de control de calidad** antes de que cualquier código llegue a `main`. Al menos otro desarrollador revisa los cambios propuestos, detectando errores lógicos, vulnerabilidades, malas prácticas o inconsistencias con los estándares del equipo que el autor pudo pasar por alto por exceso de familiaridad con su propio código.

Más allá de la revisión técnica, los PRs generan un **registro histórico de decisiones**: la discusión queda documentada en GitHub, permitiendo a cualquier integrante (incluso futuro) entender por qué se tomó cierta decisión. También fomentan una **cultura de responsabilidad compartida**: el código deja de pertenecer a una sola persona y se convierte en propiedad del equipo. Para los programadores junior, el Code Review es además una herramienta de aprendizaje acelerado: reciben retroalimentación directa y contextualizada de desarrolladores más experimentados.

### 4. ¿Cómo puede un líder técnico verificar que todos los integrantes están contribuyendo al proyecto?

GitHub ofrece herramientas de visibilidad directas: la pestaña **Insights → Contributors** muestra gráficas de commits por autor con filtros por período. El comando `git log --author="[nombre]"` filtra el historial de contribuciones de una persona específica. La pestaña **Pull Requests** registra quién creó PRs, quién los revisó y quién los aprobó.

En un contexto ágil real, integrar GitHub con **GitHub Projects** permite asociar commits y PRs con tareas del sprint, dando una visión cruzada: no solo cuánto commitea cada persona, sino si su trabajo corresponde con los objetivos comprometidos. Herramientas como **Jira** o **Azure DevOps** llevan esta trazabilidad aún más lejos, vinculando código con historias de usuario, criterios de aceptación y velocidad del equipo.

### 5. ¿Qué habilidades técnicas y de colaboración desarrolla un programador al utilizar Git y GitHub?

**Habilidades técnicas:**
- Pensar en cambios **incrementales y atómicos** en lugar de modificaciones masivas sin estructura.
- Manejo fluido de la **línea de comandos** y comprensión del modelo interno de Git (árbol de commits, índice, working directory).
- Capacidad para **leer y resolver conflictos de fusión** sin perder el trabajo del equipo.
- Comprensión de flujos de trabajo profesionales (Git Flow, Trunk-Based Development).

**Habilidades de colaboración:**
- Escribir **mensajes de commit claros** que comuniquen la intención del cambio, no solo lo que se modificó.
- **Documentar PRs** de forma que cualquier compañero entienda el contexto y propósito del cambio.
- Dar y recibir **feedback técnico constructivo** en los Code Reviews, asumiendo que las sugerencias mejoran el producto, no critican a la persona.
- Respetar y aplicar las **convenciones del equipo** (`CONTRIBUTING.md`, branching model, naming conventions).

Estas competencias son transversales: un desarrollador que domina Git y GitHub puede integrarse con facilidad a cualquier equipo de software moderno, independientemente del lenguaje o tecnología del proyecto.

---

## 7. Desafío Extra — Arsenal Avanzado

> *"El pantano tiene más secretos. Los mejores anfibios conocen todo el territorio."*

Las siguientes herramientas complementan a Git y GitHub en entornos profesionales de desarrollo:

| Herramienta | Categoría | Descripción | Beneficio para el equipo |
|-------------|-----------|-------------|--------------------------|
| **GitHub Projects** | Gestión ágil | Tablero Kanban y Scrum integrado directamente en GitHub, vinculado con Issues y PRs. | Visibilidad del progreso del sprint sin salir del ecosistema GitHub. Elimina la necesidad de herramientas externas para equipos pequeños. |
| **GitHub Issues** | Seguimiento de tareas | Sistema de tickets para reportar bugs, proponer mejoras y asignar tareas, vinculable con commits y PRs mediante palabras clave (`closes #12`). | Trazabilidad completa: cada cambio en el código puede rastrearse hasta el issue que lo originó. |
| **GitHub Actions** | CI/CD y automatización | Motor de automatización que ejecuta flujos de trabajo (lint, pruebas, builds, despliegues) automáticamente al hacer push o abrir un PR. | Garantiza calidad continua: ningún código defectuoso llega a `main` sin pasar por las verificaciones automáticas del equipo. |
| **GitLab** | Plataforma DevOps completa | Alternativa a GitHub con repositorios Git, CI/CD integrado, gestión de proyectos y opciones de autoalojamiento (self-hosted). | Ideal para empresas que requieren control total de su infraestructura o integración con pipelines DevOps existentes. |
| **Jira** | Gestión de proyectos ágiles | Plataforma de gestión con tableros Scrum/Kanban, sprints, epics e integración bidireccional con GitHub. | Conecta código con objetivos de negocio: cada PR puede vincularse a una historia de usuario del sprint, dando visibilidad completa al equipo. |
| **Azure DevOps** | Suite DevOps Microsoft | Plataforma empresarial con repos Git (Azure Repos), pipelines CI/CD (Azure Pipelines), gestión de sprints (Azure Boards) y pruebas (Azure Test Plans). | Integración profunda con el ecosistema Microsoft (Azure Cloud, Visual Studio). Opción robusta para organizaciones con infraestructura Microsoft. |

La combinación estratégica de estas herramientas con Git y GitHub permite a los equipos mantener **visibilidad completa del proyecto**, automatizar procesos repetitivos que consumen tiempo valioso, y escalar la colaboración de forma ordenada incluso con equipos distribuidos geográficamente o en múltiples zonas horarias.

---

```
╔══════════════════════════════════════════════════════════════╗
║         MISIÓN COMPLETADA — OPERACIÓN GITSWAMP               ║
║══════════════════════════════════════════════════════════════║
║                                                              ║
║   Has cruzado el pantano digital de extremo a extremo.       ║
║   Tus huellas quedaron registradas en el historial.          ║
║   Tu código fue revisado y aprobado por el escuadrón.        ║
║                                                              ║
║   Bienvenido/a al equipo, Desarrollador/a Anfibio.           ║
║                                                              ║
║   El repositorio es más fuerte con tu contribución.          ║
║                                                              ║
║   — Comando Anfibio, Base Remota                             ║
╚══════════════════════════════════════════════════════════════╝
```

---

*Propuesta diseñada por el equipo dev-anfibios con base en escenarios reales de desarrollo colaborativo · Junio 2026*
