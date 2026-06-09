# 🚀 Operación: GitLaunch
### Programa de Capacitación en Git y GitHub para Nuevos Ingenieros de Software

> **Materia:** Desarrollo y Gestión de Software  
> **Universidad:** Tecnológica del Norte de Guanajuato (UTNG)  
> **Equipo:** Karen Anahí Padrón Martínez · Brandon Gustavo Mendoza Amaro · Lizeth Ramírez Ramírez  
> **Fecha:** Junio 2026

---

## 📡 Mensaje de la Base

```
TRANSMISIÓN ENTRANTE — CENTRO DE CONTROL DEVCORE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Bienvenido/a, Ingeniero/a.

Has sido seleccionado/a para unirte a la Misión DevShop,
el proyecto más importante de nuestra estación.

Antes de poder operar el sistema de producción,
deberás completar 4 fases de entrenamiento.

Cada fase que superes te acercará más al núcleo del equipo.
No hay atajos. Solo commits, ramas y colaboración.

Que el código esté contigo.

— Comandante del Repositorio
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 📑 Tabla de Contenidos

1. [Objetivo de Aprendizaje](#1-objetivo-de-aprendizaje)
2. [La Dinámica — Operación GitLaunch](#2-la-dinámica--operación-gitlaunch)
3. [Fases de la Misión](#3-fases-de-la-misión)
4. [Evidencias de Aprendizaje](#4-evidencias-de-aprendizaje)
5. [Criterios de Evaluación](#5-criterios-de-evaluación)
6. [Preguntas de Reflexión](#6-preguntas-de-reflexión)
7. [Desafío Extra — Módulos Avanzados](#7-desafío-extra--módulos-avanzados)

---

## 1. Objetivo de Aprendizaje

Al completar la **Operación GitLaunch**, el nuevo Ingeniero será capaz de:

- 🛸 Clonar repositorios remotos y configurar su entorno local con Git.
- 🌿 Crear y gestionar **ramas** para desarrollar funcionalidades de forma aislada.
- 📝 Registrar cambios mediante **commits** con mensajes claros y descriptivos.
- 🔄 Sincronizar su trabajo usando `push` y `pull` con el repositorio remoto.
- ⚔️ Resolver **conflictos de fusión** en escenarios colaborativos reales.
- 🔀 Crear y gestionar **Pull Requests** para proponer e integrar cambios.
- 🔍 Revisar el código de otros mediante **Code Reviews** constructivos.
- 🗺️ Comprender el flujo **Git Flow básico** utilizado en equipos ágiles.

---

## 2. La Dinámica — Operación GitLaunch

### 🌌 El universo de la misión

La **Operación GitLaunch** convierte el aprendizaje de Git en una misión espacial colaborativa. El nuevo integrante del equipo es un **Ingeniero de Software recién reclutado** por la agencia **DevCore**, cuya misión es mantener operativo el sistema `devshop-api` — la plataforma que abastece a toda la estación espacial.

El repositorio es la **estación**. Las ramas son **naves de exploración**. Los commits son **reportes de vuelo**. Los Pull Requests son **solicitudes de acoplamiento** que el equipo debe aprobar antes de integrar cualquier módulo a la estación principal.

### 👥 Modalidad

| Aspecto | Detalle |
|--------|---------|
| Participantes | Equipo de 3 ingenieros (Karen, Brandon, Lizeth) |
| Proyecto base | `devshop-api` — API REST ficticia en Node.js |
| Plataforma | GitHub (repositorio compartido del equipo) |
| Formato | 4 fases progresivas con sistema de insignias |
| Rol del facilitador | Comandante del Repositorio (líder técnico) |

### 🏅 Sistema de Insignias

Cada fase completada otorga una insignia al Ingeniero. Las insignias se registran en el `README.md` del repositorio como historial de logros del equipo:

| Insignia | Fase | Nombre |
|----------|------|--------|
| 🛸 | Fase 1 | Explorador de la Estación |
| ⚙️ | Fase 2 | Ingeniero de Módulos |
| 🌊 | Fase 3 | Navegante de Conflictos |
| 🔭 | Fase 4 | Inspector de Misión |

### 📡 El proyecto base

```
devshop-api/
├── README.md           ← incompleto, el Ingeniero lo completa en Fase 2
├── src/
│   ├── products.js     ← módulo con bug intencional (Fase 3)
│   └── users.js        ← módulo vacío para implementar (Fase 2)
├── .gitignore
└── CONTRIBUTING.md     ← protocolo oficial de la estación
```

### ⚡ Reglas de la estación

```
PROTOCOLO DEVCORE — NORMAS DE CONTRIBUCIÓN
──────────────────────────────────────────
1. Ningún Ingeniero trabaja directamente en `main`.
   main es el núcleo de la estación. Es intocable.

2. Cada nave (rama) debe tener nombre descriptivo:
   feature/nombre-descripcion

3. Todo reporte de vuelo (commit) debe ser claro:
   tipo(scope): descripción breve

4. Ningún módulo se acopla sin revisión del equipo.
   Los Pull Requests requieren al menos 1 aprobación.

5. Los conflictos se resuelven. No se evaden.
──────────────────────────────────────────
```

---

## 3. Fases de la Misión

---

### 🛸 FASE 1 — Explorador de la Estación

> *"Antes de tocar cualquier sistema, debes conocer la estación."*

**Objetivo:** Conectarse a la estación y entender su estructura.

#### Misiones

| # | Misión | Comando clave |
|---|--------|---------------|
| 1.1 | Crear cuenta en GitHub y configurar Git local con nombre y correo. | `git config --global` |
| 1.2 | Clonar el repositorio `devshop-api` vía HTTPS o SSH. | `git clone` |
| 1.3 | Explorar la estructura del proyecto. Leer `README.md` y `CONTRIBUTING.md`. | `ls`, `cat` |
| 1.4 | Ver el historial de misiones anteriores. | `git log --oneline` |
| 1.5 | Crear el archivo `bitacora/bitacora_fase1.md` con 3 observaciones sobre el proyecto y commitearlo. | `git add`, `git commit` |

#### Reporte de vuelo esperado

```
docs(bitacora): registra observaciones iniciales de la estacion
```

#### Evidencias para la insignia 🛸

- [ ] Captura del terminal mostrando la clonación exitosa.
- [ ] Captura del `git log --oneline` ejecutado.
- [ ] Archivo `bitacora/bitacora_fase1.md` visible en GitHub.

---

### ⚙️ FASE 2 — Ingeniero de Módulos

> *"La estación necesita nuevos módulos. Es hora de construir."*

**Objetivo:** Crear una nave (rama), construir funcionalidades y enviar reportes de vuelo claros.

#### Misiones

| # | Misión | Comando clave |
|---|--------|---------------|
| 2.1 | Lanzar tu nave: crear rama `feature/tu-nombre-modulo`. | `git checkout -b` |
| 2.2 | Completar el `README.md`: descripción del proyecto, tecnologías, instrucciones de instalación y uso. | editor |
| 2.3 | Activar el módulo de usuarios: implementar `getUsers()` en `src/users.js` retornando 3 usuarios ficticios. | editor |
| 2.4 | Enviar al menos **3 reportes de vuelo (commits)** con mensajes que sigan el protocolo. | `git commit -m` |
| 2.5 | Transmitir la nave al repositorio remoto. | `git push origin` |

#### Ejemplos de reportes de vuelo válidos

```
docs(readme): agrega instrucciones de instalacion
feat(users): implementa funcion getUsers con datos ficticios
docs(readme): completa seccion de tecnologias usadas
```

#### Evidencias para la insignia ⚙️

- [ ] Historial de GitHub con 3+ commits siguiendo el protocolo.
- [ ] Captura de la rama publicada en el repositorio remoto.
- [ ] `src/users.js` con la función `getUsers()` implementada.

---

### 🌊 FASE 3 — Navegante de Conflictos

> *"Dos naves intentaron modificar el mismo módulo. Hay interferencia. Tú debes resolverla."*

**Objetivo:** Sincronizar con la estación, resolver una colisión de señales (conflicto) y solicitar acoplamiento (PR).

#### Escenario de la misión

El **Ingeniero de turno** (otro integrante del equipo) también modificó `src/products.js` en su propia rama. Al intentar fusionar los cambios, se detecta una **colisión de señales** (merge conflict). El sistema no puede resolverlo solo — necesita intervención humana.

#### Misiones

| # | Misión | Comando clave |
|---|--------|---------------|
| 3.1 | Actualizar la nave con los últimos datos de la estación. | `git pull origin main` |
| 3.2 | Fusionar la señal de `main` hacia tu rama. Detectar la colisión. | `git merge main` |
| 3.3 | Abrir el archivo en conflicto, analizar ambas versiones y **resolver manualmente** eligiendo qué código conservar. | editor |
| 3.4 | Reparar el bug intencional en `src/products.js`: la función `calculateTotal()` multiplica en vez de sumar. | editor |
| 3.5 | Solicitar acoplamiento: crear un **Pull Request** con título, descripción y referencia a los archivos modificados. | GitHub UI |

#### Anatomía de un buen Pull Request

```
TÍTULO:    fix(products): corrige calculateTotal y resuelve conflicto de merge

DESCRIPCIÓN:
## ¿Qué cambia este PR?
- Corregida la función `calculateTotal()` que multiplicaba en vez de sumar.
- Resuelto conflicto de merge en `src/products.js` conservando lógica del equipo.

## Archivos modificados
- `src/products.js`

## Evidencia
[captura del conflicto resuelto]
```

#### Evidencias para la insignia 🌊

- [ ] Captura del conflicto en el editor (antes y después de resolverlo).
- [ ] Enlace al Pull Request creado con descripción completa.
- [ ] Historial de commits mostrando la resolución del conflicto y la corrección del bug.

---

### 🔭 FASE 4 — Inspector de Misión

> *"No eres solo un constructor. Eres parte del equipo que protege la estación."*

**Objetivo:** Revisar el módulo de otro Ingeniero y aprobar (o cuestionar) su acoplamiento a la estación.

#### Misiones

| # | Misión | Acción en GitHub |
|---|--------|-----------------|
| 4.1 | Revisar el Pull Request asignado por el Comandante. | Pestaña *Files changed* |
| 4.2 | Dejar **al menos 2 comentarios**: uno positivo y uno con sugerencia de mejora concreta. | *Add comment* en línea |
| 4.3 | Decidir: ¿el módulo está listo para la estación? Aprobar ✅ o solicitar cambios 🔄. | *Review changes* |
| 4.4 | Una vez que tu propio PR sea aprobado, ejecutar el acoplamiento final. | *Merge pull request* |
| 4.5 | Verificar que `main` tiene el historial completo de todos los módulos integrados. | `git log --oneline main` |

#### Diferencia entre un buen y mal comentario de revisión

```diff
- "Está bien."                          ← ❌ No aporta nada

+ "La lógica de getUsers() funciona     ← ✅ Específico y constructivo
   correctamente. Considera usar
   nombres más representativos para
   los usuarios ficticios (ej: objetos
   con nombre, email, rol)."
```

#### Evidencias para la insignia 🔭

- [ ] Capturas de los 2+ comentarios de revisión en el PR ajeno.
- [ ] Captura del PR propio con estado: **Approved** y **Merged**.
- [ ] Captura de `git log --oneline main` mostrando todos los merges del equipo.

---

## 4. Evidencias de Aprendizaje

Todas las evidencias se entregan organizadas en una carpeta `evidencias/` dentro del repositorio o en un documento con el nombre del Ingeniero.

| Fase | Evidencia | Formato |
|------|-----------|---------|
| 🛸 Fase 1 | Terminal con clonación exitosa | Captura de pantalla |
| 🛸 Fase 1 | Salida de `git log --oneline` | Captura de pantalla |
| 🛸 Fase 1 | Archivo `bitacora_fase1.md` | Visible en GitHub |
| ⚙️ Fase 2 | Historial de 3+ commits con protocolo | Link a GitHub |
| ⚙️ Fase 2 | Rama publicada en repositorio remoto | Captura de pantalla |
| 🌊 Fase 3 | Conflicto antes y después de resolverse | Capturas de pantalla |
| 🌊 Fase 3 | Pull Request con descripción completa | Link al PR |
| 🔭 Fase 4 | Comentarios de Code Review en PR ajeno | Capturas de pantalla |
| 🔭 Fase 4 | PR propio aprobado y mergeado | Captura de pantalla |
| 🔭 Fase 4 | `git log` de `main` con todos los merges | Captura de pantalla |

---

## 5. Criterios de Evaluación

Rúbrica de la misión — calificación máxima: **28 puntos**.

| Criterio | 🟢 Excelente (4) | 🔵 Bueno (3) | 🟡 Regular (2) | 🔴 Insuficiente (1) |
|----------|-----------------|-------------|---------------|-------------------|
| **Clonación y configuración** | Sin errores, SSH configurado | Clonado correctamente | Con ayuda del equipo | No logró clonar |
| **Uso de ramas** | Nombre descriptivo, aislamiento correcto | Rama creada y usada | Rama sin commits claros | Trabajó en `main` |
| **Commits (mensaje y frecuencia)** | Mensajes claros, commits atómicos | Mensajes aceptables | Mensajes genéricos | Sin mensajes |
| **Resolución de conflictos** | Resuelta de forma autónoma | Resuelta con orientación | Parcialmente resuelta | No logró resolverla |
| **Pull Request** | Completo con descripción detallada | Con descripción básica | Sin descripción | No creó PR |
| **Code Review** | Comentarios constructivos y precisos | Comentó cambios relevantes | Revisión superficial | No realizó revisión |
| **Entrega de evidencias** | Todas completas y organizadas | La mayoría entregadas | Parciales o desordenadas | No entregó |

**Escala final:**
```
25–28 pts → 🏆 Comandante (Excelente)
20–24 pts → 🚀 Piloto      (Bueno)
14–19 pts → 🛠️ Cadete      (Suficiente)
 < 14 pts → 📋 En entrenamiento (Insuficiente)
```

---

## 6. Preguntas de Reflexión

### 1. ¿Qué ventajas ofrece Git frente a guardar múltiples versiones de un archivo manualmente?

Guardar versiones manualmente (`archivo_v1.js`, `archivo_v2_final.js`, `archivo_v2_ESTE_SÍ.js`) es una práctica que escala muy mal. Git almacena únicamente los **cambios diferenciales** entre versiones (deltas), no copias completas, lo que hace que el historial sea ligero y eficiente. Cada snapshot está etiquetado con autor, fecha y descripción, convirtiendo el historial en una **bitácora auditable del proyecto**. Si algo se rompe, `git revert` permite regresar al estado anterior en segundos. En equipos, la coordinación manual genera pérdida de trabajo cuando dos personas modifican el mismo archivo simultáneamente; Git lo resuelve con ramas aisladas y algoritmos de fusión automática.

### 2. ¿Por qué es importante trabajar mediante ramas?

Las ramas permiten **desarrollo paralelo y seguro**. Al crear una rama, el desarrollador obtiene un entorno completamente aislado del código estable de producción (`main`), por lo que puede experimentar y probar ideas sin poner en riesgo el trabajo del equipo. Este aislamiento es crítico en proyectos con usuarios reales donde `main` siempre debe estar en estado desplegable. Las ramas también facilitan la organización del trabajo: cada funcionalidad tiene su propio contexto, lo que hace que los **Code Reviews sean más precisos**. Modelos como **Git Flow** o **GitHub Flow** estandarizan el uso de ramas, reduciendo la fricción de coordinación en el equipo.

### 3. ¿Qué beneficios aportan los Pull Requests en un equipo de desarrollo?

Los Pull Requests son el principal **punto de revisión de calidad** antes de que cualquier cambio llegue a `main`. Al menos otro desarrollador revisa el código, detectando errores lógicos, malas prácticas o violaciones del estándar del equipo que el autor pudo pasar por alto. Además, los PRs crean un **registro histórico** de decisiones técnicas (la discusión queda documentada), facilitan el **onboarding** de nuevos integrantes y fomentan una cultura de responsabilidad compartida: el código pertenece al equipo, no a una sola persona.

### 4. ¿Cómo puede un líder técnico verificar que todos los integrantes están contribuyendo al proyecto?

GitHub ofrece herramientas concretas: la pestaña **Insights → Contributors** muestra gráficas de commits por autor. El comando `git log --author` filtra contribuciones por persona. Los **Pull Requests y Code Reviews** quedan registrados, mostrando quién creó PRs, quién los revisó y quién aprobó cambios. En un contexto ágil, integrar GitHub con **GitHub Projects** o **Jira** permite cruzar la actividad de código con las tareas del sprint, dando una visión completa: no solo si alguien commitea mucho, sino si sus commits corresponden a las historias de usuario comprometidas.

### 5. ¿Qué habilidades técnicas y de colaboración desarrolla un programador al utilizar Git y GitHub?

**Técnicas:** pensar en cambios incrementales y atómicos, manejo de la línea de comandos, comprensión del modelo de datos de Git (árbol de commits, DAG) y destreza para resolver conflictos sin perder trabajo.

**De colaboración:** escribir mensajes de commit claros, documentar PRs para que otros los entiendan, dar y recibir **feedback técnico constructivo** en los Code Reviews, y respetar las convenciones del equipo (`CONTRIBUTING.md`, branching model). Estas habilidades son indispensables en el mercado laboral: un desarrollador que no usa Git profesionalmente tiene una barrera importante para integrarse a cualquier equipo de software moderno.

---

## 7. Desafío Extra — Módulos Avanzados

> *"La misión no termina con el merge. Los mejores ingenieros conocen todo el arsenal."*

Las siguientes herramientas extienden las capacidades de Git y GitHub para equipos profesionales:

| Módulo | Herramienta | Descripción | Beneficio para el equipo |
|--------|-------------|-------------|--------------------------|
| 📋 | **GitHub Projects** | Tablero Kanban integrado en GitHub para gestionar tareas e historias de usuario. | Visibilidad del progreso del sprint sin salir de GitHub. |
| 🐛 | **GitHub Issues** | Seguimiento de errores, mejoras y tareas vinculado al código. | Relaciona commits y PRs con issues específicos; trazabilidad completa. |
| ⚡ | **GitHub Actions** | CI/CD que automatiza pruebas, builds y despliegues al hacer push o PR. | Reduce errores humanos y garantiza calidad continua en cada entrega. |
| 🦊 | **GitLab** | Plataforma DevOps completa con repositorios, CI/CD y gestión integrados. | Alternativa all-in-one; ideal para empresas que requieren autoalojamiento. |
| 🗂️ | **Jira** | Gestión ágil con tableros Scrum/Kanban, sprints y epics. | Integración con GitHub para asociar código con tareas del sprint. |
| ☁️ | **Azure DevOps** | Suite de Microsoft con repos Git, pipelines CI/CD y gestión de pruebas. | Integración profunda con el ecosistema Microsoft; opción empresarial robusta. |

La combinación de estas herramientas con Git y GitHub permite a los equipos mantener **visibilidad total del proyecto**, automatizar procesos repetitivos y escalar la colaboración de forma ordenada, incluso con equipos distribuidos geográficamente.

---

```
FIN DE TRANSMISIÓN — OPERACIÓN GITLAUNCH
─────────────────────────────────────────
Misión completada.
El repositorio es más fuerte con tu contribución.

Bienvenido/a al equipo, Ingeniero/a.
─────────────────────────────────────────
```

*Propuesta diseñada con base en escenarios reales de desarrollo colaborativo · Junio 2026*